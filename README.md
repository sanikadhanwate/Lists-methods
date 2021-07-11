# Lists-methods
list1 = ["Lilac", "White", "Blue"]
print(list1)

# String, Int & Boolean Data Types
list1 = [1, 2, 3, 4, 5]
list2 = [1, 2, 3, 4, "Sanika"]
print(list1)
print(list2)

# Access List
thislist = ["hat", "pencil", "car"]
print(thislist[0])

# Negative Indexing
thislist = ["buterstoch", "blueberry", "strawberry", "pineapple"]
print(thislist[-3])

# Range of Indexes
thislist = ["one", "two", "three", "four", "five", "six", "seven", "go"]
print(thislist[4:7])

# If/else item exist in the list
list1 = ["apple", "banana", "cherry"]
if "orange" in list1:
  print("Yes, This is in the fruits list")
else:
  print("No, This is not in the fruits list")
  
# Change Item value 
list1 = ["school", "ground", "teacher"]
list1[1] = "students"
print(list1)

# Change Range of Item value 
list2 = ["room", "kitchen", "hall", "mirror", "books", "chair"]
list2[1:3] = ["bed", "wardrobe"]
print(list2)

# Change value by replacing it with new values:
list1 = ["apple", "orange", "banana", "cherry"]
list1[2:3] = ["blueberry", "watermelon"]
print(list1)

# replacing item
list2 = ["laptop", "keyboard", "mouse", "desktop" ]
list2[1:4] = ["paper"]
print(list2)

# Insert item
list = ["lecture", "practical", "assignment"]
list.insert(2, "break")
print(list) 

# Add list 
# append item
list = ["C", "C++", "Java"]
list.append("Python")
print(list)

# Extend list
country = ["India", "Africa", "Ladhak"]
abroad = ["Itlay", "London", "France"]
country.extend(abroad)
print(country)

# Remove
list1 = ["sus", "imposter", "amongus"]
list1.remove("sus")
print(list1)

# pop() method 
list = ["red", "yellow", "blue", "green"]
list.pop(1)
print(list)

list1 = ["A", "B", "C"]
list1.pop()
print(list1)

# whole list gets deleted 
list1 = ["rice", "sprouts", "soup"]
del list1
print(list1)

# del
list = ["abc", "def", "xyz"]
del list[1]
print(list)

# Clear the list
list = ["abc", "def", "xyz"]
del list[1]
print(list)
