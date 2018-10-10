# A program which accepts a sequence of comma-separated numbers from console and generate a list.

l =[]
for x in range(1000):
    num = input('insert a valid number')
    if num.isalpha():
        break
    else:
        l.append(num)
print(l)
