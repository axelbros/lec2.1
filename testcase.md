## Title

## Проверка новой бонусной системы

### Summary

Проверим написанный код(программу) на правильность расчета бонусов

### Priority

middle

### Steps to reproduce

1. Открыть IntelliJ IDEA
2. Создать проект
3. Создать Main.java class
4. Вставить код
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
5. Запустить программу


### Expected result

1. IntelliJ IDEA запущена
2. Проект создан
3. Main.java class создан
4. Код вставлен
5. Программа запущена, в терминале видим ответ 0,9


### Дополнительно

1. Код для вставки (4 шаг)

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








