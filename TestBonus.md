# Отчёт о тестировании приложения "Precision"

## Краткое описание

17.09.2020 проведено функциональное тестирование приложения Precision. 

На тестирование затрачено: 30 мин

## Описание процесса тестования
Произведено функциональное тестирование приложения. Тест функции расчета бонусов. 

В процессе тестирования использовались артефакты:
* Баг-репорт
* Отчет о тестировании

В качестве тестовых данных использовался исходный код:
```
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```
Тестирование производилось в следующем окружении:
* Устройство: ASUS N73S
* ОС: Windows 10 Pro-64 bit
* Java version: "11.0.8" 2020-07-14
* IntelliJ IDEA CE 2020.2.1

## Результаты
1. 100% не успешных тестов
2. [Расчёт бонусов производится неправильно](https://github.com/Rimmkin/homework_2.2-java/issues/1#issue-703395715)
