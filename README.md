# two-dimensional-arrays
from array import*
a=[[1,2,3],[4,5,6],[7,8,9]]

print(a[0])
print(a[1][1])

for i in range(a):
    for j in range(i):
        print(c,end='')
    print()
        
 #INSERT THE NEW ARRAY
 from array import*
a=[[1,2,3],[4,5,6],[7,8,9]]
a.insert((1),[8,4,3])
print(a)
        
        
 #INSERT THE NEW ARRAY IN 2D
 from array import*
a=[[1,2,3],[4,5,6],[7,8,9]]
a.insert((1),[8,4,3])
for i in a:
    for j in i:
        print(j,end='')
    print()


 #UPDATE THE NEW ARRAY IN 2D
 
from array import*
a=[[1,2,3],[4,5,6],[7,8,9]]
a[0][2]=0
a[2]=[10,9]
for i in a:
    for j in i:
        print(j,end='')
    print()


#OUTPUT
[1, 2, 3]
5

123
456
789


[[1, 2, 3], [8, 4, 3], [4, 5, 6], [7, 8, 9]]



123
843
456
789


120
456
109
> 
