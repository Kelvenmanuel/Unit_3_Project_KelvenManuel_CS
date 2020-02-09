def prime_value1(n):

"""Return 'True' if 'n' is a prime number.  False otherwise."""

# this function said that if the number is 1 is not primer 
if n == 1:
   return False 
   
# this function check if the number if the remainder of the number is 0;
for d in range(2, n):
  if n % d == 0:
    return False 
return True

# this function check what are the numbers prime within 1 and 50 
for n in range (1, 50):
  print(n, prime_value1(n))
  
  
  
