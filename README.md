# PALP Week 4

## Assembly 8085

1. What is value of A in the following program?

```
LXI B, 203Bh
MVI A, 20h
ADD C
halt
```

2. Draw a table describe value of following diagram

```
LXI H, 1010h
MVI E, 20h
MOV D, E
ADD D
ADD E
MOV M, A
MVI L, 11h
ADD E
MOV M, A
LDA 1010h
LXI H, 1010h
halt
```

3. Draw a table describe value of following diagram

```
LXI B, 1111h
LXI D, 2020h
PUSH B
PUSH D
POP B
POP D
halt
```

4. What is the type of following instruction? _(eg. Immediate addressing, Direct addressing... )_

  - `ADD C`
  - `MVI C, 30h`
  - `LXI B, 3030h`
  - `MOV M, C`

 *** What is the `M` in `MOV M,C` means?

 5. What is register A call?

 6. The list of register in 8085 is `A, B, C, D, E, H, L`, why is `H` and `L` following by `E`?