# Sandstorm lang

A musical [brainfuck](https://esolangs.org/wiki/Brainfuck) derivative.

## Language overview

| Sandstorm | Brainfuck | Description |
|:---------:|:---------:|:------------|
| `BBBB` | `>` | Move the pointer to the right |
| `EEEE` | `<` | Move the pointer to the left |
| `B=EE` | `+` | Increment the memory cell at the pointer |
| `E=DD` | `-` | Decrement the memory cell at the pointer |
| `DDDD` | `.` | Output the character signified by the cell at the pointer |
| `    ` | `,` | Input a character and store it in the cell at the pointer |
| `BBB=` | `[` | Jump past the matching `]` if the cell at the pointer is 0 |
| `D=AA` | `]` | Jump back to the matching `[` if the cell at the pointer is nonzero |
