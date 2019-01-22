# ProbStat1

L = [25,33,35,48,55,38,56,55,64,38]

from random import randint


a = randint(0,9)
print(a)
num1 = L[a]
print(num1)
L2 = L
L2.remove(num1)
print(L2)

b = randint(0,8)
num2 = L2[b]
L3 = L2 
L3.remove(num2)

c = randint(0,7)
num3 = L3[c]

print(num1,num2,num3)