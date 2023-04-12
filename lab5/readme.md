Задание 1

Написать обработку, которая создаёт документ “Реализация товаров” и помещает в него все остатки товаров по выбранному складу.

В форме обработки должно быть предусмотрено поле выбора склада, остатки по которому планируется реализовать и кнопка выполнения действия.
В документ должны подставляться: текущая дата в поле “Дата”, выбранный склад в соответствующее поле. В табличной части обязательно должны заполняться поля: Номенклатура, Характеристика, Количество.

Если в базе заведено только два вида номенклатуры — Товар и Услуга, — то заведите третий: “скоропортящийся товар”. В запросе используйте отбор: выбор только номенклатуры вида “Товар” либо “Скоропортящийся товар”. Реализуйте это через оператор “В” в запросе.

После выполнения запроса использовать метод Выгрузить() и работать с результатом как с таблицей значений.

Записанный документ должен проводиться

Создадим Склады и Реализацию Товаров

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/1.png)
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/2.png)

Сделаем обработку
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/3.png)
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/4.png)

Сделаем 2 склада и наполним их товаром

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/5.png)

Сформируем отчет по 2ум видам товара

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/6.png)
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/7.png)

Получим два проведенных отчета об остатках

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/8.png)
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/9.png)
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/10.png)

 
Задание 2

Добавить в обработку возможность подхватывать цены на каждый из реализуемых товаров из регистра “Цены номенклатуры” и заполнять ими поле “Цена реализации”. Также должна рассчитываться стоимость по каждой позиции и подставляться в поле “Стоимость”.

Так как в регистре хранятся разные виды цен, то на форме обработки должно располагаться поле выбора вида цены. Выбранный вид цены должен использоваться в запросе.

Также на форме обработки должно стоять поле “Провести документ” с типом данных булево. Если оно установлено в Истина, то создаваемый документ должен сразу проводится.

Добавим новые поля остаткам

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/11.png)

И новый фильтр

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/12.png)

Проверим регистр сведений

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/13.png)

Дополним модуль обработки подгрузкой цен в запросе, их обработкой фильтром, подсчет стоимости и проведение/не проведение

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/14.png)
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/15.png)

Посмотрим на цены товаров

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/16.png)

Сделаем не проведенный отчет по товарам первого скалада с оптовой ценой

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/17.png)
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/18.png)
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/19.png)

Сделаем проведенный отчет по скоропорту первого склада с розничной ценой

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/20.png)
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/21.png)
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab5/screenshots/22.png)
