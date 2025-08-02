Write  a  program  to  determine  sum , difference , product , quotient , largest  and  smallest  of  two  numbers.



Also  find  remainder,  sqrt  of  first  input , power, gcd  and  factorial  of  first  input







Hint:  Use  F  string  to  print  results



\########answere###########

import math

try:

a=float(input('Enter the 1st integer value:'))

b=float(input('Enter the 2nd integer value:'))



print(f'{a} and {b} = {a + b}')

print(f'{a} and {b} = {a - b}')

print(f'{a} and {b} = {a \* b}')

print(f'{a} and {b} = {a / b}')

print(f'{a} and {b} = {a % b}')

print(f'Max of {a} and {b} = {max(a,b)}')

print(f'Min of {a} and {b} = {min(a,b)}')

print(f'square root of a = {math.sqrt(a)}')

print(f'Power of {a} and {b} = {math.power(a,b)}')

print(f'GCD of {a} and {b} = {math.gcd(a,b)}')

print(f'Factorial of {a} = {math.factorial(a)}')



except value error :

print('Invalid Input enter the coorect  integer number:')





\#################################################





Write  a  program  to  swap  values  of  any  two  objects  in  a  single  statement  without  using  3rd  object

Let  'x'  be  25  and  'y'  be   'Hyd'

What  are  'x'  and  'y'  after  swap ?  ---> Hyd  and  25

Hint:  Swap  references  but  not  objects



x = eval(input('Enter the 1st Swap value:'))

y = eval(input('Enter the 2nd Swap value:'))



print(f"Before swap: x is '{x}' and y is '{y}' ")



x,y=y,x



print(f"After Swap:x is '{x}' and y is '{y}' ")





\########### question ##########



Write  a  program  to  determine  largest  of  three  inputs  without  using  max()  function

1\\) What  is  the  output  if  inputs  are  10 , 20  and  15 ?   --->  20

2\\) What  is  the  output  if  inputs  are  35.8 , 42.8  and  27.9 ?   --->  42.8

3\\) What  is  the  output  if  inputs  are  'RAMA'  , 'RAKESH'  and  'RAJESH' ?   --->  'RAMA'

4\\) What  is   the  output  if  inputs  are  \\\[10 , 20 , 15 , 18]  , \\\[10 , 20 , 32, 19]  and  \\\[10 , 20 , 25, 17] ?  ---> \\\[10 , 20 , 32 , 19]

5\\) Inputs  can  be  integers , floats , strings  and  so  on

6\\) Use  nested  ternary  operator



\####### Answere #####



num1 = float(input('Enter 1st integer number:'))

num2 = float(input('Enter 2nd integer number:'))

num3 = float(input('Enter 3rd integer number:'))



largest\_number = num1 if (num1 > num2 and num1 > num3 ) else (num2  if num2 > num3 else num3)



print(' largest number:"{largest\_number}"')







\####### Question #############



Write  a  program  to  print   '>'  if  1st  input  >  2nd  input,



                                               '<'  if  1st  input  <  2nd  input  and



                                               '='  if  inputs  are  same

1\\) What  is  the  result  if  inputs  are  10  and  20 ?  ---> <

2\\) What  is  the  result  if  inputs  are  70  and  60 ?  --->  >

3\\) What  is  the  result  if  inputs  are  25  and  25 ?  ---> =

4\\) Inputs  can  be  integers , floats , strings  and  so  on

5\\) Use  ternary  operator



**########## ANSWERE ###########**



**X = float(input('enter the 1st input:'))**

**y = float(input('enter the 2nd input:'))**



**result = '>' if x > y else ('<' if x < y else '=')**



**print(f'result is: "{result}"')**


\##### Question ##########################



Write  a  program  to  print  1  if  input  is  +ve  ,  -1    if  input  is  -ve  and  0  if  input  is  0

1\\) What  is  the  result  if  input  is  -25 ?  --->  -1

2\\) What  is  the  result  if  input  is  75 ?  --->  1

3\\) What  is  the  result  if  input  is  0 ?  --->  0

4\\) Use  nested  ternary  operator



\######## Answere #############

**input1 = int(input('Enter value of integer:'))**



**result = "1" if (result = "+ve" else** 



































































