# motion: Left-right

*Q_lr*		Left-right motions

```
  h		left (also: CTRL-H, <BS>, or <Left> key)
  l		right (also: <Space> or <Right> key)
  0		to first character in the line (also: <Home> key)
  ^		to first non-blank character in the line
  $		to the last character in the line (N-1 lines lower) (also: <End> key)
  g0		to first character in screen line (differs from "0" when lines wrap)
  g^		to first non-blank character in screen line (differs from "^" when lines wrap)
  g$		to last character in screen line (differs from "$" when lines wrap)
  gm		to middle of the screen line
  gM		to middle of the line
  |		to column N (default: 1)
  f{char}	to the Nth occurrence of {char} to the right
  F{char}	to the Nth occurrence of {char} to the left
  t{char}	till before the Nth occurrence of {char} to the right
  T{char}	till before the Nth occurrence of {char} to the left
  ;		repeat the last "f", "F", "t", or "T" N times
  ,		repeat the last "f", "F", "t", or "T" N times in opposite direction

```
