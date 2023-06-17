# TITTLE
# MINIMISE THE FUNCTION USING K MAP F(A,B,C)=A'B' +BC'+ BC + A'B'C' AND SIMULATE THE LOGIC DIAGRAM USING VERILOG

# THEORY
With the help of the K-map method, we can find the simplest POS and SOP expression, which is known as the minimum expression. A visual way to simplify logic expressions.It gives the most simplified form of the expression.The K-map is a systematic way of simplifying Boolean expressions. Simplification of logic expression using Boolean algebra is awkward because: it lacks specific rules to predict the most suitable next step in the simplification process it is difficult to determine whether the simplest form has been achieved. A Karnaugh map is a graphical method used to obtained the most simplified form of an expression in a standard form (Sum-of-Products or Product-of-Sums). The simplest form of an expression is the one that has the minimum number of terms with the least number of literals (variables) in each term. By simplifying an expression to the one that uses the minimum number of terms, we ensure that the function will be implemented with the minimum number of gates. By simplifying an expression to the one that uses the least number of literals for each terms, we ensure that the function will be implemented with gates that have the minimum number of inputs.

# LOGIC DIAGRAM
![image](https://github.com/yuvabharathib/Simulation-project--Digital-Electronics/assets/113497404/bf4b3a14-ddea-44d4-a8ae-e2bdcc8b9bab)


# NETLIST DIAGRAM
![image](https://github.com/yuvabharathib/Simulation-project--Digital-Electronics/assets/113497404/7ec19f06-8330-4ccb-94d4-97d988e0cdca)


# TIMING DIAGRAM
![image](https://github.com/yuvabharathib/Simulation-project--Digital-Electronics/assets/113497404/d43657b2-5744-4f88-8b16-f9fc5757c2cc)


# PROGRAM
```
DEVELOPED BY YUVABHARTHI.B REG NO. : 212222230181

module sp(d,a,b);
input a,b;
output d;
wire f;
not(f,a);
or (d,f,b);
endmodule
```
