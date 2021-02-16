# Addition-of-Numbers
Addition of two or more than two numbers

We will be using a tuple to add two or more than two numbers to simply add as a function

def is the function used to create function named add
we will pass b (*b) as a tuple to store the rest of the numbers

#Code for python
def add(*b) #example for defining the function
  c=0  #Initialize variable with value 0
  for i in b: #For loop till the values present
  c = c + i #iteration to add the tuples and store it in c
  print('Value is ',c) #finally let's print it 

c(4,3,4,5) #example for calling the function

#Output: Value is 16
