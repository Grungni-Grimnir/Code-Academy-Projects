# Code-Academy-Projects
Python Code Academy Projects

Getting Ready for Physics Class - You are a physics teacher preparing for the upcoming semester. You want to provide your students with some functions that will help them calculate some fundamental physical properties. The file is the code to do so.


Sal's Shipping:

Sal runs the biggest shipping company in the tri-county area, Sal’s Shippers. Sal wants to make sure that every single one of his customers has the best, and most affordable experience shipping their packages. In this project, you’ll build a program that will take the weight of a package and determine the cheapest way to ship that package using Sal’s Shippers.

Sal’s Shippers has several different options for a customer to ship their package. They have ground shipping, which is a small flat charge plus a rate based on the weight of your package. Premium ground shipping, which is a much higher flat charge, but you aren’t charged for weight. They recently also implemented drone shipping, which has no flat charge, but the rate based on weight is triple the rate of ground shipping.

Here are the prices:

Ground Shipping

Weight of Package	Price per Pound	Flat Charge
2 lb or less	$1.50	$20.00
Over 2 lb but less than or equal to 6 lb	$3.00	$20.00
Over 6 lb but less than or equal to 10 lb	$4.00	$20.00
Over 10 lb	$4.75	$20.00

Drone Shipping

Weight of Package	Price per Pound	Flat Charge
2 lb or less	$4.50	$0.00
Over 2 lb but less than or equal to 6 lb	$9.00	$0.00
Over 6 lb but less than or equal to 10 lb	$12.00	$0.00
Over 10 lb	$14.25	$0.00

Premium Ground Shipping

Flat charge: $125.00


Write a program that asks the user for the weight of their package and then tells them which method of shipping is cheapest and how much it will cost to ship their package using Sal’s Shippers.


Finding the Cheapest Shipping Method

1. First off, we need to know how much it costs to ship a package of given weight by normal ground shipping.

Write a function for the cost of ground shipping. This function should take one parameter, weight, and return the cost of shipping a package of that weight.

2. A package that weighs 8.4 pounds should cost $53.60 to ship with normal ground shipping:

8.4\ lb \times \$4.00 + \$20.00 = \$53.608.4 lb×$4.00+$20.00=$53.60
Test that your ground shipping function gets the same value.

3. We’ll also need to make sure we include the price of premium ground shipping in our code.

Create a variable for the cost of premium ground shipping.

Note: this does not need to be a function because the price of premium ground shipping does not change with the weight of the package.

4. Write a function for the cost of drone shipping. This function should take one parameter, weight, and return the cost of shipping a package of that weight.

5. A package that weighs 1.5 pounds should cost $6.75 to ship by drone:

1.5\ lb \times \$4.50 + \$0.00 = \$6.751.5 lb×$4.50+$0.00=$6.75
Test that your drone shipping function gets the same value.

6. Using those two functions for ground shipping cost and drone shipping cost, as well as the cost of premium ground shipping, write a function that takes one parameter, weight and prints a statement that tells the user

The shipping method that is cheapest.
How much it would cost to ship a package of said weight using this method.

7. Testing Function:

What is the cheapest method of shipping a 4.8 pound package and how much would it cost?

What is the cheapest method of shipping a 41.5 pound package and how much would it cost?




-PYTHON GRADEBOOK-

You are a student and you are trying to organize your subjects and grades using Python. Let’s explore what we’ve learned about lists to organize your subjects and scores.

If you get stuck during this project or would like to see an experienced developer work through it, click “Get Help“ to see a project walkthrough video.

Tasks
0/7Complete
Mark the tasks as complete by checking them off 
Create Some Lists:

1. Create a list called subjects and fill it with the classes you are taking:

"physics"
"calculus"
"poetry"
"history"

2. Create a list called grades and fill it with your scores:

98
97
85
88

3.Use the zip() function to combine subjects and grades.

Save this zip object as a list into a variable called gradebook.

4. Print gradebook.


Add More Subjects:
5. Your grade for Computer Science class just came in! You got a perfect score, 100!

After your definitions of subjects and grades but before you create gradebook, use append to add "computer science" to subjects and 100 to grades.

6. Your grade for visual arts just came in! You got a 93!

After the creation of gradebook (but before you print it out), use append to add ("visual arts", 93) to gradebook.

7. You also have your grades from last semester, stored in last_semester_gradebook. Create a new variable full_gradebook with the items from both gradebook and last_semester_gradebook.


Len's Slice
You work at Len’s Slice, a new pizza joint in the neighborhood. You are going to use your knowledge of Python lists to organize some of your sales data.

If you get stuck during this project or would like to see an experienced developer work through it, click “Get Help“ to see a project walkthrough video.

Tasks
0/12Complete
Mark the tasks as complete by checking them off
Make Some Pizzas

1. To keep track of the kinds of pizzas you sell, create a list called toppings that holds the following:

pepperoni
pineapple
cheese
sausage
olives
anchovies
mushrooms

2. To keep track of how much each kind of pizza slice costs, create a list called prices that holds:

2
6
1
3
2
7
2
3.

Find the length of the toppings list and store it in a variable called num_pizzas.

4. Print the string "We sell X different kinds of pizza!", with num_pizzas where the X is.

5. Use zip to combine the two lists into a list called pizzas that has the structure:

[(price_0, topping_0), (price_1, topping_1), (price_2, topping_2), ...]
In order to make the result of zip a list, do the following:

list(zip(____, ____))

6. Print pizzas.



Sorting and Slicing Pizzas

7. Sort pizzas so that the pizzas with the lowest prices are at the start of the list.

8. Store the first element of pizzas in a variable called cheapest_pizza.

9. A man in a business suit walks in and shouts “I will have your MOST EXPENSIVE pizza!”

Get the last item of the pizzas list and store it in a variable called priciest_pizza.

10. Three mice walk into the store. They don’t have much money (they’re mice), but they do each want different pizzas.

Slice the pizzas list and store the 3 lowest cost pizzas in a list called three_cheapest.

11. Print the three_cheapest list.

12. Your boss wants you to do some research on $2 slices.

Count the number of occurrences of 2 in the prices list, and store the result in a variable called num_two_dollar_slices. Print it out.
