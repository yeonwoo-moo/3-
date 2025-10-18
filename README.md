과제#11(1)
a = input().split()
a = list(map(int, a ))
print(a)

과제#11(2)
a = input().split()
a = list(map(int, a ))
a.append(a)
print(a)

과제 #12
a = list(input().split())
del a[-2:]
print(a)

과제 #13
a = input().split()
for index, value in enumerate(a):
  print()

  과제 #14
a = [10, 20, 30, 40, 30, 20, 10]
result = a.count(20)

print(result)

과제 #15
a = list(map(int, input().split()))
min_value = min(a)
max_value = max(a)

print(min_value, " and " , max_value)

과제 #16
a = list(map(int, input().split()))
min_value = min(numbers)
max_value = max(numbers)

print(a)

과제 #17
a = [10, 20, 30, 40, 30, 20, 10]
while 20 in a:
    a.remove(20)
print(a)

과제 #18
a = [i for i in range(1, 6)]
print(a)

과제 #19
a = [i for i in range(1, 21) if i % 2 == 1]
print(a)

과제 #20
start, end = map(int, input().split())
a = [2 ** i for i in range(start, end + 1)]
if len(a) >= 2:
    del a[1] 
    del a[-2]   
print(a) 

과제 #21
sting_var = ('Hello, world!')
print(sting_var.replace('Hello', 'Hi'))
print(sting_var)

과제 #22
sting_var = input("4개의 문자를 입력받으시오: ")
sting_var = " / ".join(sting_var)
print(sting_var)

과제 #23
name = input("성을 영어로 입력하시오: ")
name = name.lower()
print(name.rjust(10))

과제 #24
prices = input().split(';')
prices = list(map(int, prices))
prices.sort(reverse=True)
for price in prices:
    print(f"{price:>9}")
