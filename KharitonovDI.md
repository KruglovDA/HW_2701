# Руководство по GIT
## Локальный репозиторий
### Команды
* init - создание локального репозитория
* add - добавление файлов
* status - состояния репозитория
## Ссылки
* [Ссылка](https://www.google.com)
* [С указанием ссылки в сноске][Arbitrary case-insensitive reference text]
* [Можно использовать цифры в качестве сносок][1]
* Ссылка, обрамлённая в угловые скобки, автоматом преобразуется
<https://www.google.com>
### Сноски
Какой-то текст перед сносками

[arbitrary case-insensitive reference text]: https://www.mozilla.org

[1]: http://slashdot.org

## Изображения
Задание ссылки на изображения сразу: 
![alt text](https://img.iamcook.ru/old/upl/recipes/cat/u6009-6f7bc626987a569ea82abc781c2c1205.jpg "Logo Title Text 1")
Указание ссылки на изображение в сноске: 
![alt text][logo]

[logo]: https://img.iamcook.ru/2022/upl/recipes/cat/u-0055aa1fb8da4adafee90111fede57ed.jpg "Logo Title Text 2"

## Подсветка кода и выделение элементов

С попмощью апострофов `текст` будет `обрамлён`
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
``````
## Таблицы

Обязательно требуют заголовок и настройки выравнивания (второй строкой). Выравнивание задаётся двоеточием. Колонки задаются вертикальным палками (|)

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Внешние вертикальные палки (|) задавать необзяательно, также не требуется подгонять колонки под один размер. Можно использовать стили, описанные выше.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

## Цитаты
> Цитаты задаются угловой скобкой.
> Это строка является частью цитаты.

Здесь цитата прерывается.

> Можно писать много-много текста, и он автоматически всё преобразует в одну цитату. Также можно использовать разилчные *начертания* в **цитате**. Красота!

## HTML
В любой момент можно вставить кусок html и не париться.

<div>
  <p>Тег. Внутри тега markdown **игнорируется**.</p>
</div>

## Линия
Три или больше символов задают линию

---

Дефисы

***

Звёздочки

___

Подчеркивания