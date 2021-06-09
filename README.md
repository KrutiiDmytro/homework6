# homework6
txt = 'когда нибудь я сдам домашку на сто баллов'
x = txt.capitalize()
print(x)

txt = 'Когда Нибудь я Сдам домашку на СТО баллов!'
x = txt.casefold()
print(x)

txt = 'когда нибудь я сдам домашку на сто баллов!'
x = txt.center(45)
print(x)

txt = 'когда нибудь я сдам домашку на сто баллов!'
x = txt.count('а', 3, 30)
print(x)

txt = 'My nåme is Dimå'
x = (txt.encode(encoding="ascii", errors='ignore'))
print(x)

txt = 'когда нибудь я сдам домашку на сто баллов!'
x = txt.endswith('сто баллов', 6, 29)
print(x)

txt = 'когда\tнибудь\tя\tсдам\tдомашку\tна\tсто\tбаллов!'
x = txt.expandtabs(4)
print(x)

txt = 'когда нибудь я сдам домашку на сто баллов!'
x = txt.find('д', 4, 11)
print(x)
print(txt.find("ж"))

txt = 'Даю {price:.2f} и вы ставите сто баллов моей домашке'
print(txt.format(price=49))

txt1 = 'Меня зовут {fname},и у меня {size}см'.format(fname='Учитель', size=30)
txt2 = '{0}, {1}'.format('Учитель', 30)
txt3 = '{},{}'.format('Учитель', 30)

print(txt1)
print(txt2)
print(txt3)

txt = 'когда нибудь я сдам домашку на сто баллов!'
x = txt.index('д', 5, 14)
print(x)

txt = 'Hillel100'
x = txt
print(txt1.isalnum())

txt = 'КогдаНибудьЯсдамДомашкуНаСтоБаллов'
x = txt.isalpha()
print(x)

txt = '\u0033'
x = txt.isdecimal()
print(x)

txt = '666'
x = txt.isdigit()
print(x)

txt = 'a_8z'
x = txt.isidentifier()

a = 'когда нибудь я сдам домашку на сто баллов!'
b = 'Когда нибудь я сдам домашку на сто баллов!'
c = 'когда нибудь я сдам домашку на 100 баллов!'

print(a.islower())
print(b.islower())
print(c.islower())

a = '\u0030'
b = '\u00B2'
c = '666km2'
d = '-1'
e = '1.5'

print(a.isnumeric())
print(b.isnumeric())
print(c.isnumeric())
print(d.isnumeric())
print(e.isnumeric())

txt1 = 'Здесь есть\nнепечатный символ #1?'
txt2 = 'А здесь нет #1?'

print(txt1.isprintable())
print(txt2.isprintable())

txt = 'Когда Нибудь Я Сдам Домашку На 100 Баллов!'
x = txt.istitle()
print(x)

txt = 'ВСЁ ЗАГЛАВНЫМИ БУКВАМИ'
x = txt.isupper()
print(x)

myTuple = ('Гитлер', 'Сталин', 'Янукович', '.')
x = 'Лох'.join(myTuple)
print(x)

txt = 'Ура'
x = txt.ljust(20, 'а')
print(x, 'зарплата пришла!)')

txt = 'Привет ВСЕМ)'
x = txt.lower()
print(x)

txt = 'давайте'
x = txt.lstrip()
print('Друзья,', x, 'жить дружно!')

txt = 'Я буквы путаю'
x = 'бт'
y = 'пк'
mytable = txt.maketrans(x, y)
print(txt.translate(mytable))

txt = 'Разбивает строку на три части'
x = txt.partition('на три')
print(x)

txt = 'Камень, Ножницы, Бумага'
x = txt.rsplit(', ')
print(x)

txt = 'Когда Нибудь Я Сдам Домашку На 100 Баллов!'
x = txt.rstrip('На 100 Баллов!')
print(x)

txt = 'Камень#Ножницы#Бумага#Ящерица#Спок'
x = txt.split('#', 2)
print(x)

txt = 'Разделяет строку\n на элементы списка'
x = txt.splitlines()
print(x)

txt = 'Когда Нибудь Я Сдам Домашку На 100 Баллов!'
x = txt.startswith('б', 8, 15)
print(x)

txt = 'удалитьскоро конец)удалить'
x = txt.strip('илтаьдуа')
print(x)

txt = 'прописные СТРОЧНЫЕ'
x = txt.swapcase()
print(x)

txt = 'первая буква в каждом слове в верхнем регистре'
x = txt.title()
print(x)

txt = 'Заменить любые символы'
x = 'Заи'
y = 'Поя'
mytable = txt.maketrans(x, y)
print(txt.translate(mytable))

txt = 'Всё в верхнем регистре'
x = txt.upper()
print(x)

a = '666'
b = 'больше десяти символов'
c = 'HI'

print(a.zfill(10))
print(b.zfill(10))
print(c.zfill(10))
