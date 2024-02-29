# duplicate-numbers in python
#print the duplicate numbers
#approach-1
n=int(input())
a=list(map(int,input().split()))
for i in range(n-1):
  if a[i] in a[i+1:]:
    print(a[i])
    break
