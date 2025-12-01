# Palindrome-number
def is_palindrome_string(number):
    """
    Checks if a number is a palindrome by converting it to a string
    and comparing it to its reverse.
    """
    num_str = str(number)  # Convert the number to a string
    reversed_str = num_str[::-1]  # Reverse the string using slicing
    return num_str == reversed_str  # Compare original and reversed strings

# Get input from the user
num = int(input("Enter a number to check: "))

# Check and print the result
if is_palindrome_string(num):
    print(f"{num} is a palindrome number.")
else:
    print(f"{num} is not a palindrome number.")