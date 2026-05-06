# Ночная лампа гайвера v1.0

## Описание проекта
Модификация лампы гайвера для ночных фонарей.
- Упрощённая схема, без кнопки. Управление только через Wifi.
Основана на прошивке [FieryLedLamp v5.4 132 эффекта](https://community.alexgyver.ru/threads/wifi-lampa-budilnik-obsuzhdenie-proshivki-fieryledlamp-ot-mishanyats.7530/page-88)

## Сборка

### Подготовка схемы

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



## Примечания
Если

## Полезная информация
* [Сайт AlexGyver](http://alexgyver.ru/)
* [Основной YouTube канал AlexGyver](https://www.youtube.com/channel/UCgtAOyEQdAyjvm9ATCi_Aig?sub_confirmation=1)
* [YouTube канал про Arduino от AlexGyver](https://www.youtube.com/channel/UC4axiS76D784-ofoTdo5zOA?sub_confirmation=1)
* [Видеоуроки по пайке](https://www.youtube.com/playlist?list=PLOT_HeyBraBuMIwfSYu7kCKXxQGsUKcqR)
* [Видеоуроки по Arduino](http://alexgyver.ru/arduino_lessons/)
* [Оригинальная лампа Гайвера](https://alexgyver.ru/gyverlamp)