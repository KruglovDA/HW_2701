# Руководство по Git
## Локальный репозиторий
### Команды:

#### *1. Знакомство с **GIT**:*
1. *config --global user.name "**Name**"* - имя
2. *config --global user.email "**mail**"* - почта

#### *2. Начало работы с документом:*
* *init* - создание локального репозитория
* *add* - добавление файла
* *status* - состояние репозиторов
* **clear** - чистка терминала

#### *3. Сохранение файла:*
* Ctrl + S - сохранение
* *add **file*** - добавление файла (включаем в отслеживание)
* *commit -m"**comments**"* - комментируем изменения
   >Сокращение команд ~~[*add **file***, * *commit -m"**comments**"*]~~ *
  >>*commit -am"**comments**"*

#### *4. Отслеживание изменений:*
* *log* - информация об изменениях
* *checkout **4 символа комментария*** - вернуться к сохранению
* *checkout master* - вернуться к рабочей версии
* *diff* - разница между сохраненной и текущей
___
Полезная информация на сайте [***Git Hub***](https://docs.github.com/ru/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
___

#### *5. Отслеживание веток:*
* *branch* - информация о ветках
* *branch **name branch*** - создать ветку
* *branch -d **name branch*** - удалить ветку
* *checkout **name branch*** - перейти на ветку
* *merge **name branch*** - слияние ветки
* *log --graph* - полная информация об изменениях
  > Сокращение команд ~~[*branch __name branch__*, *checkout __name branch__*]~~
  >> *checkout -b __name branch__*

#### *6. Перемещение веток*
* *branch -f __name branch__ HEAD~2* - перенести ветку на 2 вверх.
* *checkout HEAD~2* - переместиться на 2 ветки вверх.
* *cherry-pick __name name2__* - добавление веток в активную

___
Приложение для достижения мощных возможностей ветвления и работы с git
[__*LearnGitBranching*__](https://learngitbranching.js.org/?locale=ru_RU)
___

#### *7. Работа с удаленным репозиторием*
1. Переходим по ссылке __*https://github.com/*__
2. Находим нужный репозиторий.
3. Жмем на кнопку **Fork** - *(в списке наших репозиториев появился fork)*
4. Клонируем ссылку к себе в VS
5. Открываем папку в VS 
6. Выполняем *git branch* 
7. Выполняем *git checkout*
8. Добавляем свой файл с названием
9. Выполняем *add* and *commit*
10. Выполняем *git push* - *(если git ругается, выполняем команду из подсказки)*
11. На github выполняем **pull request**

#### *8. Как исправить HEAD detached*
1. *branch temp* 
2. *checkout temp* 
3. *branch -f master temp* 
4. *checkout master* 
___
___
![HEAD detached](head_detached.jpg)
___
___

##### __Добавление картинок:__
1. Сайт:

![Git](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3sbvB3nTktjiedy1RJyxYlpXfxSDUIi6jyg&usqp=CAU)

2. Файл:

![image](images.jpg)
____
##### __Добавление таблиц:__

#### Таблица

| Rank | THING-TO-RANK |
|-----:|---------------|
|     1|               |
|     2|               |
|     3|               |

___

#**Git** <sub>*полезные ссылки и материалы**</sub>

* [Настройка репозитория](https://www.atlassian.com/ru/git/tutorials/setting-up-a-repository)
* [Сохранение изменений](https://www.atlassian.com/ru/git/tutorials/saving-changes)
* [Проверка репозитория](https://www.atlassian.com/ru/git/tutorials/inspecting-a-repository)
* [Отмена изменений](https://www.atlassian.com/ru/git/tutorials/undoing-changes)