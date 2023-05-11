# Author:           James Kometani
# Lab:              Discussion 9
# Date:             05/10/2023
# Description:      Discussion 9
# Input:            rating and is it expensive
# Output:           rating and expensive or not
# Sources:          No one helped me
# Difficulty:       this post feels like a program that is designed for the reviews that someone leaves after they used service or product.if the review has too many questions with closed ended responses it might not be a good reflection of actual experience

#welcome to pizza restaurant reviews
#sample run
#choose restraunt name
#input type price and rating
#output prints out a review based on what was entered
#fast food inexpensive and rating 3
#function can be changed to show different objects


#variables
name = pizzaplace
type = fastfood
price = inexpensive
rating = 0

get_rating = ""
get_price = ""

#program name and welcome or start
print("welcome to pizza review")

#this is an example
pizza_1 = pizza_1("pizzas now" , "fastfood" , "inexpensive" , 5)
pizza_2 = pizza_2("pizzariea" , "fancy" , "expensive" , 1)

print(pizza_1)
print(pizza_2)

#class with objects
def __init__(self, name, type, price, rating):
  self.name = name
  self.type = type
  self.price = price
  self.rating = rating

#input
name = input("enter name of restaurant: ")
type = input("enter type of restaurant: ")
price = input("enter price of restaurant: ")
rating = input("enter rating of restaurant: ")

#output
print("thank you for using the pizza review")
print(name, type, price, rating)
print("this is the results of the review")

#end program

- 👋 Hi, I’m @jameskometan
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
jameskometan/jameskometan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
