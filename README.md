# 1.5
#Assignment 5
l =[]
for x in range(1000):
    num = input('insert a valid number')
    if num.isalpha():
        break
    else:
        l.append(num)
print(l)
