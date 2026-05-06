# Ночная лампа гайвера v1.0

## Описание проекта
Модификация лампы гайвера для ночных фонарей.
- Упрощённая схема, без кнопки. Управление только через Wifi.
Основана на прошивке [FieryLedLamp v5.4 132 эффекта](https://community.alexgyver.ru/threads/wifi-lampa-budilnik-obsuzhdenie-proshivki-fieryledlamp-ot-mishanyats.7530/page-88)

## Сборка

- Для распайки компонентов хорошо подошла макетная плата 30x70. Режем пополам, оставляя по 11 отверстий с каждой стороны.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img03.jpg)
- Компоненты паяются по схеме, исключая сенсор и дисплей. Транзистор заменил на D472 с платы BMS 40A(видна на фоне). Такая плата стоит 170р примерно, там 10 штук.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/schemes/Lamp(ESP8266).png)
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img04.jpg)
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img05.jpg)
- Печатаем две половинки корпуса из папки 3D print. Печатать лучше круглой частью к столу, так меньше поддержек и печатается быстрее. Но принтеры разные, так что на своё усмотрение.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img01.jpg)
- Загоняем гайки в паз, закручивая болтик без второй половики.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img02.jpg)
- Цоколь используем от сгоревшей лампочки, предварительно отрезав болгаркой примерно 5мм от металлической части. Если нет лампочки, можно использовать переходник e27 e14, но если покупать он стоит также как самая дешёвая лампочка.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img06.jpg)
- Модуль питания используем такой 5В 2А. На алиэкспресс стоит 130р
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img07.jpg)
- Собираем компоненты в корпусе.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img08.jpg)
- Матрицу используем 8x32. Режем пополам по 16 столбиков светодиодов с каждой стороны.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img09.jpg)
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img10.jpg)
- Отпаиваем провод, отрезаем 3 см, запаиваем обратно.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img11.jpg)
- Опционально нарезаем алюминиевую банку на лист 15,8 на 9 см. Для отвода тепла.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img12.jpg)
- Вырезаем примерно 2 на 2 см, чтобы не замкнуло, и приклеиваем к матрице двумя капельками горячего клея.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img13.jpg)
- Соединяем матрицу. Цоколь сажаем на клей.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img14.jpg)
- Заворачиваем всё и крепим стяжками. Между листом алюминия и пластиком тоже нужна капля клея, для того чтобы алюминий не проскальзывал, когда заворачиваем лампочку в цоколь. (Горячий клей не стоит капать на алюминий, так как он очень быстро остывает)
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img15.jpg)
- Лампа готова, осталось поставить Wemos.

## Примечания
Вторую часть матрицы в штатных местах запаиваем только 5в и GND. Третий провод оставляем сверху, чтобы запаять как на картинке.
![SCHEME](https://github.com/Rustem666666/GyverNightLamp/blob/main/images/img16.jpg)

## Прошивка


## Полезная информация
* [Сайт AlexGyver](http://alexgyver.ru/)
* [Основной YouTube канал AlexGyver](https://www.youtube.com/channel/UCgtAOyEQdAyjvm9ATCi_Aig?sub_confirmation=1)
* [YouTube канал про Arduino от AlexGyver](https://www.youtube.com/channel/UC4axiS76D784-ofoTdo5zOA?sub_confirmation=1)
* [Видеоуроки по пайке](https://www.youtube.com/playlist?list=PLOT_HeyBraBuMIwfSYu7kCKXxQGsUKcqR)
* [Видеоуроки по Arduino](http://alexgyver.ru/arduino_lessons/)
* [Оригинальная лампа Гайвера](https://alexgyver.ru/gyverlamp)