# Arithmetic-Calculator
title = "Finding the Nth term with the given 1st term and common difference"
print(title[:].upper())
print('') ##############
first_term = float(input('First term = '))
nth_term = int(input('Nth term = '))
common_diff = float(input('Common Difference = '))
a_sub_n = float(first_term) + int((nth_term - 1)) * common_diff
print(f'The {round(nth_term, )}th term is {round(a_sub_n, )}')
print('') ##############
print(f'How about the sum of all terms from {round(first_term, )} to {round(a_sub_n, )}? ')
Yes_No = str(input('Do you want to continue? (Yes or No) '))
part = first_term + a_sub_n
part_whole = part / 2
answer_allsum = nth_term * part_whole
no_message = 'Okay. Just try this feature next time.'
if Yes_No == str('Yes'):
    print(f'The sum of all terms from the 1st term ({round(first_term, )}) to the {nth_term}th term ({round(a_sub_n, )}) is {round(answer_allsum)}')
else:
    print(no_message)
