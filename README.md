# Kama
Just Kama
a=9
b=[5,9,6,3,8,4,1,7,2]
for run in range(a-1):
    for i in range(a-1):
        if b[i]>b[i+1]:
            b[i+1],b[i]=b[i],b[i+1]
print(b)
