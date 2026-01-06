a=int(input("enter 1st number:"))
b=int(input("enter 2nd number:"))
c=input("enter the operation +,-,/,*,:")
print("the result is:",end='')
if c=='+':
print(a+b)
elif c=='-':
print(a-b)
elif c=='/':
print(a/b)
elif c=='*':
print(a*b)
else:
print("error:wrong operator entered")

Output:
enter 1st number:6
enter 2nd number:8
enter the operation +,-,/,*,:*
the result is:48
