# Elite101-Prework by Reeddhiman Pradhan (Chatbot)

print("Welcome to the Elite 101 Chatbot!")

name = input("Please enter your name: ")

age = int(input("Nice to meet you, " + name + "! How old are you? "))

print("Welcome, Zach! Oh, to be " + str(age) + " again! How can I help you today?")

print("Please choose from the following options :")

print("1. Placeholder option 1")
print("2. Placeholder option 2")
print("3. Placeholder option 3")
print("4. Exit the chat")

choice = int(input("Please enter the number of your choice: "))

if choice == 4:
    print("It was nice talking to you, " + name + "! Have a great day!" )
