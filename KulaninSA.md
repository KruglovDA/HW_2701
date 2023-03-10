Инструкция
# Инструкция по работе с Git
## Команды:
* git init - создает локальный репозиторий;
* git add file_name - добавляет файлу версионность в локальном репозитории;
* git commit -m "*комментарий*" - фиксирует изменения и информирует об основных изменениях в новой версии файла;
* git diff - показывает разницу между текущей и уже зафиксированной версией файла;
* git log - выводит список всех сохранений в хронологическом порядке;
* git checkout *hash* - позволяет перемещаться между сохранениями;
* git status - показывает состояние файла в рабочем журнале.

**Работа с ветками:**
* git branch - выводит на экран список веток в репозитории;
* git branch *название ветки* - создает новую ветку в репозитории;
* git checkout *название ветки* - переход на другую ветку в репозитории;
* git merge *название ветки* - слияние веток в репозитории (куда нужно залить данные, отткуда вызываем команды);
* git branch -d *название ветки* - удаление ветки в репозитории;
* git log --graph - открывает журнал коммитов с визуализацией между ними.

**Работа с удаленным репозиторием:**
* git clone *адрес* - копирует репозиторий из github в локальный репозиторий;
* git push - направляет в удаленный репозиторий все изменения, которые были сделаны в локальном репозитории;
* git pull - стягивает с удаленного репозитория все изменения в локальный репозиторий;
* pull request - запрос на вливание изменений в репозиторий;
* fork -  создание точной копии чужого репозитория на своем аккаунте github.
### **Дополнительные команды**:
*Использовать один раз при первом входе в программу:*
1. git config --global user.name "*имя Пользователя*";
2. git config --global user.email "*e-mail Пользователя*".
 * Для очистки терминала можно использовать команду *clear*;
 * Чтобы git пропускал какие-то файлы и не сохранял в репозиторий, можно создать новый файл *название файла*.gitignore. Внутри файла прописать то, что необходимо игнорировать.