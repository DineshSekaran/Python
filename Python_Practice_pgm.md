#Write Program 
```
s=2000
e=3201
l=list()
v1=''
for i in range(s,e):
    if i%7==0 and i%5!=0:
        
        l.append(str(i))
print('Numbers dvisible by 7 and not multiple of 5 between 2000 and 3200 ',l) 
myString = ",".join(l)
print('Numbers dvisible by 7 and not multiple of 5 between 2000 and 3200 ',myString) 
```
