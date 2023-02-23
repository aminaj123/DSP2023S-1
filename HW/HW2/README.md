Python values problems
  
  1. a. When we type this we get a syntax errror. This is because of the slash
     
     b. We get 0.5 because it 1 divided by 2 is 0.5 
     
     c. the int8 means that the it can store 8 bits. However putting it into the jupyter notebook gives you a name error 
     
     d. the int8 means that it can store 8 bits. However putting it into jupyter notebook gives youa a nname error 
     
     e. The answer for this is -7. This is because the ^ uses the "xnot" command. Basically the ^ looks for the binary value of both 
     -5 ^ 2, checks if they are they are similar. Once this is completed you get a number and that numbers binary value is -7 
     
     f. The answer is -25 this is because the command is to square -25 
     
     g. The anser to this 25. The ^ sqaures the -5 but the parentheses makes the answer postive. 
     
     h. The answer to this is 7.0 this is differrent than the int answer which would just be 7 
     
     j. The answer to this 30.0 this preforms the mathmatical operation. 
 
 2. If you put in a higher number then the you will get an error. For example putting in a higher number will result in an error because the int8 only stores 8 bits 
  this will result in a syntax error. The lowest number for int16 is -32768 and the highest 32767. For int32 the lowest number is 
 -2147483648 and the highest number is 2147483647
 
 Python Variable problems
  
1.  
a = 1  this makes a=1. From now on a in this code will be equal to 1 

b = 'x'.    this makes b equal to x. Now x and b are the same in this code

c = true  this causes a sytnax error because the term "true" does not exist in python 

whos a b c this will also cause a syntax error 

a == c this equal sign checks if the this equal, because they are not equal this is false 

a + c we cannot add these because c is not a integer value

d = [1 2 3 4] this makes d equal to this list 

e = ['a' 'b' 'c' 'd'] this will make the list equal [abcd] 

f = ['a','b','c','d'] this will make a list of  a, b, c , d 

g = ['abcd'] this will give you can an 'abcd' list 

h = {‘a’ ‘b’ ‘c’ ‘d’}  this gives you a 'abcd' list 

i = { a b c d} this gives you a syntax error 

whos d e f g h i

class(a)

type(a) because we defined a as 1 in the first line this will result as int as an output 

True this is bool type 

true syntax error because t is not capilized 

False this is bool type 

false syntax error because f is not capitlaized 
Overall this code would not run because of the syntax errors 

2. 

Part A. 

Part A. a = 5
b = a
print (id(a), id(b))
 This reuslts in the output of 140659105262000 140659105262000. Notice that both numbers are the same this is because we set a=5 and we made a=b. The command id
 
 looked at the address of the number 5 and the print command gaves the id or "adress" of a a and be which is the same in this case 
 
 c = b
 
b = 3

print (a,b,c)

print (id(a),id(b),id(c))

The output of this command is 

5 5 5

140659105262000 140659105262000 140659105262000

the first output of "5 5 5" is because we set a=5 and made b=a and c=b this will then make everything equal to 5 
and print a 5 5 5 output. 

the second part of the output " 140659105262000 140659105262000 140659105262000" is the address of 5. Remember because 
a=b=c this means this all equals 5 and gives us the same id for all three because it is the same number. 

b = a

b = 5

print (id(a), id(b))

the output of this is 140659105262000 140659105262000

we are still looking at the 5 address because a=b=5 

Part B
a=[5]

b=a

print(id(a), id(b))

the output of this command is 140658300554880 140658300554880. 

We made a=b so both a and b is equal to [5]. This index value has a id of 140658300554880 

b.append(1)

print(a,b)

print(id(a),id(b))

the output of this is 

[5, 1] [5, 1]

140658300554880 140658300554880

The append command appends an element to the end of the list. In this case it is 1 because the command is

b.append(1) at the end of the list that why when we type print(a,b) we get [5,1]. the id of this 140658300554880 which is 

why we get this an output. 

Part C

a = [5]
b = list(a)
print (a,b)
print (id(a), id(b))
 the output of this is 
 [5] [5]
140658571498688 140659108464704
First we defined a to be equal to [5] 
then we made b=list(a). The list command is used to store multiple items in a single variable so in this case we made
b=[5] as well. The second part of the output prints out the specific id associated with the [5]

b = a[:]

print (a,b)

print (id(a), id(b))

output is 

[5] [5]

140658571474944 140658571472704

The [:] command makes a shallow copy of the array and in way slices everything. In this case we defined b=a[:] which gives you [5] as the output. However it is important to remember that we defined b to be a[:] because of this the 
a and b have different unique id's giveing them differnt numbers. 

Part D 

a = (5,)

b = tuple(a)

print (id(a), id(b))

the output of this is 140659399588016 140659399588016

The first line of the code makes a = (5,). The secound line of code makes b=tuple(a). The tuple command is used 
to store multiple items in a single variable so in this case it is (5,). The id command finds the id for (5,) which is 
140659399588016. Because we essintially made a=b this gives the same id. 

b = a[:]

print (id(a), id(b))

The output of this is 140658571556704 140658571556704. 

The fist line of code makes b=a[:]. This is differnt then what a is. Due to this a and b have different unique id's 
giving rise to two different numbers. 

4
1a = 2  # In a varaible the number cannot be in front 

a1 = b   

x = 2

y = X + 4 # is it 6? # X has to be lower case 

from Math import tan # the "Math" should be "math"

print tan(pi)  # needs to have an inside parentheses 

pi = "3.14159’ # needs to be the same kind of qoutation 

print (tan(pi)) 

c = 4**3**2**3

_ = ((c-78564)/c + 32)) #the parentheses is not consistent there is an extra one or you can add it to the other equation 

discount = 12% # the % is not valid in this case because of the 12 

AMOUNT = 120.- # This function has no end it is incomplete 

amount = 120$ # you cannot use dollar signs python 

address = hpl@simula.no # this is supposed to be a string so you need to add qoutations

and = duck # the and should be "And"

class = ’INF1100, gr 2" 

continue_ = x > 0

rev = fox = True

Persian = ['a human language']

true = fox is rev in Persian

5. not compatible with my computer 

6.  The answer to this is 248.862. When writing the code you have to define each variable before preforming the operation

Tw= 100

Ty= 70

T0= 4

T01= 20 

M= 47

c= float(3.7)

K= float(0.0055)

p= float(1.038)

import math

t= (M**(2/3)*c*p)/K(pi)**2 ln((0.76(T0-Tw)/(Ty-Tw))

7. A dictionary in python consistes of key value pairs. In this case I would pair the students and generate a loop of to repear student 16 times 
