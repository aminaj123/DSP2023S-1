1. def dummy(i):

    j=0 if i == 0 else 1 if i ==1 else 'j is not in [0,1,2]'
    
print(dummy(2))

2.  (A) Cdegrees = [-20, -15, -10, -5, 0, 5, 10, 15, 20, 25, 30, 35, 40]

print(' C       F')

num= len(Cdegrees)

while num >=0:

    F= (9.0/5)*C + 32
    
    print ('%5d %5.1f' % (Cdegrees[num], F))
    
    num = num -1
  
 3.  for n in numbers:
    i = len(numbers)//2
    del numbers[i]
    print ('n={}, del {}'.format(n,i), numbers)
   
   The weird behavior observed in this behavior is that it deletes the middle index so it seems like it is skipping numbers. 
   
   4.  
 eps = 1.0
 
while 1.0 != 1.0 + eps:

    print ('...............', eps)
    
    eps /= 2.0
    
print ('final eps:', eps)

The code is adding 1.0 to eps. eps is the mahine epiloson this is a constant that is the smallest postive float value greater then 0. Adding the print 

( '...............', eps) prints the dots when printing the output to the 1+ eps. This is why the output has ............... before the answer.

5.

from math import sqrt

for n in range(1, 60):

    r_org = 2.0
    
    r = r_org
    
    for i in range(n):
    
        r = sqrt(r)
        
    for i in range(n):
    
        r = r ** 2
        
    print ('With {} times sqrt and then {} times **2, the number {} becomes: {:.16f}'.format(n,n,r_org,r))

This code uses a built in function to preform the square root and multipication functions adding the reverse and forward tasks. The code uses a range function

which returns the a sequence of number, starting from 0, back to one by default. The print function adds the string to the output of the 

function this can help make the output easier to understand for the coder. We do not get the reover the 2.0 value because we made r_0 equal to 2.0

2.0 is also a float type. 

6. extra credit 

7. 
answer: 

q = ['abcdefgh']

for x in q:

     print(x)
