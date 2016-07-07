# d.is_unique_dead()
Функция **d.is_unique_dead** проверяет, мертв ли уникальный монстр.

## Параметры функции
### unique_name
Тип *string*. **Обязательный параметр**. Имя уникального монстра

## Возвращаемые значения
### is_dead
Тип *boolean*. `true`, если монстр мертв, а `false` &mdash; если жив. Также `false` возвращается в случаях, если параметр [unique_name](#unique_name) не является строкой или если функция была вызвана вне подземелья. `true`, если уникального монстра с таким именем не существует.

## Примечания
Функция может быть вызвана анонимно.

Функция работает только в подземельях.