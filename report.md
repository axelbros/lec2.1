## Отчёт о тестировании внедрения бонусной системы

### Краткое описание

01.04.21 - 01.04.21 было проведено функциональное тестирование приложения приёма платежей.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* **[Issue](https://github.com/axelbros/lec2.1/issues/1)**


### Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* **[Тест-кейс](https://github.com/axelbros/lec2.1/blob/master/testcase.md)**




### В качестве тестовых данных использовались данные от разработчиков:
* Код: 
```java
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```


### Тестирование производилось в следующем окружении:
* Win 10 x64
* Java 11
* IntelliJ IDEA Ultimate 2020.3.3