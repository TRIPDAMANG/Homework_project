# Инструкция для работыс Git и удаленными репозиториями

## Что такое Git?
Git - это одна из реализаций распределенных систем контроля версий, имеющая как и локальные, так и удаленные репозитории. Является самой популярной реализацией систе контроя версий в мире.
## Подготовка репозитория.
для создания репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления изменений в коммит используется команда *git add<имя файла>*

### Просмотр состояния репозитория
для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиториями написать *git status*, и Вы увидите были ли изменения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит (сохранение) необходимо выполнить команду *git commit*. Выполняется она так: git commit -m "название сохранения"

### Проверка состояния рабочего файла
Для проверки состояния файла используется Команда *git status*, она отображает состояние рабочего каталога и раздела проиндексированных файлов.

```sh
Важно! при работе с файлом в системе VScode не забывайте использоваьт комбинацию ctrl+S для сохрания текущих изменений на жесктий диск.
```
при создании данного файла использовался язык разметки Markdown, чтобы полноценно отобразился формат текущего файла используйте следующую ссылку, и внутри вставьте текущий файл:

[ссылка для отображения файла .md](https://products.aspose.app/words/ru/viewer/markdown
)