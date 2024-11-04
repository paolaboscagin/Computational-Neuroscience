```
For reference only:

>> A=[1;2;3]

A =

     1
     2
     3

>> B=[-1;-2;-3]

B =

    -1
    -2
    -3


>> C=A.*B

C =

    -1
    -4
    -9

>> C=A*B
Error using  * 
Inner matrix dimensions must agree.
 
>> C=A'*B

C =

   -14
