# pc.is_clear_skill_group()
Функция **pc.is_clear_skill_group** сообщает, выбрал ли игрок набор навыков или нет.

## Возвращаемые значения
### is_clear_skill_group
Тип *boolean*. `true`, если у игрока не выбраны навыки; иначе `false`.

## Примечания
Функция **не** может быть вызвана анонимно.

Данная функция является некой оберткой для проверки квестового флага `clear` в квесте `skill_group_clear`. Если данный флаг равен `1`, то функция возвращает `true`, иначе `false`. Примечательно то, что в ядре не было найдено, чтобы где-нибудь задавалось значение этого флага, то бишь вы должны задавать его самостоятельно. Именно поэтому эту функцию лучше вообще не использовать &mdash; используйте [pc.get_skill_group](../pc/pc.get_skill_group.md)() (при отсутствии набора навыков возвращает `0`).