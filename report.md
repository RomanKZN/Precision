# Отчёт о тестировании программы бонусной системы

## Краткое описание

Дата начала 30.09.2021 было проведено функциональное тестирование приложения Бонусной системы.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

* [Приложение не верно рассчитывает дополнительный бонус новым
  клиентам](https://github.com/RomanKZN/Precision/issues/1#issue-1013657640)

## Описание процесса тестирования
Создать базовое приложение и разместить в нём переданный код.

В качестве тестовых данных использовать данные из Задачи №2 - Precision:

`public class Main { public static void main(String[] args) { double regularBonus = 0.3; double specialBonus = 0.6; double totalBonus = regularBonus + specialBonus; System.out.println(totalBonus); } }`

Тестирование производилось в следующем окружении:

* Windows 10 Pro 64-bit
* Java version 11.0.12
* IntelliJ IDEA