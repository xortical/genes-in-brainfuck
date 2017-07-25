# genes-in-brainfuck
Encoding base pair sequence as numbers in a cell for brainfuck

Instead of writing genes as sequence of A,C,G,T, writing it as numbers in a cell might make life easier. Brainfuck seems to have a cool protocol to do so.
I have assigned 
"A" --> 1 or {'+'}
"C" --> 2 or {'++'}
"G" --> 3 or {'+++'}
"T" --> 4 or {++++}

The sequence : "GGCAAGGTCTTC"

becomes

+++>+++>++>+>+>+++>+++>++++>++>++++>++++>++>
