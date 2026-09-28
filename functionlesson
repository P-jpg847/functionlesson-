"""Quick 10-Minute Lesson: Python Functions

Goal:
- Understand what a function is
- Learn how to define and call a function
- See return values, parameters, and default arguments
- Practice with a simple example you can run right away

A function is a reusable block of code that performs a task.
Think of it like a recipe: you give it ingredients (arguments),
it does work, and optionally returns a result.
"""

# -----------------------------------------------------------------------------
# 1) The basic structure of a function
# -----------------------------------------------------------------------------
# A function starts with the keyword `def`, followed by a name,
# then parentheses `()`. Inside, we write the code.

def greet_user(name):
    # This function uses the parameter `name`.
    print(f"Hello, {name}! Welcome to Python!")


# Call the function with a value.
# This is how we pass information into the function.
greet_user("Ava")
greet_user("Ava")
greet_user("Ava")
greet_user("Ava")


# -----------------------------------------------------------------------------
# 2) Returning values
# -----------------------------------------------------------------------------
# A function can also return a value to the caller using `return`.
# This makes the function more useful, because you can use the result later.

def add_numbers(a, b):
    total = a + b
    return total


result = add_numbers(10, 5)
print(f"10 + 5 = {result}")

# -----------------------------------------------------------------------------
# 3) Default parameter values
# -----------------------------------------------------------------------------
# You can give parameters default values. If the caller does not provide
# a value, Python uses the default instead.

def describe_pet(name, animal="dog"):
    print(f"{name} has a {animal}.")


describe_pet("Milo")
describe_pet("Zoe", "cat")
describe_pet("Buddy", "hamster")


# -----------------------------------------------------------------------------
# 4) Functions can take multiple arguments
# -----------------------------------------------------------------------------
# This is useful when you want to group several inputs into one task.

def area_of_rectangle(width, height):
    area = width * height
    return area


room_area = area_of_rectangle(8, 5)
print(f"Area of rectangle: {room_area} square feet")

# -----------------------------------------------------------------------------
# 5) A function can call another function
# -----------------------------------------------------------------------------
# This keeps code organized and reusable.

def square(number):
    return number * number


def print_square_and_double(number):
    squared = square(number)
    doubled = squared * 2
    print(f"Number: {number}")
    print(f"Square: {squared}")
    print(f"Double the square: {doubled}")


print_square_and_double(4)

# -----------------------------------------------------------------------------
# 6) A quick exercise: build your own function
# -----------------------------------------------------------------------------
# Notice the pattern:
# 1. Define function with def
# 2. Accept parameters
# 3. Do work
# 4. Return a value if needed

def is_even(number):
    # `%` gives the remainder after division.
    # If remainder is 0, the number is even.
    if number % 2 == 0:
        return True
    return False


for value in [2, 7, 10, 13, 22]:
    print(f"{value} is even? {is_even(value)}")

# -----------------------------------------------------------------------------
# 7) Key ideas to remember
# -----------------------------------------------------------------------------
# - Functions let you reuse code.
# - Parameters are inputs to a function.
# - Return values send results back to the caller.
# - Functions make code easier to read and maintain.

print("\nLesson complete! You now know the basics of Python functions.")
print("Testing testing")
print("Testing again")
