# BASIC-python
#python basics


print('hello github world')
output:'hello github world' #quotations are also come
#if you don't want quotations in the output and you want sapce for each element write like this
print(*'hello github world')


a,b=3,5
print(a is b) # is operator compare the memory location of the variables
#if they belonging to the same memory location it will give true
output: false



#if condition examples
i=10
if(i>5):
  print('i is greater')
 else:
  print('i is not greater')
  
  
  
  
  i=10
  if(i==10):
    if(i<15):
      print('i is smaller')
  if(i<12):
    print('less than 12')
  else:
    print('greater')
    
    
    
  i=20
  if(i==10):
    print('i is 10')
  elif(i==15):
    print('i is 15)
   else:
    print('i is greater)
