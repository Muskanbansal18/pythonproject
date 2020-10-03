"# pythonprojectswap" 
#different methods to swap two numbers in python

print('first method')
a=int(input('enter 1st no.: '))
b=int(input('enter 2nd no.: '))
a,b=b,a
print('a=',a)
print('b=',b)

print('second method')
a=int(input('enter 1st no.: '))
b=int(input('enter 2nd no.: '))
b=a*b
a=b/a
b=b/a
print(a)
print(b)

print('third method')
a=int(input('enter 1st no.: '))
b=int(input('enter 2nd no.: '))
a=a+b
b=a-b
a=a-b
print(a)
print(b)

print('fourth method')
a=int(input('enter 1st no.: '))
b=int(input('enter 2nd no.: '))
temp=a
a=b
b=temp
print(a)
print(b)

print('fifth method')
a=int(input('enter 1st no.: '))
b=int(input('enter 2nd no.: '))
a=a^b
b=a^b
a=a^b
print(a)
print(b) 

print('sixth method')
n=(input('enter two numbers: ')).split()
print(n)
n.reverse()
a=int(n[0])
b=int(n[1])
print(a)
print(b)


print('seventh method')
List=[int(input("enter a")),int(input("enter b"))]
List.reverse()
print(List)
