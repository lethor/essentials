# Web Development Essentials

My basic needs for a Unix environment.  I make Web sites.

## Setup

Run create-symlinks to link your dotfiles and ~/bin directory.

~~~ sh
git clone <repo url>
cd essentials/
./create-symlinks
~~~

Doing so creates a symlink called "this" in the repository root, pointing to the
appropriate directory for your operating system.  This way you can have
different implementations on different systems as needed.

Copy the example gitconfig, then tell git your name and email address:

~~~ sh
cp -i this/dotfiles/gitconfig ~/.gitconfig
sensible-editor ~/.gitconfig
~~~

The directory "this/setup" contains additional setup scripts.

* install-essentials installs software packages I find crucial, like rsync.

* tweak-ui alters the user interface to my liking.  For example: it turns on
  numlock, stops the cursor from blinking, and turns off the terminal bell.

~~~ sh
cd this/setup/
./install-essentials
./tweak-ui
~~~
