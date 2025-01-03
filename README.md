# BreadcrumbsAsynchronous-programming-Practical-task-6

Ця програма демонструє асинхронність у Spring за допомогою `@Scheduled` та `ScheduledExecutorService`.

## Завдання

- Кожні 10 секунд оновлюються дані у файлі `updated_data.txt`, збільшуючи лічильник на 5.
- Через 5 секунд після запуску програми виводиться повідомлення "5 секунд від запуску програми".

## Як запустити

1. Переконайтеся, що у вас встановлено Java та Gradle.
2. Клонуйте цей репозиторій.
3. Перейдіть у кореневу директорію проекту.
4. Виконайте команду для збірки та запуску програми:

   ```bash
   ./gradlew bootRun

## Очікуваний результат

Після запуску програми ви побачите наступний вивід у консолі:
```output
Записано у файл: Лічильник: 5
5 секунд від запуску програми
Записано у файл: Лічильник: 10
Записано у файл: Лічильник: 15
Записано у файл: Лічильник: 20
Записано у файл: Лічильник: 25
Записано у файл: Лічильник: 30
Записано у файл: Лічильник: 35
Записано у файл: Лічильник: 40
Записано у файл: Лічильник: 45
Записано у файл: Лічильник: 50
Записано у файл: Лічильник: 55
Записано у файл: Лічильник: 60
```

## Додатково

У кореневій директорії проекту буде створено файл updated_data.txt, який міститиме рядки з оновленими значеннями лічильника.

## Залежності

Spring Boot Starter