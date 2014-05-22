Web Development Essentials
==========================

My basic needs for a Unix environment.  I make Web sites.

Run the script to link your dotfiles and ~/bin directory.

~~~ sh
cd essentials/
./create-symlinks
~~~

Doing so creates a symlink called "this" in the repository root, pointing to the
appropriate directory for your operating system.  In this way, you can have
different implementations on different systems as needed.

Since the .gitconfig contains your name and email address, I copy and edit that
manually:

~~~ sh
cp -i dotfiles/gitconfig ~/.gitconfig
sensible-editor ~/.gitconfig
~~~

The directory "this/setup" contains additional setup scripts.
