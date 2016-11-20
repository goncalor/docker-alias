docker-alias
============


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

That will make the new aliases available the next time you log in. If you want to make them available right now just run that same command on your current shell.
