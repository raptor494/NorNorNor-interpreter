# ((?)?)? Interpreter
This is an interpreter for (((?)?)?)[https://esolangs.org/wiki/((%3F)%3F)%3F], an Estoeric Programming Language.

# Usage
Once you've compiled the program, run it with `qqq <filename>` where `filename` is an ASCII file containing the program.

# Info
More info can be found at (https://esolangs.org/wiki/((%3F)%3F)%3F)[https://esolangs.org/wiki/((%3F)%3F)%3F].

# Implementation Notes
The `=` (out num) instruction reads 8 bits from the stack and interprets them as an unsigned byte. The first bit read is the most significant bit.
The `$` (input num) instruction reads a number from stdin and casts it as an unsigned byte, pushing the 8 bits to the stack. The first bit pushed is the least significant bit.