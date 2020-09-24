def search (list,n):
    i=0

    while i<len(list):
        if list[i]==n:
            globals()['pos']=i
            return True
        i=i+1

    return False

list=[5,8,4,6,9,2]
n=9

if search(list,n):
    print("found at",pos+1)
else:
    print("not found")
    
    found at 5
    
    def linearsearch(arr,elem):
    for i in range(len(arr)):
        if(arr[i] == elem):
            return i+1
        else:
            continue
    return -1
    
limit = int(input("Enter the limit : "))
arry = []
for i in range(0,limit):
    ele = input("Enter alphabet : ")
    arry.append(ele)
    
findele = input('Enter element to find : ')
pos = str(linearsearch(arry,findele))
print("The element found at index "+pos)

enter limit :3
enter Alphabet :E
enter Alphabet :R
enter alphabet :A
enter element to find:R
element found at index 2

