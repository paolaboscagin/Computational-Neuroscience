```
For reference only:

>> A=[5,-2,3;2,-3,4;3,4,-8]

A =

     5    -2     3
     2    -3     4
     3     4    -8

>> A<0=0
 A<0=0
    |
Error: The expression to the left of the equals sign is not a valid target for an assignment.
 
>> (A<0)=0
 (A<0)=0
      |
Error: The expression to the left of the equals sign is not a valid target for an assignment.
 
>> A(A<0)=0

A =

     5     0     3
     2     0     4
     3     4     0

>> A(:)=0

A =

     0     0     0
     0     0     0
     0     0     0

```
