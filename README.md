# Data collections in Python 
- Lists (shopping list)

#What is a list
- Lists is commonly used to store the data
- Lists are mutable
- Syntax [] is used to create a list

- shopping_list = ["bread", "chocolate", "avacados", "milk"]
               #    0           1           2           3
- print(shopping_list)
- print(shopping_list[1])
- print(shopping_list[-2])

# change the value of 0 index from bread to orange
- print(shopping_list)
- shopping_list[0] = 'Orange'
- print(shopping_list)


#use append to add things into the list

- shopping_list.append('cherries')
- print(shopping_list)

# remove orange from shopping list
- shopping_list.remove('orange')
- print(shopping_list)

# pop() deletes the last item on the list
- shopping_list.pop()
- print(shopping_list)

#Can we mix data types in a list?
- mixed_list = [1, 2, 3, "one", "two", "three" ]
- print(mixed_list)



# #What is a list
# #Lists is commonly used to store the data
# #Lists are mutable
# #Syntax [] is used to create a list
#
# shopping_list = ["bread", "chocolate", "avacados", "milk"]
#                #    0           1           2           3
# # print(shopping_list)
# # print(shopping_list[1])
# # print(shopping_list[-2])
#
# # change the value of 0 index from bread to orange
# print(shopping_list)
# shopping_list[0] = 'Orange'
# print(shopping_list)
#
#
# #use append to add things into the list
#
# shopping_list.append('cherries')
# print(shopping_list)
#
# # # remove orange from shopping list
# # shopping_list.remove('orange')
# # print(shopping_list)
#
# # pop() deletes the last item on the list
# shopping_list.pop()
# print(shopping_list)
#
# #Can we mix data types in a list?
# mixed_list = [1, 2, 3, "one", "two", "three" ]
# print(mixed_list)


# Tuples - The difference between Lists and Tuples?
# Syntax tuples()
# Tuples are exactly the same as Lists but they are immutable (cannot change/be modified)

essential = ("paracetamol", "tooth paste", "tea bags")
print(essential)
print(type(essential))
essential[0] = "cereal"
print(essential)

# Dictionaries?
# Dictionaries use KEY VALUE pairs to save the data
# The data can be retrieved by it's value or the key
# Syntex dictionary{} list[] tuple()
# Within the dictionary we can also have a list declared

# Let's create one
# dev_ops_student = {
#     "key": "value",
#     "name": "James",
#     "stream": "devops",
#     "completed_lesson": 3,
#     "completed_lesson_names": ["variables", "data types", "collections"]
#     #key                 value: 0               1               2
# }
# print(dev_ops_student)
# #confirm the type
# print(type(dev_ops_student))

# print(dev_ops_student["name"])
# print(dev_ops_student["completed_lesson"])
# print(dev_ops_student["completed_lesson_names"][1])
#
# print(dev_ops_student.keys())
# print(dev_ops_student.values())

# add "operators" as a value of completed lesson

# dev_ops_student["completed_lesson_names"].append("Operators")
# print(dev_ops_student["completed_lesson_names"])

# change the completed lesson from 3 to 4

# dev_ops_student["completed_lesson"] = 4
# print(dev_ops_student["completed_lesson"])

# remove the "data type" from completed_lesson_names

# dev_ops_student["completed_lesson_names"].remove("data types")
# print(dev_ops_student["completed_lesson_names"])

# Sets? and the difference is that sets are unordered
# Syntax {}
# Lets create a set

car_parts = {"wheels", "windows", "doors"}
print(car_parts)
print(type(car_parts))
car_parts.add("seats")
print(car_parts)
car_parts.discard("doors")
print(car_parts)
