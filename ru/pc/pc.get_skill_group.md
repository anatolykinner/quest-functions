# pc.get_skill_group()
Функция **pc.get_skill_group** сообщает какой набор навыков у персонажа.

## Возвращаемые значения
### skill_group
Тип *number*. Если у персонажа нет набора навыков, то возвращается `0`.

## Примечания
| skill_group | Класс | Набор навыков |
| --- | --- | --- |
| `1` | Воин | Физический бой |
| `1` | Ниндзя | Ближний бой |
| `1` | Сура | Магическое оружие |
| `1` | Шаман | Мощь дракона |
| `1` | Ликан | - |
| `2` | Воин | Духовный бой |
| `2` | Ниндзя | Дальний бой |
| `2` | Сура | Темная магия |
| `2` | Шаман | Магия исцеления |

Функция **не** может быть вызвана анонимно.