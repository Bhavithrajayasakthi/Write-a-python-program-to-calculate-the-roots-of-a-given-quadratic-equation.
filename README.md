# Write-a-python-program-to-calculate-the-roots-of-a-given-quadratic-equation.
import math
a=int(input("enter a"))
b=int(input("enter b"))
c=int(input ("enter c"))
d=(b*b)-(4*a*c)
if d>0:
    print("roots are :")
    x1=-b+math.sgrt(d)/(2*a)
    x2=-b-math.sqrt(d)/(2*a)
    print("x1= =",x1)
    print("x2= =",x2)
else:
    print("roots are imaginary")
 
Output 1:
enter a 10
enter b 5
enter c 6
roots are imaginary

