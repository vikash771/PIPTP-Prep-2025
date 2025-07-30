Question: what will be the output of following pseudo code for w=40 and x=4?
void fun( integer w, integer x)
Integer y
Set y=0
if(x mod w EQUALS 0 | | w mod x EQUALS 0)
y = y + 1
Else
y = y + 10
End if
Print y
End function fun()

Solution:
[ ]
def fun (w,x) :
y=0
if ((x%w==0) or (w%x)==0):
y=y+1
else:
y=y+10
print (y)
print (fun (40,4))
