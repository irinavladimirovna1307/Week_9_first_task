# Week_9_first_task

Задание.

Представь: турист из Пскова прилетел в Москву и заказал автомобиль до хостела.

Ты в роли программы-навигатора.

1) Маршрут построен, время посчитано, но сохранить его некуда. Создай переменную time, чтобы программа смогла обновлять оставшееся в пути время, и турист был спокоен.
2) Проверь, может ли JavaScript достучаться до переменной по её имени. Заодно посмотрим, что лежит в коробке сейчас — там должно быть пусто. На следующей строке выведи значение переменной в консоль. При обращении через  console.log()  в скобках укажи имя переменной.
3) Поездка начинается, время в пути 34 минуты. Самое время сохранить это значение в переменную и вывести на экран. Сразу после создания переменной time присвой значение 34. «Консоль-лог» переместится на третью строчку кода и выведет значение переменной.
4) Вывод в консоль числа 34 ни о чём не говорит. Сделаем его более человечным и понятным. Соедини текст и значение переменной. Внутри скобок для console.log  напишите 'Старт поездки. Осталось минут: ' + time.Кавычки важны, не потеряй их.
5) Пока ты писала сообщение, турист из Пскова смотрел сторис, а такси ехало 15 минут. После уже написанного кода уменьши значение переменной time на 15.
6) Примени уже знакомый трюк. Воспользуйся конкатенацией (сложением) строк, чтобы вывести в консоль фразу 'Немного сторис в соцсетях. Осталось минут: 'и текущего значения переменной time. Пиши код ниже уже написанного, ведь браузер читает его сверху вниз.
7) Ещё 10 минут. Машина едет, турист читает новости. Уменьши значение переменной time на 10. В консоль выведи фразу 'Немного не новостей, но событий. Осталось минут: ' плюс обновленное значение time.
8) Тем временем машина доехала до пункта назначения. Присвой переменной time значение 0.
9) Не хватает сообщения о том, что поездка завершена: Вы приехали. Добро пожаловать в Москву. Выведи его в консоль в самом конце программы, не забыв заключить текст в кавычки.