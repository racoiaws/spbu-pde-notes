## Структура проекта
**main.tex** - основной файл, содержит в себе список используемых пакетов, команды, определенные пользователями, стили теорем и прочую информацию. Также, в нем перечислены остальные файлы проекта `(\input{})`.

**partN.tex** - тексты лекций. Номер файла соответствует номеру лекции.

## Организация работы
Предполагается, что каждый участник пишет свою лекцию в отдельном файле partN.tex и не редактирует файлы остальных участников. Работать над проектом можно в онлайн-редакторе Papeeria (там есть интеграция с git) или локально.

### Papeeria
Проект живет [здесь](http://papeeria.com/p/a24ec28891b1f56b22d7aa61257d165e). Чтобы пушить изменения из Papeeria, необходимо добавить себе в [настройки](https://github.com/settings/ssh) SSH ключ, который вам даст Papeeria (Version control with Git -> Sync Now -> SSH). Отправляйте изменения в ветку `papeeria` (проект уже настроен на нее). Papeeria добавляет в коммит все измененные файлы, то есть, если несколько человек одновременно работают над проектом и один из них выполняет `push`, в репозиторий отправятся все изменения. Ну и пусть `¯\_(ツ)_/¯`

### Offline
Если вам не нравится Papeeria и/или хочется работать локально, то в качестве комилятора рекомендуется использовать **XeLaTeX**. Для локальной работы используйте ветку `dev`. 

Так как некоторые десктопные редакторы не очень хорошо распознают кодировку, просьба добавлять в начало новых файлов строку `% !TEX encoding = UTF-8 Unicode`

## Как присоединиться
* Чтобы получить доступ к репозиторию, отправьте свой github-логин [Коту](http://vk.com/id26175742). Если вы планируете использовать  Papeeria, необходимо также добавить почту, на которую зарегистрирован ваш аккаунт.
* Выберите свободную [лекцию](https://github.com/racoiaws/spbu-pde-notes/issues).
* Добавьте себя в `assignee` в соответствующем issue.
* Создайте файл для своей лекции и добавьте его в main.tex c помощью `\input{}`
