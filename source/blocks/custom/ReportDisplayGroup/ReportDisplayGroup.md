# ReportDisplayGroup

Показ блока информации (общего или для конкретного объекта).

Содержит опциональные элементы: `Stat` и `Table`.

Принимает данные в параметре `data` (`ctx.data`):

- `rows`: Строки таблицы (см. mod:`showTable`).
- `columns`: Столбцы таблицы (см. mod:`showTable`).
- `stat`: Контент для блока статистики (см. mod:`showStat`).
- `title`: Заголовок блока (см. mod:`showTitle`). Может передаваться в контексте самого блока.

Возможные состояния:

- `showTitle`: Показывать ли блок заголовка (с собственно заголовком и элементом раскрытия информации, см. mod:`expandable`).
- `showStat`: Показывать ли статистику.
- `showTable`: Показывать ли таблицу.
- `tableFirst`: Показывать таблицу первой (иначе сначала следует статистика).
- `expandable`: Явялется ли блок раскрываемым.
- `expanded`: Скрыт или открыт блок детальной информации.

