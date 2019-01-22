# ProbStat1

L = [25,33,35,48,55,38,56,55,64,38]

from random import randint


a = randint(0,9)
num1 = L[a]
L2 = L.remove(num1)

b = randint(0,8)
num2 = L2[b]
L3 = L2.remove(num2)

c = randint(0,7)
num3 = L3[c]

print(num1,num2,num3)