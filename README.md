## TITTLE

Design and simulate 5 bit parity generator using Verilog.

## THEORY

![image](https://github.com/shalini-venkatesan/Simulation-project--Digital-Electronics/assets/118720291/f5b38213-92af-4b90-9a00-0936bca31744)

## LOGIC DIAGRAM

![image](https://github.com/shalini-venkatesan/Simulation-project--Digital-Electronics/assets/118720291/7933ce09-fa45-4e8a-92de-ada761ce822b)

## NETLIST DIAGRAM

![image](https://github.com/shalini-venkatesan/Simulation-project--Digital-Electronics/assets/118720291/cada9b4f-62f5-4ea8-a9df-611ecc4ca566)

## TIMING DIAGRAM

![image](https://github.com/shalini-venkatesan/Simulation-project--Digital-Electronics/assets/118720291/4777855c-ee57-4bee-b86d-ca8e93e4b801)

## PROGRAM
```
module ll(A0,A1,A2,A3,A4,even,odd);
input A0,A1,A2,A3,A4;
output even,odd;
wire a,b,c;
xor(a,A0,A1);
xor(b,A2,a);
xor(c,A3,b);
xor(even,A4,c);
not(odd,even);
endmodule
```

## RESULT:
Thus the given equation is minimised using k map and simulated the logic diagram
using verilog.
