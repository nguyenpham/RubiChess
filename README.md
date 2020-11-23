# RubiChess
Just another UCI compliant chess engine. Have a look at the ChangeLog for a detailed feature list.

I don't want to compete with highend engines but to practise programming C++ and to see it improving compared
to earlier releases. I try to avoid simple copy and paste code from other engines, everything needs to "pass
my brain" before it gets implemented...
Well, now two years later and while competing at Grahams tournaments I got a little ambitious to compete with some of the best engines :-)

Many thanks to the excellent documentation at https://chessprogramming.org.
Also many thanks to Bluefever and his video tutorial https://www.youtube.com/user/BlueFeverSoft/videos
A special thank you goes to open source engine Olithink. I had a look at its source code or even two.
And while improving RubiChess more and more I looked at several open source engines like
Ethereal, Stockfish, Pirarucu, Laser, ...
Thank you for the great list of engines at http://www.computerchess.org.uk/ccrl/4040/
Not mentioned all the other documentation and tools freely available.

For using NNUE evaluation you have to
- enable 'Use NNUE' option
- set 'NNUENetpath' option to a valid network weight file

You can download network files from my repository https://github.com/Matthies/NN and put it in the same folder as the executable.
Default net is nn-803c91ad5c-20201107.nnue which will be included in release packages.
