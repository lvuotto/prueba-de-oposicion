Equivalencias `NAND`:
 - `NOT x   = x NAND 1`
 - `x AND y = NOT (x NAND y) = (x NAND y) NAND 1`
 - `x OR  y = (NOT x) NAND (NOT y) = (x NAND 1) NAND (y NAND 1)`
 - `x XOR y = (x OR y) AND ((NOT x) OR (NOT y)) = (((x NAND 1) NAND (y NAND
   1)) NAND (x NAND y)) NAND 1`
