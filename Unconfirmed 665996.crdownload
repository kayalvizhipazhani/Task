from array import *

T = [ [3,2], [4,3], [2,3], [3,4] ]
s = []
for i in range(0,T[0][1]):
    list1 = []
    for j in range(0,T[0][0]):
       if j==0:
           list1.append('w')
       elif j==1:
           list1.append('m')
       elif j==2:
            list1.append('a')
    s.append(list1)
print(s)

e = []
for i in range(0,T[3][1]):
    list1 = []
    for j in range(0,T[3][0]):
       if j==0:
           list1.append('w')
       elif j==1:
           list1.append('m')
       elif j==2:
            list1.append('a')
    e.append(list1)
print(e)

list_mid = []
for i in T:
    list_mid.append(i)
#calculate length
len = len(list_mid)

mid = []
for i in range(1,len-1):
    list3 = []
    for j in range(0, T[i][1]):
        list2 = []
        for k in range(0, T[i][0]):
            if k == 0 or k == T[i][0] - 1:
                list2.append('a')
            else:
                list2.append('m')
        list3.append(list2)
    mid.append(list3)
print(mid)

final1 = []
k = 0

for i in s:
    add = []
    add.append(i)
    for j in range(0, mid.__len__()):
        add.append(mid[j][k])
    k = k + 1
    final1.append(add)

for i in s:
    add = []
    add.append(i)
    for j in range(0, mid.__len__()):
        add.append(mid[j][k])
    k = k + 1
    final1.append(add)
print(final1)




