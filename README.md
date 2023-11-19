# Прожитые дни

Позволяет узнать, сколько прошло дней от даты рождения

## Требования

- PHP 7.4

## Установка

```bash
 composer required ekovalev/livedday
```

## Использование

```php
<?php
use Ekovalev\Otus\LivedDay;

$lDay = new LivedDay();

$amountDays = $lDay->calculate('13-01-1986');
echo "Вы прожили $amountDays дней";

```