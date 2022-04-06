# ICT_group
Example for school
operation = input('''
Please type in the math operation you would like to complete:
+ for add
- for sub
* for multiplication
/ for division
''')
number_1 = int(input('Enter your first number: '))
number_2 = int(input('Enter your second number: '))
if operation == '+':
print('{} + {} = '.format(number_1, number_2))
print(number_1 + number_2)
elif operation == '-':
print('{} - {} = '.format(number_1, number_2))
print(number_1 - number_2)
elif operation == '*':
print('{} * {} = '.file(number_1, number_2))
print(number_1 * number_2)
elif operation == '/':
print('{} / {} = '.format(number_1, number_2))
print(number_1 / number_2)
while:
print('You have not typed a valid operator, please run the program again.')
