# EXPT 1b: Computation-of-DFT-using-FFT-ALGORITHM

## AIM
To perform and verify DFT using FFT-ALGORITHM by SCILAB.
## APPARATUS REQUIRED
PC installed with SCILAB
## PROGRAM 
```
clc;
clear;
x = [1 1 1 1];
h = [1 2 3 4];
m = length(x); n = length(h); a=0:1:m-1;
b=0:1:n-1;
subplot(3,1,1);
plot2d3(a,x);
xlabel('Time'); ylabel('Amplitude');
title('Graphical Representation of Input Signal X'); subplot(3,1,2);
plot2d3(b,h);
xlabel('Time'); ylabel('Amplitude');
title('Graphical Representation of Impulse Signal h'); for i = 1: n+m-1
conv_sum = 0;
for j = 1:i
if (((i-j+1) <= n)&(j <=m))
conv_sum = conv_sum + x(j)*h(i-j+1);
2
end;
y(i) = conv_sum;
end; end;
disp(y,'Convolution Sum using Direct Formula Method = ') subplot(3,1,3);
plot2d3(y)
title('Graphical Representation of output Signal y');
```
### DFT FFT-ALGORITHM
<br>
<br>
<br>
<br>
<br>

<br>
### CALCULATIONS:
<br>
<br>
<br>
<br>
<br>
### SAMPLE OUTPUT:
<br>
<br>
<br>
<br>



## RESULT:
Thus,  DFT using FFT-ALGORITHM for two given sequences were performed and its result was verified.

