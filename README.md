# Level 1

Check accuracy of move generation for single piece on the board.

## Examples

Rook on d4 can moved to squares: a4, b4, c4, e4, f4, g4, h4, d8, d7, d6, d5, d3, d2, d1

```
    a b c d e f g h
  + - - - - - - - - +
8 | . . . * . . . . | 8
7 | . . . * . . . . | 7
6 | . . . * . . . . | 6
5 | . . . * . . . . | 5
4 | * * * r * * * * | 4
3 | . . . * . . . . | 3
2 | . . . * . . . . | 2
1 | . . . * . . . . | 1
  + - - - - - - - - +
    a b c d e f g h
```

# Level 2

Sliding pieces can not jump over other pieces.

# Level 3

Captures

# Level 3+n

Checks, Mates, En passant, castles, promotions