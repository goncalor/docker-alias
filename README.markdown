docker-alias
============

docker-alias provides you with aliases for some common [Docker][docker-com] tasks.

[docker-com]: https://www.docker.com


Aliases
-------

All aliases start with `docker-`. The rest of the alias describes more or less what the command does. The aliases may seem long, but once you type `docker-` and two more characters your shell's tab completion should figure the rest.

**`docker-rm-all`** Removes all stopped containers.

**`docker-stop-all`** Stops all running containers, giving them time to stop.

**`docker-force-rm-all`** Stops and then removes all containers.

**`docker-volume-rm-all`** Removes all volumes not in use.

**`docker-shark`** Stops and removes all containers and *removes all volumes*. (Be careful!)


Installation
------------

Installing is as simple as downloading a file to your computer and making sure it is sourced when you log in.

### Download

Create a new directory and move into it

    mkdir -p ~/.config/docker-alias
    cd ~/.config/docker-alias

Download `docker.alias` with `wget` or `curl`

    wget https://raw.githubusercontent.com/goncalor/docker-alias/master/docker.alias
    # or
    curl https://raw.githubusercontent.com/goncalor/docker-alias/master/docker.alias > docker.alias

Go back to your original directory

    cd -

### Source

Add the following command to your `.bashrc`, `.zshrc`, or other script that suits your case

    source ~/.config/docker-alias/docker.alias

That will make the new aliases available the next time you open a terminal. If you want to make them available right now just run that same command on your current shell.
