---
title: Constants
localeTitle: Константы
---
## Константы

Константы - это тип переменной в PHP. Функция `define()` для установки константы принимает три аргумента - имя ключа, значение ключа и логическое (true или false), которое определяет, не является ли имя ключа нечувствительным к регистру (по умолчанию установлено false). Значение константы не может быть изменено после его установки. Он используется для значений, которые редко меняются (например, пароль базы данных или ключ api).

### Объем

Важно знать, что в отличие от переменных константы ALWAYS имеют глобальную область видимости и могут быть доступны из любой функции в скрипте.

### пример

```PHP
<?php 
 define("freeCodeCamp", "Learn to code and help nonprofits", false); 
 echo freeCodeCamp; 
```

**Выход:**

```text
Learn to code and help nonprofits 
```

#### Дополнительная информация:

*   [Руководство по константам php.net](https://secure.php.net/manual/en/language.constants.php)
*   [Руководство по php.net define ()](https://secure.php.net/manual/en/function.define.php)