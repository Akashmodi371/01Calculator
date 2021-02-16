# 01Calculator
Beginning with python its my first simple calculator project .
#Here you can get Whole calculator code properly..

class Calculator:
    def __init__(self,num):
        self.num=num

    def __str__(self):
        print(f"The your result are :-")

    def __add__(self,num2):
        return self.num + num2.num
    
    def __mul__(self,num2):
        return self.num * num2.num
    
    def __sub__(self,num2):
        return self.num-num2.num

    def __truediv__(self,num3):
        return self.num/num3.num
value1=int(input("Enter your value1"))
value2=int(input("Enter your value2"))



v1=Calculator(value1)
v2=Calculator(value2)
sum=v1+v2
sub=v1-v2
mul=v1*v2
div=v1/v2
print( "Addition of your two number are :-", sum)
print("Substraction of your two number are :-", sub)
print("Multiplication of your two number are :-", mul)
print("Division of your two number are :-", div)
