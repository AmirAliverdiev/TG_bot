# QUESTIONS
01) age = input()
if age == 14:
    print('Вам есть 14! Поздравляю!')
if age > 14:
    print("Добро пожаловать!")
if age < 14:
    print("Вам ещё рано!")
02)
password = input()
if password == "secret":
    print("Доступ разрешен!")
else:
    print("Неверный пароль!")
03)
a = input()
if a >= "A" and a <= "z":
    print("Это буква!")
elif a >= 0 and a <= 9:
    print("Это цифра!")
else:
    print("Это не цифра и не буква!")
04)
some = int(input())
if some > 1000:
    some1 = (some / 100) * 10
    print(some + some1)
elif some > 500:
    some1 = (some / 100) * 5
    print(some + some1)
else:
    print(some)
05)
some = 0
for i in range(5):
    a = int(input())
    some += a
print(some)
06)
some = int(input())
i = 1
fac = 1
while i <= some:
    fac = i * fac
    i += 1
print(fac)
   
   
