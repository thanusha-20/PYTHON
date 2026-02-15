#dictionary
fruits={
    "a":"apple",
    "b":"banana",
    "c":"cherry"
}
print(fruits)

#acessing elements in dictionary

print(fruits.get("a"))



print(fruits.keys())
print(fruits.values())
print(fruits.items())

print(type(fruits))

#updating
x={"k":"kiwi"}
fruits.update(x)
print(fruits)
