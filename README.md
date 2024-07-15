# python-read-write-file
# Writing to a file
with open('example.txt', 'w') as file:
    file.write("Hello, world!\n")
    file.write("This is a test file.\n")

print("Data written to 'example.txt'")

# Reading from a file
with open('example.txt', 'r') as file:
    content = file.read()

print("Content of 'example.txt':")
print(content)
