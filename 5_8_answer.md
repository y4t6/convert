**Ответ по первому равенству**

Два объекта равны только тогда, когда это один и тот же объект.

В первом равенстве создаются два массива, это разные объекты, так что они неравны.

**Ответ по второму равенству**

Первым делом, обе части сравнения вычисляются. Справа находится ![]. Логическое НЕ '!' преобразует аргумент к логическому типу. Массив является объектом, так что это true. Значит, правая часть становится ![] = !true = false. Так что получили:

```js
alert( [] == false );
```
Проверка равенства между объектом и примитивом вызывает численное преобразование объекта.

У массива нет valueOf, сработает toString и преобразует массив в список элементов, то есть – в пустую строку:

```js
alert( '' == false );
```
Сравнение различных типов вызывает численное преобразование слева и справа:

```js
alert( 0 == 0 );
```
Теперь результат очевиден.

[task](https://github.com/y4t6/convert/blob/master/5_8.md)
