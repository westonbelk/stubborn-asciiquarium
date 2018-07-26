Fork of Asciiquarium that's a bit more stubborn. Captures signals that would commonly be used to exit the asciiquarium.

Why? It's a fun prank for red vs blue team simulations.




Original Readme
---------------


                              Asciiquarium v1.1
                    by Kirk Baucom <kbaucom@schizoid.com>
                          http://www.robobunny.com

Asciiquarium is an aquarium/sea animation in ASCII art.

Installation
------------

Asciiquarium is a single perl script, so all you have to do is make sure
it's executable and put it somewhere convenient, like /usr/local/bin or
/usr/local/games.

  Ubuntu
  ------

  Out-of-the-box ubuntu doesn't satisfy the Requirements below, so
  here's how to get them:
  1) Get perl's curses package which is available from apt:
       sudo apt-get install libcurses-perl
  2) Run
       cpan
     at the shell.  Agree to the defaults for everything.
     To leave cpan, type 
       quit
  3) Type
    sudo cpan Term::Animation

Requirements
------------

You must have the Term::Animation module, which you can get from
http://www.cpan.org. The Term::Animation module also requires the Curses
module, which you can also get from CPAN. This program will only run on
platforms that have a Curses library (so it won't work on Windows, but
you might get it to run under cygwin).

Usage
-----

Command line arguments:
	-c	"classic" mode, only show species from Asciiquarium 1.0

While running:
	q	quit
	r	redraw (will recreate all entities)
	p	toggle pause

Contributors
------------

New fish species backported from the Android live wallpaper and
other minor improvements by Claudio Matsuoka.

Pretty much all of the ASCII art was done by Joan Stark:
http://www.geocities.com/SoHo/7373/

Anything that she didn't do, I don't have a source for.
