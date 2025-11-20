# basic-chat-bot
basic chat bot using python
def chatbot():
    print("Chatbot: Hello! I am your ChatBot.")
    print("Type 'bye' to end the chat.\n ")
while True:
        user_input=input("You:").lower()
        if user in["hi","hello"]:
            print("Hi!How are you?")
        elif user=="how are you":
            print("I'm fine,thanks!and you")
        elif user in["I am fine","good"]:
            print("That's great")
        elif user=="what is your name":
            print("I am basic chatbot.")
        elif user in["what do you do"]:
            print("I'm print massage according to user demand")
        elif user=="bye":
            print("Good bye! Have a nice day!")
            break
        else:
            print("Sorry, I don't understand that.")

