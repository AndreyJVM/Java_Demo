**Принцип KISS "Keep It Short and Simple"** — это когда вы берёте задачу и решаете её простым способом:

- Не подключаете всю библиотеку, если нужна всего пара функций.
- Не закладываете избыточные функции, если о них не просил заказчик.
- Не используете избыточные классы и методы.
- Не перегружаете интерфейс и не делаете сложную бизнес-логику.
- Не выполняете другие действия, если они не влияют на работу проекта.

---

**Принцип "Не повторяйся" DRY "Don`t Repeat Yourself"** — избегать дублирование кода

---

**Принцип единственной ответственности SRP "Single Responsibility Principle"** — 
- никогда не должно быть больше одной причины изменить класс.
- Один класс несёт ответственность за одну функциональность приложения.

Обычно применяется для классов и методов.

---

**Связность High Cohesion** — характеризует то, как взаимодействуют друг с другом различные детали.
 
- связность — это мера того, насколько сильно взаимосвязанны задачи элементов внутри класса или метода.

**Внутриклассовая связность:**

- Функциональная 
    Опасность функциональной связности заключается в том, что можно поддаться искушению и создать слишком много простых 
классов имеющих по одному методу

- Информационная 
- Служебная 
- Логическая
- Последовательная 
- Временная 

---

**Объект доступа к данным DAO Data Access Object** — представляет собой абстрактный класс и инкапсулирует
доступ к источнику данных.

---

**Связанность Low Coupling** — показывает уровень зависимости от других классов.

Это важно, поскольку, чем больше функций возложено на класс, тем сложнее вносить в него
изменения

###### Например часы: главное, чтобы вы знали время(интерфейс), а (реализация) как оно устроенно внутри для нас не важно

---

**Автоматизированное тестирование**

Если вы хотите быть уверены в том, что ваша программа ведет себя корректно и работает стабильно, тестирование
должно производиться **сразу** после внесение изменений в программное обеспечение.

Выполнение тестов для проверки поведения программы на **соответствие спецификации** дает вам уверенность,
что вы выполнили все требования заказчика.

---

**Исключения Java**

![exceptionsInJavaHierarchy.png](../../resources/exceptionsInJavaHierarchy.png)