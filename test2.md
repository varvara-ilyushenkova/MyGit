# MyGit
x = int(input())
y = int(input())
if (z >999 and x < 10000) and (y > 999 and y < 10000) and x<y:
 for i in range(x, y + 1):
  a = i // 1000
  b = (i // 100) % 10
  c = (((i // 10 )% 100) %10)
  d = (((i % 1000) % 100) % 10)
  if (a == d) and (b == c):
   print(i)
 else:
 print ("введите числа в порядке возрастания")
