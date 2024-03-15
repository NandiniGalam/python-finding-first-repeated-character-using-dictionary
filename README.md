# python-finding-first-repeated-character-using-dictionary
t=int(input())
for i in range(t):
  d={}
  s=input()
  for i in s:
    if i not in d:
      d[i]=1 
    else:
      d[i]=d[i]+ 1 
  for i in d:
    if d[i]>1:
      print(i)
      break
  else:
    print(".")


try:
  d={}
  n=int(input())
  for i in range(n):
    k,v=input().split()
    d[k]=v 
  while True:
    x=input()
    if x in d:
      print(f"{x}={d[x]}")
    else:
      print("not found")
except:
  pass
        
      
