# pat
shuzu=[]
t=int(input())
for i in range(0,t):
    list=input("please input three numbers:").split()
    list=[int(list[i]) for i in range(len(list))]
    shuzu=shuzu+list
for j in range(1,t+1):
    a=shuzu.pop(0)
    b=shuzu.pop(0)
    c=shuzu.pop(0)
    if a+b>c:
        print("Case #%d:true"%(j))
    else:
        print("Case #%d:false"%(j))
