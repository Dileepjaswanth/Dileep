a=int(input())
reverse=0
while(a>0):
  reminder=a%10
  reverse=(reverse*10)+reminder
  a=a//10
print(reverse)
