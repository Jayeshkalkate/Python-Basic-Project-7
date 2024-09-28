# Python-Basic-Project-7
By using python programming language

"""
Find Maximum in a List :- Determine the maximum value in a list.
"""

blank_list = []

end = (int(input("Enter the number of students : ")))

for loop in range (end) :
    loop = (input("Enter your name : "))
    blank_list.append(loop)

print(f"This is a real list :-\n{blank_list}\n")

sorting = blank_list.sort()

print(f"This is the sorted methood :-\n{sorting}\n")

print(f"This is the sorted list in assending order :-\n{blank_list}\n")

large = blank_list[0]

print(f"The largest string in the list is :-\n{large}\n")

small = blank_list[-1]

print(f"The smallest string in the list is :-\n{small}\n")
