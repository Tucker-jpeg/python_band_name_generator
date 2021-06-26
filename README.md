# python_band_name_generator
Create a Band Name Generator Using Python

Python will be required for this project. If you don’t have python currently installed, follow the link below for more information on how to install it. You will need Homebrew to install for a Mac OS and Chocolatey for Windows OS.
https://wiki.python.org/moin/BeginnersGuide/Download
After installation, verify the version that you have installed
$ python3 —- version
Python 3.7.6
Now let’s get started on the name generator. Create a greeting for the name generator so that the user knows what program they are using.
print("Welcome to the Band Name Generator")
We’ll want to ask the user for inputs that will combine to create their band name. Create “city”, “food_name”, and “kicker” variables so that we can use the user’s input values in our code later on. Start a new line after each prompt for input by adding “\n”.
#Ask the user for the city that they grew up in.
city = input("What's name of the city you grew up in?\n")
#Ask the user for the name of their favorite food.
food_name = input("What's your favorite food or drink?\n")
#Ask the user for an obscure occupation
kicker = input("Name a random object, substance, or animal\n")
Combine the 3 variables to create the band name. We’ll add a space in between each variable by including + “ “ between each one.
#Combine the name of their city, food, and object and show them their band name.
print(“Your band name could be “ + city + “ “ + food_name + “ “ + kicker)
Your final output will look something like below:
$ python3 band_name.py
Welcome to the Band Name Generator
What's name of the city you grew up in?
College Park
What's your favorite food or drink?
Cheeto
Name a random object, substance, or animal
Dust
Your band name could be College Park Cheeto Dust
We can adjust the code to ask for different inputs.
