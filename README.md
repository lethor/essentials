# Web Development Essentials

My basic needs for a Unix environment.  I make Web sites.

## Setup

Run the setup script to prepare a new computer for development.

~~~ sh
git clone <repo url>
cd essentials/
./setup
~~~

The script will run create-symlinks to link your dotfiles and ~/bin directory.
Doing so creates a symlink called "this" in the repository root, pointing to
the appropriate directory for your operating system.  This way you can have
different implementations on different systems.

If you don't already have a ~/.gitconfig, the setup script will copy the example
(this/dotfiles/gitconfig) and open a text editor.  Scroll to the bottom, and
tell git your name and email address.

Voila!  My idea of a basic Web development environment.

## License

Released as open source software under the terms of the [ISC License](https://en.wikipedia.org/wiki/ISC_license).
