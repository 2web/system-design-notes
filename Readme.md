**Русский** | [English](./Readme.en.md)


# [System Design Interview — An Insider's Guide (т. 1 и 2)](https://bytebytego.com/courses/system-design-interview)
Эти конспекты основаны на книгах System Design Interview — [т. 1 и т. 2, 2-е изд.](https://www.goodreads.com/book/show/54109255-system-design-interview-an-insider-s-guide) 

Конспекты можно посмотреть здесь: https://pagefy.io/system-design/system-design-interview-by-alex-xu

**Примечание:** работа над конспектами ещё продолжается. 


 * [Глава 1 — Масштабирование от нуля до миллионов пользователей](./01.%20Scaling/)
 * [Глава 2 — Оценки «на салфетке» (Back-of-the-envelope Estimation)](./02.%20Back%20Of%20the%20Envelope%20Estimation/)
 * [Глава 3 — Фреймворк для интервью по проектированию систем](./03.%20System%20Design%20Framework/)
 * [Глава 4 — Проектирование ограничителя запросов (Rate Limiter)](./04.%20Rate%20Limiter//)
 * [Глава 5 — Проектирование консистентного хеширования (Consistent Hashing)](./05.%20Consistent%20Hashing/)
 * [Глава 6 — Проектирование хранилища «ключ — значение» (Key-Value Store)](./06.%20Key-Value%20Store/)
 * [Глава 7 — Проектирование генератора уникальных ID (Identifier — идентификатор) в распределённых системах](./07.%20Unique-Id%20Generator/)
 * [Глава 8 — Проектирование сервиса сокращения ссылок (URL Shortener)](./08.%20URL%20Shortener/)
 * [Глава 9 — Проектирование веб-краулера (Web Crawler)](./09.%20Web%20Crawler/)
 * [Глава 10 — Проектирование системы уведомлений](./10.%20Notification%20System/)
 * [Глава 11 — Проектирование системы ленты новостей (News Feed)](./11.%20News%20Feed%20System/)
 * [Глава 12 — Проектирование чата](./12.%20Chat%20System/)
 * [Глава 13 — Проектирование системы автодополнения поиска](./13.%20Search%20Autocomplete/)
 * [Глава 14 — Проектирование YouTube](./14.%20Youtube/)
 * [Глава 15 — Проектирование Google Drive](./15.%20Google%20Drive/)
 * [Глава 16 — Сервис поиска поблизости (Proximity Service)](./16.%20Proximity%20Service/)
 * [Глава 17 — Друзья поблизости (Nearby Friends)](./17.%20Nearby%20Friends/)
 * [Глава 18 — Проектирование Google Maps](./18.%20Google%20Maps/)
 * [Глава 19 — Распределённая очередь сообщений](./19.%20Distributed%20Message%20Queue/)
 * [Глава 20 — Система сбора метрик, мониторинга и алертинга](./20.%20Metrics%20Monitoring%20and%20Alerting%20System/)
 * [Глава 21 — Агрегация событий кликов по рекламе](./21.%20Ad%20Click%20Event%20Aggregation/)
 * [Глава 22 — Система бронирования отелей](./22.%20Hotel%20Reservation%20System/)
 * [Глава 23 — Распределённый почтовый сервис](./23.%20Distributed%20Email%20Service/)
 * [Глава 24 — Объектное хранилище в стиле S3 (Amazon Simple Storage Service)](./24.%20S3-like%20Object%20Storage/)
 * [Глава 25 — Игровой рейтинг (лидерборд) в реальном времени](./25.%20Real-time%20Gaming%20Leaderboard/)
 * [Глава 26 — Платёжная система](./26.%20Payment%20System/)
 * [Глава 27 — Цифровой кошелёк](./27.%20%20Digital%20Wallet/)
 * [Глава 28 — Фондовая биржа](./28.%20Stock%20Exchange/)


# Дополнительные материалы

### Ограничение частоты запросов (Rate Limiting)
- [Circuit Breaker Algorithm](https://martinfowler.com/bliki/CircuitBreaker.html)
- [Uber Rate Limiter](https://github.com/uber-go/ratelimit/blob/master/ratelimit.go)


### Консистентное хеширование (Consistent Hashing)
- [Consistent Hashing](https://tom-e-white.com/2007/11/consistent-hashing.html)
- [CS168: Introduction and Consistent Hashing:]( http://theory.stanford.edu/~tim/s16/l/l1.pdf)
- [Apache Cassandra](http://www.cs.cornell.edu/Projects/ladis2009/papers/Lakshman-ladis2009.PDF)
- [Scaling Discord](https://blog.discord.com/scaling-elixir-f9b8e1e7c29b)
- [Google Maglev](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44824.pdf)


### Хранилище «ключ — значение» (Key-Value Store)
- [Amazon Dynamo](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
- [Cassandra Architecture](https://docs.datastax.com/en/archived/cassandra/3.0/cassandra/architecture/archIntro.html)
- [Google BigTable Architecture](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
- [Amazon Dynamo DB Internals](https://www.allthingsdistributed.com/2007/10/amazons_dynamo.html)
- [Design Patterns in Amazon Dynamo DB](https://www.youtube.com/watch?v=HaEPXoXVf2k)
- [Internals of Amazon Dynamo DB](https://www.youtube.com/watch?v=yvBR71D0nAQ)


### Генератор уникальных ID
- [Ticket Servers: Distributed Unique Primary Keys on the Cheap](https://code.flickr.net/2010/02/08/ticket-servers-distributed-unique-primary-keys-on-the-cheap)
- [Snowflake](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake.html)


### Веб-краулер
- [Web Crawling](http://infolab.stanford.edu/~olston/publications/crawling_survey.pdf)
- [Google Dynamic Rendering](https://developers.google.com/search/docs/guides/dynamic-rendering)



### Чаты
- [How Discord stores billions of messages](https://discord.com/blog/how-discord-stores-billions-of-messages)
- [Flannel: An Application-Level Edge Cache to Make Slack Scale](https://slack.engineering/flannel-an-application-level-edge-cache-to-make-slack-scale/)


### Автодополнение поиска
- [How We Built Prefixy](https://medium.com/@prefixyteam/how-we-built-prefixy-a-scalable-prefix-search-service-for-powering-autocomplete-c20f98e2eff1)
- [Prefix Hash Tree](https://people.eecs.berkeley.edu/~sylvia/papers/pht.pdf)


### YouTube
- [YouTube Architecture](http://highscalability.com/youtube-architecture)
- [YouTube scalability 2012](https://www.youtube.com/watch?v=w5WVu624fY8)
- [Transcoding Videos at Scale](https://www.egnyte.com/blog/2018/12/transcoding-how-we-serve-videos-at-scale/)
- [Facebook Video Broadcasting](https://engineering.fb.com/ios/under-the-hood-broadcasting-live-video-to-millions/)
- [Netflix Video Encoding at Scale](https://netflixtechblog.com/high-quality-video-encoding-at-scale-d159db052746)
- [Netflix Shot based encoding](https://netflixtechblog.com/optimized-shot-based-encodes-now-streaming-4b9464204830)


### Google Drive
- [Differential Synchronization](https://neil.fraser.name/writing/sync/)
- [Differential Synchronization Video](https://www.youtube.com/watch?v=S2Hp_1jqpY8)
- [How We’ve Scaled Dropbox](https://www.youtube.com/watch?v=PE4gwstWhmc&feature=youtu.be)
