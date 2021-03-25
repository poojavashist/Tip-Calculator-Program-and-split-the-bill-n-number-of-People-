# Tip-Calculator-Program-and-split-the-bill-n-number-of-People-
Tip Calculator Program and split the bill n number of People 
If the bill was $150.00, split between 5 people, with 12% tip. 
#Each person should pay (150.00 / 5) * 1.12 = 33.6
# 

print("welcome to the top calculater!")

bill = float(input("what was the total bill ? $  "))
tip = int(input("how much tip you like to give? 10,15,12?  :"))
people =int(input("how many people to split the bill  : "))

tip_as_percent = (tip/100)
print("how much tip_as_percent : ")
print(tip_as_percent)

total_tip_amount = bill * tip_as_percent
print("total_tip_amount : ")
print(total_tip_amount)

total_bill= bill + total_tip_amount
print("total_bill :" )
print(total_bill)

bill_per_person = total_bill/people
print("bill_per_person :")
print(bill_per_person)

final_amount= round(bill_per_person ,2)
print("Final amount per person will pay:") 
print(final_amount)
