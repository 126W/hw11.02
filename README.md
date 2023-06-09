# Домашнее задание к занятию "11.2. Кеширование Redis/memcached" - Евгений Шахов
---
### Задание 1

Кэширование позволяет увеличивать производительность веб-приложений за счет использования сохраненных ранее данных, вроде ответов на сетевые запросы или результатов вычислений. Благодаря кэшу, при очередном обращении клиента за одними и теми же данными, сервер может обслуживать запросы быстрее. Кэширование — эффективный архитектурный паттерн, так как большинство программ часто обращаются к одним и тем же данным и инструкциям. Эта технология присутствует на всех уровнях вычислительных систем. Кэши есть у процессоров, жестких дисков, серверов, браузеров.
Эффективное кэширование помогает как пользователям, так и контент-провайдерам. Преимущества:
+ Снижение сетевых затрат. Контент можно кэшировать в разных точках сетевого пути между потребителем и источником контента. Когда контент кэшируется ближе к потребителю, запросы не будут требовать значительной сетевой активности за пределами кэша.
+ Повышение отзывчивости. Кэширование позволяет получать контент быстрее, потому что нет необходимости снова проделывать путь по всей сети. Кэши, поддерживаемые рядом с пользователем, например кэш браузера, могут сделать обслуживание запроса почти мгновенным.
+ Повышенная производительность. Контент-провайдер может использовать мощные серверы в пути доставки, чтобы взять на себя основную нагрузку на обслуживание контента.
+ Доступность контента во время сбоев сети. При использовании определенных политик кэширование может обслуживать контент пользователям даже в течение коротких сбоев.

---

### Задание 2

![image](https://user-images.githubusercontent.com/122415129/227725444-f56d2648-5410-4f2b-8804-6431d252f8e1.png)

---

### Задание 3

![image](https://user-images.githubusercontent.com/122415129/227727787-89c6c005-ff45-4503-9ff2-bb4978da2b41.png)

---

### Задание 4

![image](https://user-images.githubusercontent.com/122415129/227728338-bf2723c6-2543-495f-8152-5c7d8fc390d2.png)

![image](https://user-images.githubusercontent.com/122415129/227730244-5c1d649c-8cf1-4e90-a7eb-56b61b02b2e2.png)

![image](https://user-images.githubusercontent.com/122415129/227729756-0fad2a78-2ff1-40e6-9f51-bf210e93b660.png)

---

### Задание 5

![image](https://user-images.githubusercontent.com/122415129/227730086-79d48a03-ff3d-447b-9c55-63d95ac82218.png)

---
