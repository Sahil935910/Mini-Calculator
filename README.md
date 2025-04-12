# Mini-Calculator
#i used python to make the mini calculator
print ("~~~~~ mini Calculator ~~~~~")
num1 = float(input ("enter the first number here: "))
num2 = float(input ("enter the second number here: "))
print("print 1 for addition \npress 2 for substraction \npress 3 for multiplication \npress 4 for division")

choise = int(input("enter your choise from 1-4: "))

if choise == 1:
  print (num1 + num2)
elif choise == 2:
    print (num1 - num2)
elif choise == 3:
      print (num1 * num2)
elif choise == 4:
        print (num1 / num2)
else:
        print ("please put valid input sir and mam")
