# Questões de Conversão

## 1. Binário → Decimal

**Formula EX:** 1x2⁶ o resultado é 64 por que 2 x 2 x 2 x 2 x 2 x 2
```-
    2x2=4 > 4x2=8 > 8x2=16 > 16x2=32 > 32x2=64 | por fim (1x64) e (1x2⁶) resulta em 64 se for (0x64=0)
```

**Formula EX:** 7x8¹ o resultado é 56 por que 8 umas vez

**Formula EX:** 12x16² o resultado é 3072 por que 16 x 16 = 256 (12x256) = 3072



1. Converta 1010₂ para decimal.

   > 1010: (1x2³=8) + (0x2²=0) + (1x2¹=2) + (0x2⁰=0) = 10

2. Converta 111001₂ para decimal.

   > 111001: (1x2⁵=32) + (1x2⁴=16) + (1x2³=8) + (0x2²=0) + (0x2¹=0) + (1x2⁰=1) = 57

3. Converta 1001101₂ para decimal.
   > 1001101: (1x2⁶=64) + (0x2⁵=0) + (0x2⁴=0) + (1x2³=8) + (1x2²=4) + (0x2¹=0) + (1x2⁰=1) = 77

## 2. Decimal → Binário

**Formula EX:** dividendo − (divisor×quociente) = Resto | 9 − (2×4) = 1 se não

4.Converta 18₁₀ para binário.
18 ÷ 2 = 9 [18 - (2x9=18) = 0]
9 ÷ 2 = 4 [9 − (2×4=8) = 1]
4 ÷ 2 = 2 [4 - (2x2=4) = 0]
2 ÷ 2 = 1 [2 - (2x1=2) = 0]
1 ÷ 2 = 0 [1 - (0x2=0) = 1]
= 10010₂ Binário

5.Converta 63₁₀ para binário.
63 ÷ 2 = 31 [1]
31 ÷ 2 = 15 [1]
15 ÷ 2 = 7 [1]
7 ÷ 2 = 3 [1]
3 ÷ 2 = 1 [1]
1 ÷ 2 = 0 [1]
= 111111₂ Binário

6.Converta 127₁₀ para binário.
127÷ 2 = 63 [1]
63 ÷ 2 = 31 [1]
31 ÷ 2 = 15 [1]
15 ÷ 2 = 7 [1]
7 ÷ 2 = 3 [1]
3 ÷ 2 = 1 [1]
1 ÷ 2 = 0 [1]
= 1111111₂ Binário

## 3. Octal → Decimal

7.Converta 45₈ para decimal.
45: (4x8¹=32) + (5x8⁰=5) = 37

8.Converta 72₈ para decimal.
72: (7x8¹=56) + (2x8⁰=2) = 58

9.Converta 144₈ para decimal.
144: (1x8²=64) + (4x8¹=32) + (4x8⁰=4) = 100

## 4. Decimal → Octal

10.Converta 30₁₀ para octal.
30 ÷ 8 = 3.75 [0.75 x 8 = 6]
3 ÷ 8 = 0 [0.375 x 8 = 3]
= 36₈ Octal

11.Converta 95₁₀ para octal.
95 ÷ 8 = 11 [0.875 x 8 = 7]
11 ÷ 8 = 1 [0.375 x 8 = 3]
1 ÷ 8 = 0 [0.125 x 8 = 1]
= 137₈ Octal

12.Converta 200₁₀ para octal.
200 ÷ 8 = 25 [0]
25 ÷ 8 = 3 [0.125 x 8 = 1]
3 ÷ 8 = 0 [0.325 x 8 = 3]
= 310₈ Octal

| Hex | Decimal |
| --- | ------- |
| A   | 10      |
| B   | 11      |
| C   | 12      |
| D   | 13      |
| E   | 14      |
| F   | 15      |

## 5. Hexadecimal → Decimal

13.Converta 2A₁₆ para decimal.
2A₁₆: (2x16¹=32) + (10x16⁰=10) = 42₁₀

14.Converta C7₁₆ para decimal.
C7₁₆: (12x16¹=192) + (7x16⁰) = 199₁₀

15.Converta 1F4₁₆ para decimal.
1F4₁₆: (1x16²=256) + (15x16¹=240) + (4x16⁰=4) = 500₁₀

## 6. Decimal → Hexadecimal

> Usa A–F para os restos maiores que 9

16.Converta 50₁₀ para hexadecimal.
50 ÷ 16 = 3 [0.125 x 16 = 2]
3 ÷ 16 = 0 [0.1875 x 16 = 3]
= 32₁₆ Hexadecimal

17.Converta 175₁₀ para hexadecimal.
175 ÷ 16 = 10 [0.9375 x 16 = 15 → F]
10 ÷ 16 = 0 [0.625 x 16 = 10 → A]
= AF₁₆ Hexadecimal

18.Converta 512₁₀ para hexadecimal.
512 ÷ 16 = 32 [512 - (16x32=512) = 0]
32 ÷ 16 = 2 [32 - (16x2=32) = 0]
2 ÷ 16 = 0 [0.125 x 16 = 2]
= 200₁₆ Hexadecimal

O agrupamento deve ser feito da esquerda para a direita: 10101011₂ agrupado -> [1010] [1011]

## 7. Binário → Hexadecimal

19.Converta 11011010₂ para hexadecimal. > 1101: (1x2³=8) + (1x2²=4) + (0x2¹=0) + (1x2⁰=1) = 13 → D > 1010: (1x2³=8) + (0x2²=0) + (1x2¹=2) + (0x2⁰=0) = 10 → A
= DA₁₆ Hexadecimal

20.Converta 10101011₂ para hexadecimal. > 1010: (1x2³=8) + (0x2²=0) + (1x2¹=2) + (0x2⁰=0) = 10 → A > 1011: (1x2³=8) + (0x2²=0) + (1x2¹=2) + (1x2⁰=1) = 11 → B
= AB₁₆ Hexadecimal
