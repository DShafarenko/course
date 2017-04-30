# Нормализация строки

Вам надо реализовать функцию `normalize`, которая возвращает исправленную строку.

Правила нормализации:
- заглавной может быть только первая буква в строке;
- два пробела не могут идти один за другим;
- первым или последним символом не может быть пробел.

Примеры:

```javascript
normalize(" HElLo,    wORld  !   "); // "Hello, world !"
normalize("hELLo  "); // "Hello"
normalize("   "); // ""
```

[Тесты для заданияъ(http://codepen.io/gaech/pen/JNNJqg)