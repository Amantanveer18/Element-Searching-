# Element-Searching-

a = [1,2,3,4,5]
b = int(input("enter a number"))

def search(a, b):
    for i in a:
        if b == i:
            return True
        else:
            return False

print(search(a, 4))  
