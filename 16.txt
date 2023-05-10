16. Write a program that computes the net amount of a bank account based a 
transaction log from console input. The transaction log format is shown as 
following:
D 100
W 200
D means deposit while W means withdrawal.
Suppose the following input is supplied to the program:
D 300
D 300
W 200
D 100

lines = []
while True:
	loopInput = input()
	if loopInput == "done":
		break
	else:
		lines.append(loopInput)

lst = list(int(i[2:]) if i[0] == 'D' else -int(i[2:]) for i in lines)
print(sum(lst))
