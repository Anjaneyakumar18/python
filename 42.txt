Write a program which accepts a string as input to print "Yes" if the string is "yes" or "YES" or "Yes", otherwise print "No".

input = input('Enter string:')
output = ''.join(['Yes' if input == 'yes' or input =='YES' or input =='Yes' else 'No' ])
print(str(output))
