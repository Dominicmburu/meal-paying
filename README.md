# meal-paying
# A python code for meal paying amongst your friends.

import random
test_seed = int(input("Create a seed number: "))
random.seed(test_seed)
namesAsCSV = input("Give me everybody's names,")
names = namesAsCSV.split(", ") #creating a list/array
random_choice = random.choice(namesAsCSV)
print(random_choice+" is going to buy the meal")
