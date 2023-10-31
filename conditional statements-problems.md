1)  Write a Python program that asks the user for their age and prints "You are an adult" if the age is 18 or older, otherwise prints "You are a minor'


```python
age= int(input('enter your age:'))

if age>=18:                  # checks if the age is greater than is equal to 18
    print('you are an adult') # prints the statement if the age is above 18
else:
        print('you are a minor') # prints the statement if the age is less than 18

    
```

    enter your age:17
    you are a minor
    

2)  Write a program that takes a numerical grade (out of 100) as input and prints the corresponding letter grade according to the following scale:
 90-100:A
 80-89: B
 70-79: C
 60-69: D
 Below 60: F



```python
num= int(input('enter the grade'))

if num >=90:  # checks if the num is greater than equal to 90
    print('a') # prints the statement if the num is above 90
elif num >=80:
    print('b')
elif  num >=70:
    print('c')
elif num >=60:
    print('d')
else:
    print('f')
```

    enter the grade55
    f
    

3)  Write a program that calculates the Body Mass Index (BMI) of a person. The user should input their weight in kilograms and height in meters. The program should then print whether the person is underweight, normal weight, overweight, or obese



```python
weight = float(input('enter the weight in kilograms:'))
height = float(input('enter the height in meters:'))
bmi = weight/height**2
print (bmi)
if bmi < 18.5:
    print('underweight')
elif 18.5 < bmi <24.5:
    print('normalweight')
elif 24.5 < bmi <29.5:
    print('overweight')
else:
    print('obese')

```

    enter the weight in kilograms:70
    enter the height in meters:1.73
    23.38868655818771
    normalweight
    

4)  Write a program that asks the user for three numbers and prints the maximum of the three


```python
x= float(input('enter the first number:'))
y= float(input('enter the second number:'))
z= float(input('enter the third number:'))
max = max(x,y,z)

if x>y and x>z:
    print('x is maximum')
elif y>x and y>z:
    print('y is maximum')
else:
    print('z is maximum')

```

    enter the first number:10
    enter the second number:20
    enter the third number:30
    z is maximum
    

5)  Write a program that asks the user for a temperature (in Celsius) and prints "It's freezing" if the temperature is below 0, "It's cool" if it's between 0 and 10, "It's warm" if it's between 10 and 20, and "It's hot" if it's above 20



```python
temp = float(input('enter the temperature:' ))

if temp<0:
    print('it\'s freezing') 
elif temp in range(0,10):
     print('it\'s cool') 
elif temp in range(10,20):
     print('it\'s warm')
else:
     print('it\'s hot')              
                   
```

    enter the temperature:35
    it's hot
    

6)  Write a program that asks the user for a number (1-7) and prints the corresponding day of the week.


```python
day = int(input('enter a number:'))

if day==1:
    print('sunday')
elif day==2:
    print('monday')
elif day==3:
    print('tuesday')
elif day==4:
    print('wednesday')
elif day==5:
    print('thursday')
elif day==6:
    print('friday')
elif day==7:
    print('saturday')
else:
    print('invalid number')
```

    enter a number:5
    thursday
    

7)  Write a program that asks the user for a number and prints "In range" if the number is between 10 and 20 (inclusive), and "Out of range" otherwise.


```python
num= int(input('enter the number:'))

if num in range(10,20):
    print('In range')
else:
    print('out of range')
```

    enter the number:15
    In range
    

8)  Write a program that asks the user for an integer and prints whether it's even or odd.


```python
a = int(input('enter the integer:'))

if a%2==0:
    print('it is even')
else:
     print('it is odd')
```

    enter the integer:2
    it is even
    

9)   Write a Python program to add 'ing' at the end of a given string (string length should be equal to or more than 3). If the given string already ends with 'ing' then add 'ly' instead.If the string length of the given string is less than 3, leave it unchanged



```python
str = input('enter the string:')

if len(str)<=3 :
    print('str')
elif str.endswith('ing'):
    print(str.replace('ing' ,'ly'))
else:
     print((str), 'ing')
```

    enter the string:welcome
    welcome ing
    


```python

```


```python

```


```python

```


```python

```


```python

```
