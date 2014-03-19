date-control
============

Сделан по мотивам календаря из [советов в Бюро](http://artgorbunov.ru/bb/soviet/20070628/).
[https://makingoff.github.io/date-control/](https://makingoff.github.io/date-control/)

## Пока

* Формат даты только тот, что в примере (index.html)
* годы фиксированно ограничены
* тестировался только под современные браузеры
* поддержка тач-устройств

## Хочу

* Возможность задавать диапозон для годов
* возможность задавать больше двенадцати годов
* добавить локализации

## Мини-АПИ

```
$('.input-date-control').dateControl({
  changeDate: function (year, month, day, dateText)
  {
    // кликнули по дате
    // month — месяцы возвращаются в диапозоне от 0 до 11
    // dateText — дата текстом в заданном фиксированном формате
  },
  changeYear: function (year, month, day, dateText)
  {
    // мы проскролили год
    // параметры такие же
  }
});
```

## Release Notes
### v.0.0.3

* Клики по месяцам и годам для тач-устройств

### v.0.0.2

* Добавил поддержку тач-устройств
