# Dotfiles

All of my dotfiles collected in one handy git repo,
for use either with my other automation scripts or 
just by running: 

```sh
./setup.sh
```

This will copy all local directories to ~/.config/

# TODO:
- symlink to this repo instead
- pull new changes from github!
- find out how I can run a custom hook after apt for example finishes just to run the update script?!
- change our mechanism to run a post install hook using apt.conf see (https://unix.stackexchange.com/questions/70686/how-to-run-a-command-after-apt-get-upgrade)