#**제어공학1 6주차 과제 (Chapter 3)**  
2019732035 이의주
***
P3.1  
(a)  
$$x_1(t)=y(t)$$  
$$x_2(t)=\frac{dy(t)}{dt}$$  
(b)  
$$M\frac{d^2y(t)}{dt^2}+b\frac{dy(t)}{dt}+ky(t)=F(t)$$  
$$M\frac{dx_2(t)}{dt}+bx_2(t)+kx_1(t)=F(t)$$  
(c)  
$$\frac{dx_1(t)}{dt}=x_2(t)$$  
$$\frac{dx_2(t)}{dt}=-\frac{b}{M}x_2(t)-\frac{k}{M}x_1(t)+\frac{1}{M}F(t)$$
$$y(t)=x_1(t)$$  
***  
P3.3  
$$L\frac{d i_L}{dt}-V_C+V_2-V_1=0$$  
$$C\frac{dV_C}{dt}=-i_L+i_R$$  
$$i_R R-V_2+V_C=0$$  
$$i_R=-\frac{V_C}{R}+\frac{V_2}{R}$$  
$$\frac{dV_C}{dt}=-\frac{V_C}{RC}-\frac{i_L}{C}+\frac{V_2}{RC}$$  
$$\frac{di_L}{dt}=\frac{V_C}{dt}+\frac{V_1}{L}-\frac{V_2}{L}$$  

$$
 \begin{pmatrix}
  \dot{x_1} \\
  \dot{x_2}
 \end{pmatrix}=
 \begin{bmatrix}
  0 & 1/L \\
  -1/C & -1/RC
 \end{bmatrix}
  \begin{pmatrix}
  x_1 \\
  x_2
 \end{pmatrix}+
  \begin{bmatrix}
  1/L & -1/L \\
  0 & 1/RC
 \end{bmatrix}
  \begin{bmatrix}
  V_1 \\
  V_2
 \end{bmatrix}$$  
 ***  
 
 
 

