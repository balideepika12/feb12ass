hb=200
cb=100
mb=100
nb=50
sb=100
cname=int(input("enter custom name")) 
cphno=int(input("enter customer phone number"))
hbq=int(input("enter hbq packet"))
cbq=int(input("enter cbq packets"))
mbq=int(inpu("enter mbq packets"))
hbq=int(input("enter hbq packets"))
sbq=int(input("enter sbq packets"))
bill=(hb*hbq)+(cb*cbq)+(mb*mbq)+(hb*hbq)+(sb*sbq)
if bill>=5000:
    dis=bill*10%100
elif bill>=3000:
    dis=bill*8%100
    tax=bill*10%100
elif bill>=2000:
    dis=bill*5%100
elif bill>=1000:
    dis=bill*3%100
else:
    dis=0
    tax=bill*18%100
    mb=bill-discount+tax
    print("bill amount:",mb)
