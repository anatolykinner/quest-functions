# d.is_use_potion()
Функция **d.is_use_potion** проверяет, использовал ли кто-нибудь из участников подземелья зелья за весь подъем.

## Параметры функции
### empty_parameter1
Тип *number*. **Обязательный параметр**. Параметр, который ни на что не влияет (возможно, это баг).

### empty_parameter2
Тип *number*. **Обязательный параметр**. Параметр, который ни на что не влияет (возможно, это баг).

## Возвращаемые значения
### was_used
Тип *boolean*. Было ли использовано зелье. `true`, если да, и `false`, если нет. Также возвращается `true` в случаях, если один из параметров не был задан или не является числом, а также если функция была вызвана вне подземелья.

## Примечания
Функция может быть вызвана анонимно.

В качестве параметров необходимо указать совершенно любые числа, например `d.is_use_potion(1, 1)`. Эти параметры ни на что не повлияют, но если их не указать, то функция вернет `true`. Это баг.

Неизвестно, при использовании каких именно предметов функция начнет возвращать `true`.

Эта функция работает только в подземельях.