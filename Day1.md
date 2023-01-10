# Day 1 Introduction

# Convert Decimal to Binary

Decimal to Binary: Repeatedly subtract largest power of 2 you can and keep a positive result.
The powers you can subtract give the 1s in the binary result.

--

ex 1:
decimal number: 38

38 - 32 = 6
6 - 4 = 2
2 - 2 = 0

binary number: 0010 0110 

ex 2:
decimal number: 138

138 - 128 = 10
10 - 8 = 2
2 - 2 = 0

binary number: 0100 1010

--

Decimal to Binary: Division Method.
  Divide by 2 and take the remainder (gives binary digits right to left)
  
Decimal: 138

138 / 2 = 69 (remainder of 1)
69 / 2 = 34 (remainder of 1)
34 / 2 = 17 (remainder of 0)
17 / 2 = 8 (remainder of 1)
8 / 2  = 4 (remainder of 0)
4 / 2 = 2 (remainder of 0)
2 / 2 = 1 (remainder of 0)
1 / 2 = 0 (remainder of 1)

Binary: 1000 1011

--

# Convert Binary to Decimal

Add up the powers of 2 based on place value

100101 = 1*32 + 0*16 + 0*8 + 1*4 + 0*2 + 1*1 = 37

10111 = 1*16 + 0*8 + 1*4 + 1*2 + 1*1 = 23

# Convert from Binary to Hexadecimal

Group digits of 4 (from right to left). Conert each group of 4 bits to a single hex digit

Ex: 10001011101 -> 0100 0101 1101 -> 4 5 D -> 45D

Ex: 1101 0001 1001 -> D 1 9 -> D19

# Hexadecimal to Binary

Expand each hex digit to 4 binary digits

2E3B = 0010 1110 0011 1011

# Hexadecimal to Decimal

2C = 2*16^1 + 12*16^0 = 44

# Decimal to Hexadecimal

Same dividing process as binary, but remainders go up to 15.

Binary number: 93

93 / 16 = 5, remainder 13

5 / 16 = 0, remainder 5

Hexadecimal = 5D






