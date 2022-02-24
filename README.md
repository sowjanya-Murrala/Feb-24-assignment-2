x=input('Enter numbers:')
l=x.split()
o=[]
e=[]
for i in l:
    i=int(i)
    if i%2==0:
        e.append(i)
    else:
        o.append(i)
for i in range(len(o)):
    print(o[i],end=' ')
print(' ',end=' ')
for i in range(len(e)):
    print(e[i],end=' ')
    
    
    output:
    enter numbers:3 4 6 8 2 5
    3 5  4 6 8 2
