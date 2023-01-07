# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
***Git*** - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
  - Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создатся репозиторий (появится скрытая папка .git)

## Создание коммитов

- ### Git add
   - Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*
Для того, чтобы прекратить отслеживание файла, используется команда *git rm --cached*. Чтобя использовать команду, напишите *git rm --cached <имя файла>*.

- ### Просмотр состояния репозитория
   - Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

   - При необходимости изменения нужно сохранить нажатием сочетания клавиш **Ctrl+S** (при отсутствии автосохранения) и "закоммитить".

- ### Создание коммитов
   - Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>"*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

- ### Отмена коммита
   - Для отмены коммита можно воспользоваться командой *git reset --hard*.

- ### Дифференцировка
   - Для того, чтобы увидеть разницу между сохраненным, но еще не закоммиченным файлом, и тем, который был до редакции, необходимо воспользоваться командой *git diff*.

## Перемещение между сохранениями
- Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений

- Вывод **полного** журнала

   - Для того, чтобы посмотреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

- Вывод **сокращенного** варианта журнала

   - Для вывода данных в сокращенном варианте можно использовать команду *git log --oneline*. 

## Ветки в Git

- ### Создание ветки

   - Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

- ### Слияние веток

   - Для того чтобы дoбавить ветку в текущую ветку используется команда *git merge <название ветки>*

- ### Переход на другую ветку
   - Для того, чтобы перейти на другую ветку, необходимо ввести команду *git checkout <название ветки>*

- ### Удаление веток
   - Для удаления ветки ввести команду *git branch -d 'name branch'*


## Картинка

   - Для того, чтобы вставить картинку необходимо прописать определенную команду. 
   В строке прописывается восклицательный знак, квадратные и круглые скобки. В квадратных скобках указывается *текст с описанием картинки*, который виден при проблемах с "подгрузкой" самой картинки, а в круглых скобках указывается __либо__ *имя файла* (если катинка грузится с локального компьютера), __либо__ *ссылка на картинку*.

   ![Пустыня](lestn.jpg)

   ![Дождь](https://vsegda-pomnim.com/uploads/posts/2022-02/1645989638_51-vsegda-pomnim-com-p-letnii-dozhd-foto-57.jpg)




-------
> В теории, теория и практика неразделимы. На практике это не так.

-----

[Консультант Markdown](https://learn.microsoft.com/ru-ru/contribute/markdown-reference)

