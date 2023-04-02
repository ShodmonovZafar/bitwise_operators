# Bitwise Operators
## Bitwise NOT
## Bitwise XOR (Exclusive OR)
Python dasturlash tilida `^` operatori **Bitwise XOR**-ni bajaradi. Bunga quyida misollar keltirilgan:
```
# 0 ^ 0 = 0
# 0 ^ 1 = 1
# 1 ^ 0 = 1
# 1 ^ 1 = 0
# Eslatma: Ikkalasi bir xil bo'lsa 0, aks holda 1
# 60 = 0b111100
# 30 = 0b011110
60 ^ 30
# Out: 34
# 34 = 0b100010
bin(60 ^ 30)
# Out: 0b1000010
int(bin(34), 2)
# Out: 34
```
Eslatma:
```
a XOR b = c
a XOR c = b
b XOR c = a
```
## Bitwise AND
## Bitwise OR
## Bitwise LeftShift
## Bitwise Right Shift
## Inplace Operations