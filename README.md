# ____TASK_____1______
string=input("Enter a string to check Palendrom")
string2=""
stack=[]
for i in string:
 stack.append(i)
while len(stack)!=0:
 string2=string2+stack.pop()
if(string2==string):
 print("The entered string is Palendrom")
else:
 print("The entered string is not a Palendrom")
