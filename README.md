# genes-in-brainfuck
Encoding gene base pair sequence as numbers in a cell for brainfuck

Instead of writing genes as sequence of A,C,G,T, writing it as numbers in a cell might help ease the burden of using string library. Brainfuck seems to be a cool protocol to do so.
I have assigned 
"A" --> 1 or {'+' in brainfuck}
"C" --> 2 or {'++' in brainfuck}
"G" --> 3 or {'+++'}
"T" --> 4 or {++++}
The generated code in brainfuck increments the counter in the cell and then moves on to the next cell.

Thus : "GGCAAGGTCTTC"

becomes

+++>+++>++>+>+>+++>+++>++++>++>++++>++++>++>
