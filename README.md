# finding-position-of-existing-elements
L=list(map(int,input("Enter list elements: ").split()))
n=int(input("Enter number to search: "))
f=0
for i in range(len(L)):
    if L[i]==n:
        print("Item found at position",i)
        f=1
        break
if f==0: print("Item not found")

Enter list elements: 3 4 5 6 7 8
Enter number to search: 7
Item found at position 4



