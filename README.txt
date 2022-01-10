  _     ____  _   _ 
 | |   / ___|| | | |
 | |   \___ \| |_| |
 | |___ ___) |  _  |
 |_____|____/|_| |_|
                    
A fork of Lambda shell from minexew's TempleOS distro, Shrine.

TempleOS Wikipedia ... https://en.wikipedia.org/wiki/TempleOS
TempleOS website ..... https://templeos.org/
Shrine repository .... https://github.com/minexew/Shrine
Lsh repository ....... https://github.com/minexew/Lsh

---------------------------------------

EDIT: Lsh has its own repo now and this has been merged, see
      below. It's also been merged into Shrine proper, but
      since a new release hasn't happened in a while it's still
      just on the dev branch.

      >> https://github.com/minexew/Lsh <<


Lsh is a shell for Shrine and TempleOS that aims to make using the
command line simpler. It provides three major features:

- Tab completion.
- Command syntax simplification/
- Command history.

Traditionally, the command history system has been quite limited.
The fork adds advanced command history functionality, specifically:

- Command history on up/down through a speedy ring buffer system.
- Saving to and loading from file.
- `fish`-like partial command history completion.

It is due to be merged into to Shrine proper once thouroughly bug-
tested and battle-hardened.
