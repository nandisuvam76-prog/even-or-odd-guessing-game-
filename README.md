# even-or-odd-guessing-game-
# My python practice codes
number = int(input("Enter A Number:"))
guess = input("Guess even or odd: ")

if number % 2 == 0:
    answer = "even"
else:
    answer = "odd"

if guess == answer:
    print("Correct")
else:
    print("Wrong")

print("Number was:", answer)
