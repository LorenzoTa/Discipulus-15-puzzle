NAME

Discipulus15puzzle.pl

SYNOPSIS

perl Discipulus15puzzle.pl [ --verbose --nocolor --charsize n --positions n n ..]

OPTIONS

     -v|verbose
                   print to the screen the appearence of the board
                   and the solvability/difficulty of the game based
                   on the calculated and shown parity of permutations
                   
     -n|nocolor
                  high contrast colors instead of default ones
                  default colors are imperial red and gold
                  
     -c|charsize  number
                  the size used for numbers on tiles
                  
     -tiles|positions  sequence of numbers from 1 to 16
                  providing a correct sequence of numbers from 1 (the tile with
                  the 1 on it) to 16 (the empty tile) you can force the game
                  to show a particular initial disposition
                  This is unavailable while --extreme is used
                  
     -x|extreme|perl
                  instead of numbers, perl statements are shown
                  the victory condition is shown briefly then the board is
                  shuffled: good luck monks

DESCRIPTION

This classic puzzle game is dedicated to my 15th anniversary of presence at the perlmonks community.

If run without arguments nor switches it displays a shuffled board with, in the above part, a description of the diffuculty and solvability of the current game.

Not every disposition can lead to a victorious game: this is due to permutations parity. Games with odd permutations are impossible.

You can shuffle the board using CTRL-S sequence.

To play just click on the tile you want to move.

Winners are rewarded with a surprise.

Have fun!

REFERENCES

See about 15 puzzle at OEIS https://oeis.org/A087725

mathworld http://mathworld.wolfram.com/15Puzzle.html

Info in italian http://utenti.quipo.it/base5/jsgioco15/g15did.htm

Reference and support site for this program, if needed, http://www.perlmonks.org

AUTHOR

Discipulus as found at www.perlmonks.org
