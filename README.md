# Avg-of-given-numbers
#avg  of odd and even in a list
# approach-1
n=int(input())
a=list(map(int,input().split()))
r=0
k=0
for i in range(n):
  if a[i]%2==0 and a[i]>r:
    r=r+a[i]
    k=k+1
print(r//k)


#approach-2
n=int(input())
a=list(map(int,input().split()))
r=0
k=0
for i in a:
  if i%2==0 and i>r:
    r=r+i
    k=k+1
print(r//k)

#approach-3
n=int(input())
a=list(map(int,input().split()))
r=[]
for i in range(n):
  if a[i]%2==0 :
    r.append(a[i])
print(sum(r)//len(r))


#approach-4
n=int(input())
a=list(map(int,input().split()))
r=[]
for i in a:
  if i%2==0:
    r.append(i)
print(sum(r)//len(r))

