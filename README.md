# 8thJune_B1_M

# Question 2

print(5**9)
print(3//2)
print(7//3)
print(7/3)
print(6 == 6)

a = 20
a += 30
a %= 3
print(a)

print(True * False)
print(True & False)
print(True and False)
print('False' in False)  #error
print(((6 > 3) and (7 < 4) or (18 == 3)) and (9 > 3))
print(True is False)
print(((True == False) or (False > True)) and (False <= True))


# Question 3

s1 = 'Nice to have it'
s2 = 'here'
print(s1 + " " + s2)

# Question 4

a = [1, 2, [3, 4], [5, [100, 200, ['hello']], 23, 11], 1, 7]
print(a[3][1][2])

# Question 5

a.append(s2)
a.insert(0, s1)
print(a)

# Question 6

color_list_1 = set(["White", "Black", "Red"])
color_list_2 = set(["Red", "Green"])
print(color_list_1.difference(color_list_2))

# Question 7

n = set((input("Enter a string : ")).replace(" ", ""))
s = set("abcdefghijklmnopqrstuvwxyz")
if n == s:
    print("string is a pangram.")
else:
    print("string is not a pangram.")

# Question 8

z = eval('{0}+{0}{0}+{0}{0}{0}'.format(input("Enter the Number n:")))
print(z)

# Question 9

n='without','hello','bag','world'
print(sorted(n))

# Question 10

d = {'Student': ['Rahul', 'Kishore', 'Vidhya', 'Raakhi'], 'Marks': [57, 87, 67, 79]}
print(d['Student'][1])
