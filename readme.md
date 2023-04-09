# Основы работы с системами контроля версий и GitHub

## Выделение текста
 Чтобы выделить текст курсивом необходимо 
обрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например, *вот 
так* или _вот так_

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездачками (**)или знаком нижнего подчеркивания (__). апример, **вот 
так** или __вот так___.

Альтернативные способы выделения текста 
жирным или курсивом нужны для нужны для того, чтобы мы могли совмещать оба этих варианта.

Например : _**текст** может быть выделен курсивом и при этом может быть **полужирным**_.

## Списки

## Работа с изображениями
Чтобы вставить изображение в текс,
достаточно написать следующее:
![Привет, это Кубанский казак](kazak.jpg)
## Сссылки
Markdown поддерживает два стиля оформления ссылок:

Гиперссылка, с немедленным указанием адреса (внутритекстовая);
Гиперссылка, подобная сноске.
Подразумевается, что помимо URL-адреса существует еще текст ссылки. Он заключается в квадратные скобки. Для создания внутритекстовой гиперссылки необходимо использовать круглые скобки сразу после закрывающей квадратной. Внутри них необходимо поместить URL-адрес. В них же возможно расположить название, заключенное в кавычки, которое будет отображаться при наведении, но этот пункт не является обязательным.

  [пример](http://example.com/ "Необязательная подсказка")
В результате на экран выводится следующее: пример При ссылке на локальную директорию возможно использование относительного пути (от текущей страницы, сайта и т.п.)

При создании сносной гиперссылки вместо целевого адреса используется вторая пара квадратных скобок, внутри которых помещается метка, идентификатор ссылки (id).

[пример][id]:
Также, можно использовать пробел, чтобы отделять 2 пары квадратных скобок:

[пример] [id]: 
В этом случае возможно определить идентификатор в любом месте документа:

[id]: http://example.com/ "Необязательная подсказка"
В результате на экран выводится следующее: [пример] [id] [id]: http://example.com/ "Необязательная подсказка" Иными словами, она состоит из следующих элементов:

Идентификатор ссылки, окружённый квадратными скобками (которым может предшествовать необязательный отступ от одного до трёх пробелов);
Двоеточие;
Один или несколько пробелов (или символов табуляции);
URL гиперссылки;
Необязательный заголовок (подсказка к изображению, которая всплывает при наведении на него) гиперссылки, заключённый либо в двойные или одиночные кавычки, либо в скобки.
Идентификаторы ссылок могут состоять из букв, цифр, пробелов и знаков пунктуации, однако они не чувствительны к регистру. То есть эти два варианта эквивалентны:

[текст ссылки][a]
[текст ссылки][A]
Markdown позволяет также использовать неявно выраженный идентификатор (сокращенный). В этом случае метка не приводится, вместо неё текст гиперссылки используется и в качестве её имени, а вторая пара квадратных скобок остаётся пустою. Например, чтобы сделать слово «Example» гиперссылкой, ведущей на сайт http://example.com/, достаточно написать:

[Example][]
и затем определить гиперссылку:

[Example]: http://example.com/
В результате на экран выводится следующее: [Example][] [Example]: http://example.com/
## Цитаты

## Заключение