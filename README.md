ID_assistant = 'Lida'
print('Привет меня зовут', ID_assistant)
name = input('Введите ваше имя: ')
print('Приятно познакомиться,', name)
age_user = input('Сколько вам лет:')
print('Представь, через 10 лет тебе будет:',  int(age_user) + 10)
rise = float(input('Какой у тебя рост? Мой 0.52м:'))
print('Ого ты выше меня на :', rise - 0.52)
print('Мне очень приятно с тобой познакомиться:', name, age_user, 'лет!', 'С ростом:', rise)
answer = input('''Выбирите дейстие:
1-спеть песню 
2-рассказать анекдот
3-рассказать стих
''')
if answer == '1':
  print('''Baby, I'm leaving, I'm not taking anything but you
Picture us escaping
In the background of the photo I see you
I remember the time, I remember hearts sewn together with twine
Just remember that I am still right here
And if you doubt me, that's just fine
And when it comes clear, I will be waiting right here
Just tell me if you need me and I will meet you right there''')
elif answer == 2 :
  print('''— Семочка, сколько будет 2 умножить на 2?
— Четыре.
— Правильно! На тебе четыре конфеты.
— Если бы знал, сказал — пятнадцать.''')
else:
  print('''Капли падают - кап, кап -
С крыш, с деревьев и со шляп,
С капюшонов и зонтов,
С наших курток и пальто...
Сколько капель!
Сколько луж!
Будто город принял душ!''')
