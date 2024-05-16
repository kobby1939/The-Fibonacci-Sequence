# The-Fibonacci-Sequence
# Define the required variables
a= 0
b= 1

# Take the input from the user
count= 10

# Check if the count is valid
if count <= 0:
    print("Please enter a positive integer")
else:
    print("0 1 1 2 3 5 8 13 21 34:")
    for _ in range(count):
        print(a, end=' ')
        # Update the values of a and b to generate the next Fibonacci number
        a, b = b, a + b
        
