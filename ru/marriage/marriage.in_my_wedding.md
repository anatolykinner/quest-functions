# marriage.in_my_wedding()
Функция **marriage.in_my_wedding** сообщает, находится ли игрок на свадебном острове, который был запущен им, или нет.

## Возвращаемые значения
### is_my_wedding
Тип *boolean*. Находится ли игрок на своем свадебном острове или нет. `true`, если да, иначе `false`.

## Примечания
Функция **не** может быть вызвана анонимно.

Когда одновременно запускаются две свадьбы, создаются два разных свадебных острова &mdash; два разных инстанса. Эта функция проверяет, находится ли игрок в том самом инстансе, который запустил именно он.