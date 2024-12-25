1. Описание расширения
Название: remove-std

Описание:
Расширение remove-std для Visual Studio Code предназначено для автоматического удаления всех вхождений префикса std:: из кода на языке C++. Это упрощает код, делая его более чистым и читаемым, особенно для тех разработчиков, которые предпочитают не использовать пространство имен std.

2. Настройка расширения
По умолчанию, расширение настроено для удаления всех вхождений std:: с помощью комбинации клавиш Ctrl + Alt + R. Если вы хотите изменить эту комбинацию или добавить другие настройки, выполните следующие шаги:

Открытие настроек шорткатов:

Перейдите в меню File > Preferences > Keyboard Shortcuts (или используйте шорткат Ctrl + K Ctrl + S).
Поиск команды:

В строке поиска введите Remove std::.
Изменение шортката:

Найдите команду Remove std::.
Нажмите на иконку редактирования рядом с ней и введите новую комбинацию клавиш.
Нажмите Enter для сохранения изменений.
Добавление новых шорткатов (опционально):

Если необходимо, можно добавить дополнительные комбинации клавиш для одной команды.

3. Использование расширения
Удаление std:: во всем файле
Открытие файла:

Откройте C++ файл в VS Code, из которого вы хотите удалить std::.
Выполнение команды:

Нажмите комбинацию клавиш Ctrl + Alt + R.
Все вхождения std:: будут удалены из всего файла.
Удаление std:: в выделенной области
Выделение текста:

Выделите ту область кода, из которой вы хотите удалить std::.
Выполнение команды:

Нажмите комбинацию клавиш Ctrl + Alt + R.
Все вхождения std:: будут удалены только из выделенной области.

4. Горячие клавиши
По умолчанию:

Удаление std::: Ctrl + Alt + R
Настройка горячих клавиш:

Вы можете изменить или добавить новые комбинации клавиш для команды remove-std.removeStd через настройки шорткатов, как описано в разделе Настройка расширения.