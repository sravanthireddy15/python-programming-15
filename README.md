//  a python function to find the max of three numbers
def max(a,b,c):
if (a>b) and (a>c):
largest=a
elif (b>c) and (b>a):
largest=b
else:
largest=c
print(" the max of given three numbers is {}".format(largest))
max(15,28,43)
