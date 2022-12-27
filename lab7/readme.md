Задание 1. “Выгрузка JSON”


Создать обработку, на форме которой будет указываться папка для выгружаемого JSONa и кнопка запуска выгрузки. 

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/1.png)

Необходимо запросом получить документы прихода за текущий месяц, сформировать JSON и выгрузить его в файл
В структуру JSONa необходимо записать дату документа, номер документа, все реквизиты из шапки (как строки) и список товаров/услуг из табличной части(Только наименования)
Выгрузку сделать через потоковую запись

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/2.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/3.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/4.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/5.png)


Задание 2. “Загрузка”
Добавить в обработку кнопку загрузки и поле для выбора файла json

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/6.png)

Необходимо при помощи сериализации простых типов и коллекций значений прочитать ранее выгруженный файл JSON и создать документы прихода:
Номера документов должны быть присвоен автоматически при создании
Даты документов должны быть равна текущей дате-времени.

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/7.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/8.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/9.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/10.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/11.png)


Задание 3. 
Установить Apache
Разработать HTTP-сервис, который получает методом GET информацию о всех товарах/слугах и о конкретном товаре по коду
Опубликовать базу 
Проверить работу HTTP-сервиса из браузера. (Перед проверкой, вероятно потребуется закрыть 1С, т.к. учебная платформа поддерживает только одно подключение)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/12.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/13.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/14.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/15.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/16.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/17.png)

![Image alt](https://github.com/AhEhIOhYou/1c/blob/main/lab7/screenshots/18.png)
