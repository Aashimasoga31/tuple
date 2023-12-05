python
# Creating a tuple
my_tuple = (1, 2, 3, 'hello', 4.5)

# Accessing elements
print("First element:", my_tuple[0])
print("Third element:", my_tuple[2])

# Slicing
print("Slice:", my_tuple[1:4])

# Tuple unpacking
a, b, c, d, e = my_tuple
print("Unpacked variables:", a, b, c, d, e)

# Tuple concatenation
tuple1 = (1, 2, 3)
tuple2 = ('a', 'b', 'c')
concatenated_tuple = tuple1 + tuple2
print("Concatenated tuple:", concatenated_tuple)
