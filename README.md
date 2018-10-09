# anthony huynh
# ECS 032A
# 10-07-2018
# TRIVIAL PURSUIT ASSIGNMENT 2

score = 0

#welcome message
print("Trivial Pursuit 12 Questions")
print("")

#question one
print("ART AND LITERATURE: Who painted the Mona Lisa?")
print("a. Vincent van Gogh")
print("b. Michelangelo")
print("c. Leonardo da Vinci")
one = input("")

if one == "c":
    print("Enter your choice:Correct!")
    score = score + 1 
else:
    print("Enter your choice:The correct answer was c")
    

#question two
print("ART AND LITERATURE: What did the 7 dwarves do for a job?")
print("a. construction workers")
print("b. miners")
print("c. fishers")
two = input("")

if two == "b":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was b")


#question three
print('ENTERTAINMENT: Who sang "My Way"?')
print("a. Gordon Jenkins")
print("b. Louis Armstrong")
print("c. Frank Sinatra")
three = input("")

if three == "c":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was c")


#question four    
print("ENTERTAINMENT: How many oscars did Alfred Hitchcock win?")
print("a. 0")
print("b. 1")
print("c. 2")
four = input("")

if four == "a":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was a")


#question five
print("GEOGRAPHY: Which is the largest ocean?")
print("a. Pacific")
print("b. Atlantic")
print("c. Indian")
five = input("")

if five == "a":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was a")


#question six
print("GEOGRAPHY: Which river goes through London?")
print("a. River Severn")
print("b. River Tyne")
print("c. River Thames")
six = input("")

if six == "c":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was c")


#question seven
print("HISTORY: What year did the Spanish Civil War end?")
print("a. 1937")
print("b. 1939")
print("c. 1945")
seven = input("")

if seven == "b":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was b")


#question eight
print("HISTORY: Who was the first president of America?")
print("a. Washington")
print("b. Lincoln")
print("c. Jefferson")
eight = input("")

if eight == "a":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was a")


#question nine
print("SCIENCE AND NATURE: Who invented the telephone?")
print("a. Bell")
print("b. Edison")
print("c. Tesla")
x = input("")

if x == "a":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was a")


#question ten
print("SCIENCE AND NATURE: Where is the smallest bone in the body?")
print("a. Ear")
print("b. Nose")
print("c. Finger")
ten = input("")

if ten == "a":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was a")


#question eleven
print("SPORT AND LEISURE: What is the first letter on a typewriter?")
print("a. Z")
print("b. A")
print("c. Q")
eleven = input("")

if eleven == "c":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was c")


#question twelve
print("SPORT AND LEISURE: How many months have 31 days?")
print("a. 5")
print("b. 6")
print("c. 7")
twelve = input("")

if twelve == "c":
    print("Enter your choice:Correct!")
    score = score + 1
else:
    print("Enter your choice:The correct answer was c")

#score print
print("Your final score is "+str(score)+" out of 12")

#end message
if score < 5:
    print("You were unlucky!")
elif (score >= 5 and score <= 8):
    print("You did better than chance!")
elif (score >=9 and score <=11):
    print("You are a trivia star!")
else:
    print("Perfect!")
