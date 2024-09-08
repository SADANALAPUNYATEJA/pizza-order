# pizza
 pizza order
 pizza=input('you want pizza y/n:')
if pizza=='N' or pizza=='n':
       print("please order")

else:                     
               size=input('what size you want pizza(s/m/l):')
               bill=0
if size=='s' or size=='S':
       bill=100
       print('the prize of small pizza is 100')
       pepperoni=input('we want pepperoni for small pizza (y/n)')
       if pepperoni=='y' or pepperoni=='Y':
                       bill=bill+30
if size=='m' or size=='M':
                       bill=200
                       print('the price of medium pizza is 200')
                       pepperoni=input('we want pepperoni for medium pizza(y/n)')
                       if pepperoni=='y' or peppperoni=='Y':
                                       bill=bill+50
if size=='l' or size=='L':
                bill=300
                print('the price of large pizza is 300')
                pepperoni=input('we want pepperoni for large pizza(y/n)')
                if pepperoni=='y' or pepperoni=='Y':
                    bill=bill+50
cheese=input('we want extra cheese for any size pizza(y/n)')
if cheese=='y' or cheese=='Y':
    bill=bill+20
    print(f"the total bill is {bill}")

