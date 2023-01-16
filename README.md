# Nand2tetris
This is a course about

# What I learn

# Project 1 

## Nand gate (provided)
![Nand gate image](images_for_readme/nand.png)

## Not gate
![Not gate image](images_for_readme/not.png%0D) 

```hdl
Nand(a=in, b=in, out=out);
```
## And gate 
![And gate image](images_for_readme/and.png)
```hdl
Nand(a=a, b=b, out=c);
Not(in=c, out=out);
```
## Or gate 
![Alt text](images_for_readme/Or.png)
## Xor gate 
![Alt text](images_for_readme/xor.png)
## Mux gate  
![Alt text](images_for_readme/Mux.png)
Inputs: `a`, `b`, `sel`  
Outputs: `out`  
Function: If `sel=0` then `out=a` else `out=b`. 

## DMux gate 
![Alt text](images_for_readme/DMux.png)
Inputs: `in`, `sel`
Outputs: `a`, `b`
Function: If `sel=0` then `a=in, b=0` else `a=0, b=in`.

## Not16 gate 
## And16 gate 
## Or16 gate 
## Mux16 gate 
## Or8Way gate 
## Mux4Way16 gate 
## Mux8Way16 gate 
## DMux4Way gate 
## DMux8Way gate 
## And gate 