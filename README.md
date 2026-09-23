#Given a product name and its price, format a string to display: "Product: ___, Price: _____$", where price should be displayed with two decimal places.
Product_name = input("ENTER THE NAME OF PRODUCT: ")
Price = int(input("ENTER TNE PRICE OF THE PRODUCT in $: "))
print("The name of the prooduct is :",Product_name)
print("And the price of the product is :",Price)





#Create a program that takes the title, author, and publication year of a book. Print a summary in the format: "Title: '___', Author: ____, Published: _____".
Name_of_author = input("Enter the name of the author = ")
Name_of_book = input("Enter the name of the Book = ")
Publication_year = input("Enter the publication year = ")
print("The name of the author is :",Name_of_author)
print("The name of the book is :",Name_of_book)
print("The publication year is :",Publication_year)




#Write a program that prints the temperature in Celsius and Fahrenheit. Use the format() method to show the temperature values in the format: "Temperature: _______°C or __________°F".
celsius = 25
farenheit = (celsius*9/5) + 32
print("Temperature: {}°C or {}°F".format(celsius, farenheit))





# Taking input from the user
Name = input("Enter your name : ")
Age = input("Enter your age : ")
print("Name :{1},Age :{0}".format(Age,Name))




#Write a program that outputs an event schedule with the event name and time. Format the output using positional arguments to display: "Event: {1} at {0}".
Event = input("Enter the Event name :")
Time = input("Enter the Event Time :")
print("Event: {1} at {0}".format(Time, Event))





#Given a product name and its price, print a summary using positional arguments in the format: "The price of {0} is ${1}".
Product_name = input("ENTER THE NAME OF PRODUCT: ")
Price = int(input("ENTER TNE PRICE OF THE PRODUCT in $: "))
print("Product_name: {1} at ${0}".format(Price, Product_name))




# Taking input from the user
greeting = input("Enter a greeting (e.g., Hello): ")
name = input("Enter a name: ")
print("{1}, {0}!".format(greeting, name))


This are my python codes
