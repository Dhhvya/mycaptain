#FirstTask
import math

# Input the radius from the user
radius = float(input("Input the radius of the circle: "))

# Calculate the area of the circle
area = math.pi * (radius ** 2)

# Print the result
print(f"The area of the circle with radius {radius} is: {area}")


#SecondTask
# Input the filename from the user
filename = input("Input the Filename: ")

# Split the filename to get the extension
extension = filename.split(".")[-1]

# Print the extension
print(f"The extension of the file is : '{extension}'")
