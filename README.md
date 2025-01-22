def chatbot():
    print("Welcome to the chatbot!")
    
    # Collect user's name and age
    name = input("May I please have your name? ")
    age = input("How old are you? ")
    print(f"Nice to meet you, {name}! You are younger than you look for a {age} years old.")

    # Ask how the chatbot can help
    print("How can I help  you today?")

    while True:
        # Display menu options
        print("\nPlease choose an option from the menu below:")
        print("1. Placeholder Option 1")
        print("2. Placeholder Option 2")
        print("3. Exit")
        
        # Get user's choice
        choice = input("Enter the number of your choice: ")
        
        # Handle user's choice
        if choice == "1":
            print("You selected Placeholder Option 1. This feature is under construction.")
        elif choice == "2":
            print("You selected Placeholder Option 2. This feature is under construction.")
        elif choice == "3":
            print("Goodbye! Thank you for using the chatbot.")
            break
        else:
            print("Invalid choice. Please try again.")

# Run the chatbot
chatbot()
