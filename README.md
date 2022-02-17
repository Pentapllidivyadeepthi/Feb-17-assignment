# Feb-17-assignment
n=int(input())
sumo=0
sume=0
for i in range(1,n+1) :
    if i%2==0 :
        sume=sume+i
    else :
        sumo=sumo+i 
print('sum of odd numbers',sumo)
print('sumof even numbers',sume)
