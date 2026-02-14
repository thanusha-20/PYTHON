#tuple

a=("apple","banana","kiwi","goa","orange")
b=("kiwi","strawberry")
print(a[2:4])
print(a+b)
print(len(a))
print(type(b))
print(a[3])


#sets
d={"apple","banana","kiwi","goa","orange"}
e={"kiwi","strawberry"}

print(d | e)  #union
print(d & e) #intersection
print(d - e) #difference

c=list(d)
print(c)
