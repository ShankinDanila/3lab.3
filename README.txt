Вариант 16

 

1.Разработать класс "просматриваемая таблица" в соответствии со следующим заданием:

Состояние класса -

Таблица представляется в виде вектора (массива), состоящего из элементов. Элемент таблицы состоит из поля занятости (тип int), ключа (тип int) и информации (тип char[ ] фиксированной длины). Для описания элемента таблицы целесообразно использовать структуру. Память под массив выделяется статически, во время компиляции, и задается массивом фиксированного размера (SIZE).

Протокол класса -

Определяет  возможности создания и инициализации экземпляров класса и правила их использования (методы класса).

Предусмотреть следующие возможности:

·          создание экземпляров структуры (элемента таблицы) с инициализацией начальным состоянием по умолчанию;

·          пустой конструктор для инициализации экземпляров и массивов экземпляров класса (таблицы) по умолчанию;

·          создание экземпляров класса (таблицы) с инициализацией заданным количеством элементов из массива ключей и информации;

·          ввод значения экземпляра структуры (элемента таблицы) из входного потока;

·          вывод таблицы в выходной поток;

·          поиск элемента таблицы по ключу;

·          добавление элемента в таблицу;

·          выборка информации из таблицы по заданному ключу;

·          удаление элемента из таблицы (с отметкой в поле занятости) по ключу;

·          чистка таблицы от “удаленных элементов” – реорганизация таблицы.
