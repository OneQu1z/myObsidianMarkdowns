# **1. Основы программирования**

1.1 Типы данных, переменные, функции  
1.2 Ветвления (if/else, булева алгебра)  
1.3 Циклы (while, for)  
1.4 Массивы  
1.5 Введение в алгоритмы и сложность (O-нотация)

---

# **2. Объектно-ориентированное программирование (ООП)**

2.1 Классы и объекты  
2.2 Конструкторы  
2.3 Поля и методы  
2.4 Статические поля и методы  
2.5 Модификаторы доступа, инкапсуляция  
2.6 Наследование  
2.7 Полиморфизм  
2.8 Переопределение и перегрузка методов  
2.9 Абстрактные классы и интерфейсы  
2.10 Класс Object и его методы  
2.11 equals() & hashCode()

---

# **3. Исключения**

3.1 Иерархия исключений  
3.2 checked vs unchecked  
3.3 try-catch-finally  
3.4 пробрасывание исключений  
3.5 AutoCloseable, Closable  
3.6 try-with-resources

---

# **4. Коллекции и Generics**

4.1 Generics (очень важно!)  
4.2 Интерфейс Collection и иерархия  
4.3 ArrayList  
4.4 LinkedList  
4.5 Queue / Stack  
4.6 HashSet  
4.7 LinkedHashSet / TreeSet  
4.8 HashMap  
4.9 LinkedHashMap / TreeMap  
4.10 Comparable / Comparator  
4.11 Внутренние классы  
4.12 Лямбды  
4.13 Stream API: основные методы

---

# **5. Паттерны и качество кода**

5.1 SOLID  
5.2 DRY / KISS / YAGNI  
5.3 Паттерны проектирования:

- Singleton
- Factory
- Builder
- Strategy
- Template Method
- Adapter
- Facade
- Observer
- Proxy

---

# **6. Многопоточность и параллелизм**

6.1 Thread, Runnable, Параллелизм
6.2 synchronized, mutex, lock  
6.3 wait/notify  
6.4 Асинхронизм
6.4 volatile
6.5 Immutable классы  
6.6 Future, Callable
6.6 Executorservice, пул потоков
6.7 CompletableFuture  
6.8 Concurrency API  
6.9 ConcurrentHashMap

---

# **7. Работа с файлами, IO/NIO**

7.1 InputStream/OutputStream  
7.2 FileReader/FileWriter  
7.3 NIO: Path, Files, Channel, Buffer

---

# **8. Maven/Gradle**

8.1 зависимости  
8.2 Build & Clean  
8.3 профили (dev/test/prod)  
8.4 multi-module проекты

---

# **9. Unit-тестирование**

9.1 JUnit  
9.2 Mockito  
9.3 MockMvc  
9.4 Интеграционные тесты  
9.5 TestContainers

---

# **10. SQL и базы данных**

10.1 Основы SQL  
10.2 JOIN (inner/left/right/full)  
10.3 Индексы (B-Tree, Hash)  
10.4 Нормальные формы (1NF–3NF)  
10.5 Транзакции (ACID)  
10.6 explain/analyze  
10.7 SQL vs NoSQL

---

# **11. JPA, Hibernate, Spring Data**

11.1 Entity, Session  
11.2 @OneToOne, @OneToMany, @ManyToMany  
11.3 Spring Data: запросы по названиям методов  
11.4 @Query  
11.5 Кэш Hibernate 1 и 2 уровня  
11.6 @Transactional, isolation, propagation
11.7 Liquibase (миграции, changelog, rollback)

---

# **12. Spring Framework**

12.1 Бины, контекст, scope  
12.2 Component-like аннотации  
12.3 Java-конфигурация бинов  
12.4 Трёхслойная архитектура Controller–Service–Repository  
12.5 Spring Boot структура проекта  
12.6 Actuator  
12.7 Proxy, CGLIB/Java Proxy  
12.8 @Scheduled  
12.9 @Async  
12.10 Spring Security (JWT, фильтры, конфигурация)
12.11 Логирование: SLF4J, Logback, уровни логов, конфигурация

---

# **13. Web-разработка**

13.1 HTTP, устройство запроса–ответа  
13.2 Методы HTTP  
13.3 JSON  
13.4 REST, REST API  
13.5 Spring Web: @RequestMapping, @Controller, @RestController  
13.6 GlobalExceptionHandler: @ControllerAdvice  
13.7 Postman  
13.8 RestTemplate / Feign Client  
13.9 Монолиты vs микросервисы

---

# **14. DevOps и инфраструктура**

14.1 Docker: Image, Container  
14.2 Docker Compose  
14.3 CI на GitHub  
14.4 Jenkins  
14.5 CD, автодеплой, использование Docker Image
14.6 Cloud: масштабирование, отказоустойчивость  
14.7 Grafana + метрики

---

# **15. Кэширование**

15.1 Redis  
15.2 Pessimistic vs Optimistic Lock

---

# **16. Архитектура приложений**

16.1 Event Driven Architecture  
16.2 DDD (базово)  
16.3 CQRS  
16.4 Hexagonal / Clean Architecture
16.5 Брокеры сообщений vs REST (RabbitMQ, Kafka, очереди, event-driven подход)

---

# **17. Kafka**

17.1 Topic, Partition  
17.2 Принципы гарантии доставки  
17.3 Масштабирование  
17.4 Консьюмеры и продюсеры