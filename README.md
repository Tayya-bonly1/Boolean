# Boolean
Beginner things about boolean a low level language
🔁 Booleans in Action

Booleans are usually used with comparisons and conditions.

➤ 1. Comparison Operators
Operator	Meaning	Example	Result
==	Equal to	5 == 5	True
!=	Not equal to	5 != 3	True
>	Greater than	10 > 5	True
<	Less than	2 < 3	True
>=	Greater or equal	7 >= 7	True
<=	Less or equal	4 <= 2	False
a = 10
b = 5

print(a > b)  # True
print(a == b) # False

➤ 2. Using Booleans with if Statements
is_sunny = True

if is_sunny:
    print("Go outside!")
else:
    print("Stay inside.")

➤ 3. Logical Operators

You can combine Booleans with logic:

Operator	Description	Example
and	True if both are True	True and False → False
or	True if at least one is True	True or False → True
not	Flips the value	not True → False
is_tired = True
is_working = False

if is_tired and not is_working:
    print("Take a nap!")

🧠 Quick Quiz (Try it!):

What will this print?

age = 20
print(age >= 18)


✅ Answer: True (because 20 is greater than or equal to 18)

📌 Summary

Boolean = True or False

Used in comparisons and decisions

Helps control the flow of your program
