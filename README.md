# Python-programming-task8
import random

def chatbot():
    print("Welcome to the chatbot! Type 'quit' to exit.")

    while True:
        user_input = input("You: ").lower()

        if user_input == "quit":
            print("Chatbot: Goodbye!")
            break
        elif user_input in ["hello", "hi", "hey"]:
            print("Chatbot: Hi there! How can I help you today?")
        elif user_input in ["how are you", "how's it
