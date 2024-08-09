# Катлог, папка и директория - синонимы
# Часть 1: Повторение предыдущего материала
### Справка
```
Для создания директорий в заданиях "не выходя из" можно использовать или абсолютные пути, например touch ~/inform_фамилия/lab2/storage/milk_products/file_name
Или отностиельные, например если текущее местоположение ~/inform_фамилия/lab2/storage/milk_products и нужно создать объект в household_chemicals, то команда выглядит так
touch ../../toys
[touch заменятеся mkdir, в случае создания директории]
```
1) Перейти в каталог inform_фамилия создать в нем каталог lab2
2) В lab2 содать директорию storage
3) В директории storage создать каталог foodstuff
4) В директории storage создать каталог household_chemicals
5) В директории storage создать каталог toys
6) Перейти в каталог foodstuff
7) Создать в foodstuff директории fruits, groceries, milk_products
8) Не выходя из foodstuff содать в storage/household_chemicals директории cosmetic, laundry_products, cleaning_products
9) Не выходя из foodstuff содать в storage/toys директории educational_toys, soft_toys
10) Перейти в каталог toys
11) В директории storage/foodstuff/fruits создать файл с именем apples
12) В директории storage/household_chemicals/cleaning_products создать файл с именем floor_products
13) В директории storage/household_chemicals/laundry_products создать файл с именем powders
14) Перейти в директорию storage/household_chemicals/cleaning_products
15) Не выходя из storage/household_chemicals/cleaning_products создать в storage/household_chemicals/cosmetic файл с именем lipsticks
16) Не выходя из storage/household_chemicals/cleaning_products создать в storage/toys/educational_toys файл с именем constructors
17) Не выходя из storage/household_chemicals/cleaning_products создать в storage/toys/soft_toys файл с именем all_products
18) Перейти в директорию storage/toys/soft_toys

# Часть 2: Обработка текста
1) Вывести на экран содержимое файла /proc/meminfo
2) Из файла /proc/meminfo получить информацию о HugePages
3) Получить id (3 поле в строке) пользователя www-data офильтровав содержимое файла /etc/passwd
4) Создать в директории inform_фамилия папку text_processing
5) В text_processing создать файл info.csv с таким содержимым
```
Name,Company,Price,Ganre,Multiplayer
Item1,Company1,60000$,Ganre1,Yes
Item2,Company2,70000$,Ganre2,Yes
Item3,Company3,90000$,Ganre1,Yes
Item4,Company4,90000$,Ganre1,Yes
Item5,Company5,110000$,Ganre1,Yes
Item6,Company6,410000$,Ganre2,Yes
```
6) Вывести стобец Price из файла info.csv
7) Найти все строки, в которых встречается слово Ganre2
8) Найти все строки, в которых встречается слово Ganre2 и вывести для них столбец Price
