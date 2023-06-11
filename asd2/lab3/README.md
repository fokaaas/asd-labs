# Лабораторна робота 3. Графічне представлення графів

Метою лабораторної роботи No3. «Графічне представлення графів» є
набуття практичних навичок представлення графів у комп’ютері та
ознайомлення з принципами роботи ОС.

Лабораторна робота розроблена для ОС **Windows**.

## Встановлення та компіляція
Ви повинні мати встановлений компілятор **GCC**. Для спочатку склонуйте репозиторій локально:

`git clone https://github.com/basarabst/asd2-lab3.git`

Перейдіть у папку склонованого репозиторію та, якщо ви маєте **Bush GNU**, виконайте скрипти:

`bash compile.sh`

`bash compile-output.sh`

А якщо ж ні, то скомпілюйте безпосередньо:

`gcc src/app.c src/utils/coords.c  src/utils/matrix.c src/drawing/graphs.c src/drawing/edges.c -mwindows -o app.exe`

`gcc src/output.c src/utils/matrix.c -o output.exe`

>Зауваження: app.exe - вікно з графами, output.exe - консольний вивід матриць цих графів (варто запускати з консолі)

## Основні параметри

При виконанні лабораторної роботи були використанні основні параметри:

- Варіант: **2202**
- Коефіцієнт: **0.74**
- Кількість вершин: **10**
- Розташування вершин: **прямокутником**

## Матриці суміжності

### Орієнтованого графа
![directed graph matrix](https://i.imgur.com/VZIGnRC.png)

### Неорієнованого графа
![undirected graph matrix](https://i.imgur.com/2mcZNLA.png)

## Графічне представлення
Ви можете **переключатися** між графами за допомогою клавіш Shift та Ctrl.

### Орієнтований граф
![directed graph](https://i.imgur.com/nLNNCnS.png)

### Неорієнтований граф
![undirected matrix](https://i.imgur.com/rjzaMMS.png)