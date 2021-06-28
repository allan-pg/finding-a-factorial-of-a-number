# finding-a-factorial-of-a-number
A simple program in python to output factorial
n = int(input('Enter a number to find factorial: '))
factorial = 1
if (n < 0):
	print('sorry negative factorial is beyond me')
elif (n == 0):
	print('the factorial for zero is one')
else:
	for i in range(1, n+1):
		factorial = factorial * i
	print('The factorial is', factorial)
