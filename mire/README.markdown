# Mire

It's a nonviolent MUD. (Multi-User Dungeon)

You can either launch via SLIME by evaling mire.el from within Emacs
(preferred since it gives you access to the REPL) or by the included
mire.sh shell script.

Dependencies (clojure, clojure-contrib) are included, though you will
need a JVM on your system.

To connect, simply telnet to port 3333, or hit M-x mire from within
Emacs if you have used mire.el.

## Note

This branch is part of a series that builds up the full program
step-by-step, but it's meant to be an incomplete project. See the
master branch for the final product.

Copyright (c) 2009 Phil Hagelberg
Licensed under the same terms as Clojure.
