# scofield Learn, create and share// QUQDRATIC EQUATION IN PYTHON
import math

print("Evaluating the Quadratic Polinomials")
print("enter the value of variable a")
a=int(input())
print("a=", a)
print("enter the value of variable b")
b=int(input())
print("b=", b)
print("enter value of variable c")
c=int(input())
print("c=", c)
print("Calculating the Delta Value")
delta=(pow(b,2)-4*a*c)
if delta<0:
    print("Two imaginary solutions")
elif delta==0:
    x1=x2=-(b/a)
    print("one real solution x1=x2=", x1)
else:
    print("Delta=", delta)
    print("Evaluating the two root values x1 and x2")
    x1=-b+((pow(b,2)-(4*a*c))**0.5)/2*a
    print("The value of x1 = ", x1)
    x2=-b-((pow(b,2)-(4*a*c))**0.5)/2*a
    print("The value of x2 = ", x2)
print("It is done")
