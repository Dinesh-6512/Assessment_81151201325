# Assessment_81151201325

# problem 3:
string=input("Enter string: ")
sub_string=''
for i in string:
    if i not in sub_string:
        sub_string+=i
print(len(sub_string))


# problem 2:
lst=[]
n1=int(input("Enter readings: "))
n2=input("Enter number: ")
n3=int(input("Enter integer: "))
for i in n2:
    lst.append(i)
add=[]
for i in range(n3):
    get=lst[i]
    add.append(int(get))
print(sum(add))
    
    
    
#   problem 1:  
n1=int(input('Enter records: '))
for i in range(n1):
    st=int(input('Enter start value: '))
    end=int(input('Enter end value: '))
if end<st:
    print("do not start")
elif end>st:
    print(st,end)
else:
    print(st,end)




    

    
    
    
    
    


6
