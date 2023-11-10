#Write a program that creates a list of odd number from 1 to 50 that is divisible by 3

result=[]

for i in range(1,50):
    if (i%3==0):
      result.append(i)

   
print(result) 
