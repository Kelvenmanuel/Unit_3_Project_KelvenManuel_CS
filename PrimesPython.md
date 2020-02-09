def prime_value1(n):

"""Return 'True' if 'n' is a prime number.  False otherwise."""

 º this function said that if the number is 1 is not primer 
if n == 1:
   return False 
   
ª this function check if the number if the remainder of the number is 0;
for d in range(2, n):
  if n % d == 0:
    return False 
return True

º this function check what are the numbers prime within 1 and 50 
for n in range (1, 50):
  print(n, prime_value1(n))
  
  ============================= Expanation  of the program ==================================
  
  there are 3 main moments in this video/ code.
  First they give the definition of a prime number, and then they create a program to identify prime numbers between 1 and 21 ```for n in range (1, 21):
  print(n, prime_value1(n)) ```, based on the fact  that 1 is not a prime number, and that starting dividing the number by 2 until itself, if the remainder of these operations is 0 the number is not prime, otherwise the number is prime. ```if n == 1:
   return False  ``` & ```for d in range(2, n): if n % d == 0: return False return True``` then they created a function that calculate the time that the computer would take to find prime numbers between 1 and 100000. 


  
  the result of that was 56s, this take us to the 2 part of the video/code. In this part they try to create a program that can gives the primes number faster than the past one where they use another way, testing all divisors from 2 through square roof of n ( intenger ), so they use the Math module , then to find the largest possible divisor they took the square root of n and round down using the floor funtion, additionaly to test this they had to add 1 to the range function```max_divisor = math.floor(math.sqet(n)) ``` & ``` for d in range(2, 1+ max_divisor):  if n % d == 0 return false```. At the end they try again to calculate the time for the computer to take the primers numbers within  1 and 10000, the result was 0.32..s but then they tried to improve more the code.
  
  this lead us to the third moment of the code as they said step 3 where, where they stated checking if n is a even number startind counting for 2 providing that 2 is a prime number, so they said if is a even number and not 2 the n is not a prime number,  and they only do this for intengers larger than 2  for that reason above ``` if n == 2 : return false``` & ``` if n > 2 adn n % 2 == 0:  return false ```then to range the possible divisors they add one to the range and this should cover all odd numbers until the limit and eliminate roughly half of the division operation```max_divisor = math.floor(math.sqet(n)) ``` & ``` for d in range(3, 1+ max_divisor):  if n % d == 0 return false``` with this they verify again the time and the result was a success 0.1s 
  
  I stil have questions about the math module and how does work ?
