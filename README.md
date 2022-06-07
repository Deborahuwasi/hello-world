# hello-world
My first repository


print("Python program to check for prime number") 

x = int(input("Enter a number:")) 

y = [i for i in range(2,x) if x % i == 0] 

z = [j for j in range(2,x) if x % j != 0] 

if y != []: 

    print("Your number is composite","divisible by",y,"and has",len(y),"factors") 

elif z != []: 

    print("Your number is prime") 

else: 

    print("There seems to be an error in your input.Please try again") 
