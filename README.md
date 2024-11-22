# Product-Category-Analyzer

## Опис проекту
**Product-Category-Analyzer** — це Java-додаток, який демонструє використання Stream API для обробки списку продуктів, групування їх за категоріями, розрахунку середньої ціни у кожній категорії та пошуку категорії з найвищою середньою ціною.

### Основні класи
1. **Product.java** — клас, що представляє продукт із полями `name`, `category` та `price`, а також відповідними конструкторами, геттерами та методами для зручного доступу до даних.
2. **Main.java** — основний клас програми, який:
   - Створює список об'єктів класу Product.
   - Використовує Stream API для обробки даних.
   - Виводить середню ціну для кожної категорії та категорію з найвищою середньою ціною.

### Як працює програма
1. **Створення продуктів**:
   - Продукти ініціалізуються як об'єкти класу Product.
   - Дані включають назву, категорію та ціну продукту.

2. **Групування за категоріями**:
   - Дані групуються за категоріями за допомогою `Collectors.groupingBy`.
   - Розраховується середня ціна для кожної категорії з використанням `Collectors.averagingDouble`.

3. **Пошук категорії з найвищою середньою ціною**:
   - Використовується `Map.Entry` для знаходження категорії з найбільшою середньою ціною.

4. **Вивід результатів**:
   - Виводяться середні ціни за категоріями.
   - Показується категорія з найвищою середньою ціною.

### Вимоги до системи
- Java 8 або вище
- Середовище розробки Java (наприклад, IntelliJ IDEA, Eclipse, VSCode)

