## Hi there 👋, меня зовут **Сергей**, я Java Backend Developer.


Перешёл в разработку после многолетнего опыта в логистике и управлении процессами.
Создаю backend-системы на Java: от архитектуры до деплоя. Особый интерес — серверная логика, многопользовательские системы и чистая архитектура.

---

## 🛠 Стек

| Категория | Технологии |
|-----------|------------|
| Язык | Java 17+ |
| Backend | Spring Boot, Spring MVC, Spring Data JPA, Hibernate |
| API | REST, OpenAPI / Swagger |
| БД | PostgreSQL, Flyway |
| Тестирование | JUnit 5, Mockito |
| DevOps | Docker, Linux, Git, Maven, VPS deploy |

---

## 📂 Проекты

### 📦 Logistics Bot — Telegram-бот для логистической компании

> Backend-приложение для автоматизации диспетчерской работы

 
 🔗 [Репозиторий](https://github.com/cepheil/logistic-bot) · [Подробнее](https://github.com/cepheil/logistic-bot#readme)  

- Многошаговый wizard создания заявок
- Ролевая модель доступа (диспетчер / логист / админ)
- Планировщик рассылок по группам
- Управление транспортом и откликами
- Проверка организаций по ИНН (отдельный модуль)
- REST API, Docker-деплой, unit- и integration-тесты

Проект построен с разделением слоёв (controller → service → repository), конфигурация через профили (dev/prod), миграции БД управляются Flyway.


`Java 17` · `Spring Boot` · `Spring Data JPA` · `PostgreSQL` · `Flyway` · `REST` · `Docker` · `JUnit 5` · `Mockito`

---

### ♠️ Poker Bot — многопользовательский покерный движок в Telegram

> Бот-крупье для Texas Hold'em с полным игровым циклом, экономикой и системой прогрессии


<!-- 🔗 [Репозиторий](https://github.com/cepheil/poker-bot) · [Подробнее](https://github.com/cepheil/poker-bot#readme) -->

**Игровой движок**
- Полный цикл: preflop → flop → turn → river → showdown
- 10 покерных комбинаций с корректным сравнением
- Side-pots при multiple all-in, до 9 игроков за столом
- Provably fair шафл (SHA-256)

**Экономика и мультиплеер**
- Виртуальный баланс, ребаи, автоповышение блайндов
- Пошаговое создание лобби, deep-link приглашения
- ELO-рейтинг и лидерборд

**Геймификация**
- XP, уровни, 11 бейджей, стрики
- Ежедневные и еженедельные миссии с наградами
- 30-дневные сезоны с отдельным рейтингом

**Администрирование**
- Роли: USER / PRO / ADMIN
- Управление пользователями, broadcast-рассылка, мониторинг игр

`Java 17` · `Spring Boot` · `Spring Data JPA` · `PostgreSQL` · `Flyway` · `Docker` · `Maven`

---

### 🔬 Дополнительные проекты


| Проект | Описание | Стек |
|--------|----------|------|
| [Explore With Me](https://github.com/cepheil/java-explore-with-me) | Микросервисная афиша событий: создание, модерация, заявки на участие, подборки, статистика просмотров, комментарии | `Java 21` · `Spring Boot` · `Spring Data JPA` · `PostgreSQL` · `Docker` · `Maven` |
| [ShareIt](https://github.com/cepheil/java-shareit) | Микросервисный шеринг вещей: публикация, поиск, бронирование, отзывы. Gateway + Server, валидация, покрытие тестами 90%+ | `Java 21` · `Spring Boot` · `Spring Data JPA` · `PostgreSQL` · `MapStruct` · `Docker` · `Maven` |
| [Java Kanban](https://github.com/cepheil/java-kanban) | Трекер задач с иерархией Task/Epic/Subtask, REST API, файловой персистентностью, приоритизацией и историей просмотров (O(1) на двусвязном списке) | `Java 21` · `Gson` · `HttpServer` · `JUnit 5` |
| [Filmorate](https://github.com/cepheil/java-filmorate) | Групповой проект. Сервис рекомендаций фильмов: рейтинги, отзывы, лайки, лента активности, поиск по режиссёрам и жанрам | `Java 21` · `Spring Boot` · `H2` · `JDBC` · `Maven` |
| [Catsgram](https://github.com/cepheil/Catsgram) | REST API сервис публикации фото котов. Трёхслойная архитектура, чистый JDBC через обобщённый BaseRepository, загрузка изображений, Docker-деплой | `Java 21` · `Spring Boot` · `Spring JDBC` · `PostgreSQL` · `Docker` · `Maven` |

 
---

## 💼 Бэкграунд

До разработки — многолетний опыт в логистике:

- Управление клиентскими контрактами и бюджетами
- Формализация и оптимизация бизнес-процессов
- Участие в разработке внутреннего приложения как бизнес-эксперт
- Работа с 1С
- Командная работа с использованием Jira, Slack, YouTrack, GitHub Projects

Этот опыт помогает понимать бизнес-логику и проектировать решения, которые реально используются.

---

## 📫 Контакты

[![Telegram](https://img.shields.io/badge/Telegram-@rzpio-blue?logo=telegram)](https://t.me/rzpio)
[![Yandex](https://img.shields.io/badge/Yandex-cephei.l@yandex.ru-yellow?logo=yandex&logoColor=red)](mailto:cephei.l@yandex.ru)
[![Gmail](https://img.shields.io/badge/Email-sergeilev25@gmail.com-red?logo=gmail)](mailto:sergeilev25@gmail.com)
[![HeadHunter](https://img.shields.io/badge/HeadHunter-Резюме-critical)](https://hh.ru/resume/57942d5eff100e0ce80039ed1f375349486c54)

---

> Интересуют продуктовые команды, финтех и сложные серверные системы.


<!--
**cepheil/cepheil** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
