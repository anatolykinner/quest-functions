# building.set_land_owner()
Функция **building.set_land_owner** позволяет гильдии купить землю.

## Параметры функции
### land_id
Тип *number*. **Обязательный параметр**. ID земли гильдии, которую необходимо купить.

### guild_id
Тип *number*. **Обязательный параметр**. ID гильдии, которая станет владельцем земли.

## Примечания
Функция может быть вызвана анонимно.

Параметр [guild_id](#guild_id) не может быть равен `0`.

Эта функция сработает только в том случае, если возвращаемый параметр [guild_id](../building/building.get_land_info.md#guild_id) функции [building.get_land_info](../building/building.get_land_info.md)() равен `0`.

Теоретически, эту функцию можно запускать даже не от лица лидера гильдии.