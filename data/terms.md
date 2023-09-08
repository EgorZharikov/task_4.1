[Вернуться к содержанию](./../readme.md)

## Основные понятия:
- **GIT** - это распределенная система контроля версий нашего кода. Зачем она нам? Для распределенных команд нужна какая-то система управления работы. Нужна, чтобы отслеживать изменения, которые происходят со временем.
- **Состояния в GIT** 
    - неотслеживаемое (untracked);
    - измененное (modified);
    - подготовленное (staged);
    - закомиченное (committed).
- **Commit** - это основной объект в управлении контроля версий. Он содержит все изменения за время этого коммита. Коммиты связаны между с собой как односвязный список. 
    Также у коммита есть еще своя информация, так называемые метаданные:
    - уникальный идентификатор коммита, по которому можно его найти;
    - имя автора коммита, который создал его;
    - дата создания коммита;
    - комментарий, который описывает, что было сделано во время этого коммита.
- **Branch** - это указатель какого-то коммита. Так как коммит знает, какой коммит был до него, когда ветка указывает на какой-то коммит, к ней относятся и все те предыдущие. 