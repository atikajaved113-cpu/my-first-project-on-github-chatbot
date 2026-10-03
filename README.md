# my-first-project-on-github-chatbot
print("Bot: Hi! I'm RuleBot. Type 'bye' to exit.")

while True:
    user_input = input("You: ").lower()

    if user_input == "bye":
        print("Bot: Goodbye! Have a great day.")
        break

    elif user_input == "favorite color":
        print("Bot: My favorite color is blue.")

    elif user_input == "food":
        print("Bot: I don't eat, but pizza sounds delicious!")

    elif user_input == "joke":
        print("Bot: Why did the computer go to the doctor? Because it had a virus!")

    elif user_input == "motivate me":
        print("Bot: Believe in yourself and never give up!")

    elif user_input == "time":
        print("Bot: Time is precious, so use it wisely!")

    else:
        print("Bot: Sorry, I don't understand that.")
