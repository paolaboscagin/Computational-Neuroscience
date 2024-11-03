```
For reference only:

>> A = [1, 2; 3, 4]

A =

     1     2
     3     4

>> B = [2, 2; 3, 3; 4, 4]

B =

     2     2
     3     3
     4     4

>> C = eye(3)

C =

     1     0     0
     0     1     0
     0     0     1

>> d = [ 1 2 3]

d =

     1     2     3

>> E = zeros(3,3)

E =

     0     0     0
     0     0     0
     0     0     0

>> C.*E

ans =

     0     0     0
     0     0     0
     0     0     0

>> A - B
Arrays have incompatible sizes for this operation.

Related documentation
 
>> A * B
Error using  * 
Incorrect dimensions for matrix multiplication. Check that the number of columns in the first matrix matches the number of rows
in the second matrix. To operate on each element of the matrix individually, use TIMES (.*) for elementwise multiplication.

Related documentation
 
>> C*E

ans =

     0     0     0
     0     0     0
     0     0     0
 
>> A*B'

ans =

     6     9    12
    14    21    28

>> d*B

ans =

    20    20
```
