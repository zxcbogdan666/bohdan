ЛАБОРАТОРНЕ ЗАНЯТТЯ No 6

«Алгоритми обробки символьних рядків та рядкових величин».

Завдання 1: 
КОД: 

`full_name = "Oleg Shevchenko"
first_letter = full_name[0]
space_index = full_name.find(" ")
second_letter = full_name[space_index + 1]
initials = first_letter + second_letter
print("initsials = ", initials)`

screenshot [https://ibb.co/v4kHCV21](url)

Завдання 2:
КОД: 

text = input("write something: ")
for char in text:
    print("symbol:", char, "-> ASCII.:", ord(char))


screenshot [https://ibb.co/DSjk86b](url)
