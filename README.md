# Hot-Dog-Cookout-Calculator

amountOfPeople = int(input("Greetings! ... could you kindly tell me the amount of people attending? "))
amountOfHotDogsPer = int(input("and what's the amount of hot dogs per person: "))

hotDogsPerServing = 10
bunsPerServing = 8

sumAmountOfHotDogs = amountOfPeople * amountOfHotDogsPer

minPackageOfHotDogsRequired = amountOfPeople // hotDogsPerServing
minPackageOfHotDogBunsRequired = sumAmountOfHotDogs // bunsPerServing
numberOfHotDogsLeftOver = sumAmountOfHotDogs % hotDogsPerServing
numberOfHotDogBunsLeftOver = sumAmountOfHotDogs % bunsPerServing

print("Minimum number of hot dogs required =", minPackageOfHotDogsRequired)
print("Minimum number of hot dog buns required =", minPackageOfHotDogBunsRequired)
print("Amount of hot dogs left over =", numberOfHotDogsLeftOver)
print("Amount of hot dog buns left over =", numberOfHotDogBunsLeftOver)
