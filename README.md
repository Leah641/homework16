# homework16

a=int(input("What is a:"))

b=int(input("What is b:"))

c=int(input("What is c:"))

delta=b**2-4*a*c

if a==0:

    print("error")

elif delta<0:

    print("There are no real roots.")

elif delta==0:

    print("There is only one root, which is ",-b/(2*a))

elif delta>0:

    print("The root is ",((-b)+delta**(1/2))/(2*a)," and ",((-b)-delta**(1/2))/(2*a))

else:

    print("error")

quit()
