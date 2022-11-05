# Mygitrepo
ARMSTRONG NUMBER
import math
n = int(input('Enter the number: '))
temp = n
arm = 0
l = len(str(n))
while temp!= 0:
    a = (temp%10)
    arm = arm + pow(a, l)
    temp = (temp//10)
if arm == n:
    print('It is an armstrong number')
else:
    print('It is not an armstrong number')



PRIME NUMBER
n = int(input('Enter the number : '))
count = 0
i = 0
for i in range(2,n//2):
    if n % i == 0:
        count += 1
if count == 1:
    print('It is not a prime number')
else:
    print('It is a prime number')


FACTORIAL OF THE NUMBER
n = int(input('Enter the number: '))
fact = 1
for i in range(1,n+1):
    fact = fact*i
    i += 1
print('Factorial of a number is ',fact)


