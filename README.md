# wc
This script is a wrapper for the wc binary printing WC (lavatory) ascii art before doing the work

## Installation:
### Download the script:
    curl -o ~/.wc https://raw.githubusercontent.com/AMD1212/wc/master/wc
    chmod +x ~/.wc
### Set the alias:
    echo $SHELL
#### bash:
    echo 'alias wc=~/.wc'>>~/.bashrc
#### zsh:
    echo 'alias wc=~/.wc'>>~/.zshrc
#### ksh:
    echo 'alias wc=~/.wc'>>~/.kshrc

## Removal:
    Undo what you did (CTRL-Z may not work)

## Usage: wc [OPTIONS]

### Options:
    -l          Shows a urinal
    -c          Shows a cat-litter box
    -w          Reminds you to wash your hands
    -m          Displays a fancy monkey throwing poop

Without a option the script shows a fancy lavatory.

The cool ascii arts are written to STDERR so the wrapper script should not break scripts using wc.

Have fun!


