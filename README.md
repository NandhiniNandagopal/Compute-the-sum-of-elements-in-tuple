```python
# Cnum=int(input("Enter the numbers of tuples:"))
tup_list=[]
for i in range(num):
    elements=input(f"Enter elements of tuple {i+1}: ")
    tuple_elements=tuple(map(int,elements.split()))
    tup_list.append(tuple_elements)
result=list(map(sum,tup_list))
print("Sum of the elements:",result)
            
ompute-the-sum-of-elements-in-tuple
