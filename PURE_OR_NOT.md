Number = int(input())
Sum = 0
while(Number > 0):
    Reminder = Number % 10
    Sum = Sum + Reminder
    Number = Number //10
print(Sum)
if(Sum % 3)==0:
    print("Yes")
else:
    print("Not")
