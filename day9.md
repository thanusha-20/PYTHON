#decision statement

age=int(input("enter your age: "))

if age <= 5:
    print("free")
else:
    if age<=12:
       print("half amt")
    elif age>=60:
        print("senior")
    else:
      print("full fair")


time=int(input("enter your time: "))

if time<=8:
    print("time to breakfast.")
elif time<=13:
    print("time to lunch.")
elif time<=20:
    print("time for dinner.")
else:
    print("its not meal time.")
