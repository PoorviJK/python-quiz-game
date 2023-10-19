playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()

print("Okay! Let's play :)")
score = 0

answer = input("What does CPU stand for? ")
if answer.lower() == "central processing unit":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What were the names of the official mascots of the 2016 Summer Olympics?")
if answer.lower() == ("Vinicius and Tom"):
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("Who was awarded the 2016 Nobel Prize for Literature? ")
if answer.lower() == "Bob Dylan":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What does an Advent calendar count down to? ")
if answer.lower() == "Christmas":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input(" What is New Year's Eve called in Scotland?")
if answer.lower() == "Hogmanay":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")


print("You got " + str(score) + " questions correct!")
print("You got " + str((score / 4) * 100) + "%.")
