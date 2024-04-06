# Using Flipper Zero for Brute Force Attack
def brute_force_unlock():
    while True:
        try_code = generate_code()  # Function to generate code
        if try_code == correct_code:
            unlock_device()
            break
