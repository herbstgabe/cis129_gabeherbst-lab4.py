# Module 4 lab
# Gabe Herbst
#program calcualtes the bonusues of a company
#it shows montly sales and sales increased by inputs.
# calculates store bonuses



#varibales

monthlysales = 0
storeAmount = 0 
employeeAmount = 0
prompt = ' enter monthly sales amount:'
#this code gets monlty sales
monthlySales = float(input(prompt))
#this code determines store bonuses
if monthlySales>= 110000:
    storeAmount = 6000
elif monthlySales>= 100000:
    storeAmount= 5000
elif monthlySales >= 9000:
    storeAmount= 4000
elif monthlySales>= 80000:
    storeAmount = 3000
else:
    storeAmount =0 

#this code determines the employee bonuses
salesIncrease = float(input('enter sales increase in percent'))
salesIncrease = salesIncrease /100

if salesIncrease >= .05:
    employeeAmount = 75
elif salesIncrease >= .04:
    employeeAmount = 50
elif salesIncrease >= .03:
    employeeAmount = 40
else:
    employeeAmount = 0
#this code will print he bonus
print(' the store bonus amount is $', storeAmount)
print(' The employee bonus amount is $',employeeAmount)
if (storeAmount==6000)and(employeeAmount == 75):
    print('congratss you have reached the highest bonus amount possible')

    
