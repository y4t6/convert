Если с одной стороны – объект, а с другой – нет, то сначала приводится объект.

В данном случае сравнение означает численное приведение. У массивов нет valueOf, поэтому вызывается toString, который возвращает список элементов через запятую.

В данном случае, элемент только один – он и возвращается. Так что ['x'] становится 'x'. Получилось 'x' == 'x', верно.

P.S. По той же причине верны равенства:
```js
alert( ['x', 'y'] == 'x,y' ); // true
alert( [] == '' ); // true
```

[task](https://github.com/y4t6/convert/blob/master/5_6.md)
