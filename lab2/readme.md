1. Подсистемы
    
    a. Создайте подсистемы: “НСИ и Администрирование”, “Отчеты” и еще 2 на ваше усмотрение, например “Расписание”, или “Закупка”, или “Продажа”, или “Склады” исходя из темы ЛР
    
    b. Добавьте картинки к подсистемам
    
    c. Расположите подсистемы по алфавиту
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/1.png)
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/2.png)
    
    d. Создайте минимум 2 подчиненных подсистемы, например “Справочники”, “Администрирование, подчиненные “НСИ и Администрирование”
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/24.png)
    
    e. В режиме конфигуратора скройте видимость подсистемы “Отчеты”, проверьте, что данная подсистема уже не появляются при старте
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/25.png)


2. Справочники

    a. Созданные в ЛР №1 справочники необходимо добавить в подсистемы.
    
    b. В каждый справочник нужно добавить 2-3 реквизита с разными типами (пример в теме №1 к ЛР)
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/4.png)
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/5.png)
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/6.png)
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/7.png)
    
    c. Минимум один из справочников нужно сделать иерархическим
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/8.png)
    
    d. Создайте в иерархическом справочнике предопределенные группы и элементы
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/9.png)
    
    e. Минимум в одном из справочников необходимо создать табличную часть с реквизитами
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/10.png)
    
    f. Несколько справочников нужно связать между собой через объект-ссылку. Тип реквизита должен быть СправочникСсылка (пример в теме №1 к ЛР)
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/11.png)
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/12.png)
    
    g. Необходимо создать форму списка и форму элемента для каждого справочника
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/13.png)
    
    h. Для иерархического справочника необходимо изменить форму элемента, сгруппировать реквизиты, добавить закладки
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/14.png)
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/15.png)
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/16.png)
    
    ![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/17.png)


3. Необходимо создать внешнюю обработку для автоматического заполнения иерархического справочника. Используйте генератор случайных чисел
    
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/18.png)
    
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/19.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/20.png)


4. Добавьте в обработке кнопку “УдалитьЭлементы”, а в ее обработчике напишите программный код, удаляющий сгенерированные прежде элементы из всех групп иерархического справочника. Для этого потребуется использовать методы НайтиПоНаименованию, ПолучитьОбъект, Удалить.
    
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/21.png)
    
![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/22.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab2/screenshots/23.png)
