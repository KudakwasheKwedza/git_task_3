#create varibabes to store number
num1 = 0 

enter_num = int(input("plase Enter a Number (enetr -1 to exit):"))

#create while loop
while num1 != -1:
    num1 += enter_num  #same as num1 = num1 + enter_num

    enter_num = int(input("plase Enter a Number(enter -1 to exit):"))

    if enter_num == -1:
      print(num1)
      break 
#Use 'break' to break break out iof the loop 1
