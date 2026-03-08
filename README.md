<h1 align="center">Hi there, I'm Sergey 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Python Developer | Security Engineer | Automation Specialist 🇷🇺</h3>

<p align="center">
  <a href="https://t.me/DepartmentofMoney">Telegram</a> • 
  <a href="https://github.com/serejka-xaker">GitHub</a>
</p>

---

### 👨‍💻 Обо мне

Выпускник ОмГТУ (Информационная безопасность, диплом с отличием). 
Разрабатываю на Python более 1 года. Специализируюсь на **асинхронной разработке**, **Telegram-ботах** и **автоматизации процессов**. 
Имею коммерческий опыт внедрения систем защиты информации (DLP) и расследования инцидентов.

Ищу возможности для работы **Python Developer** или **DevSecOps Engineer** (удаленно).

---

### 🛠 Технический стек

| Категория | Технологии |
|-----------|------------|
| **Languages** | Python 3.11+, SQL, Bash |
| **Core** | Asyncio, Multithreading, OOP, REST API, OAuth2 |
| **Telegram** | aiogram 3.x, Telethon (MTProto) |
| **Web & API** | FastAPI, Flask, Requests, BeautifulSoup, Selenium |
| **Databases** | PostgreSQL, SQLite, MongoDB, SQLAlchemy 2.0 |
| **DevOps** | Docker, Docker Compose, Git, Linux (Astra, Debian) |
| **Security** | Wireshark, UserGate, SearchInform DLP, OWASP Top 10 |

---

### 🚀 Ключевые проекты

#### 🏆 SaaS-платформа для управления парком Telegram-ботов
*Микросервисная архитектура с поддержкой Multi-tenancy*
- **Архитектура:** Мастер-бот динамически запускает дочерних ботов в изолированных процессах.
- **Безопасность:** Разделение данных клиентов, уникальные API-ключи, RBAC.
- **Стек:** `aiogram 3` `PostgreSQL` `Docker` `SQLAlchemy Async` `REST API`
- 🔗 [telegram-bot-park-manager](https://github.com/serejka-xaker/telegram-bot-park-manager)

#### 📱 Инфраструктура мультиаккаунтной автоматизации (MTProto)
*Система управления сессиями и прокси для Telegram*
- **Функционал:** Ротация прокси, менеджер сессий, защита от блокировок.
- **Архитектура:** Асинхронная обработка, логирование ошибок, ORM-модель аккаунтов.
- **Стек:** `Telethon` `Asyncio` `SQLite` `Proxy-инфраструктура`
- 🔗 [telegram-commenting-multiaccount-infrastructure](https://github.com/serejka-xaker/telegram-commenting-multiaccount-infrastructure)

#### 💰 Telegram-бот для обмена валют с Docker-инфраструктурой
*Сервис с автоматическим парсингом курсов*
- **Инфраструктура:** Микросервисы в контейнерах (Bot + Selenium + MongoDB).
- **Оптимизация:** Headless Chrome в Docker, интеграция синхронного Selenium в asyncio.
- **Стек:** `aiogram` `Selenium` `Docker Compose` `MongoDB` `APScheduler`
- 🔗 [exchange-money-docker-selenium](https://github.com/serejka-xaker/exchange-money-docker-selenium)

#### 🕷️ Парсеры вакансий (HH.ru, SuperJob)
*Автоматизированный сбор данных с обходом антибот-защиты*
- **Функции:** OAuth2 авторизация, обход Cloudflare, экспорт в Excel/DB.
- **Надежность:** Exponential backoff, валидация данных, дедупликация.
- **Стек:** `Python` `Requests` `BeautifulSoup` `Flask` `OAuth2`
- 🔗 [hh-vacancy-parser](https://github.com/serejka-xaker/hh-vacancy-parser) | [superjob-parser-flask](https://github.com/serejka-xaker/superjob-parser-flask)

#### 🤖 Telegram-бот модератор с геймификацией
*Автоматическая модерация и система рейтинга пользователей*
- **Функции:** Стоп-слова, начисление баллов, разграничение прав доступа.
- **Архитектура:** Асинхронная БД, централизованное логирование.
- **Стек:** `aiogram 3` `APScheduler` `SQLite` `aiosqlite`
- 🔗 [telegram-moderation-bot](https://github.com/serejka-xaker/telegram-moderation-bot)

#### 📥 Парсер вакансий из Telegram-каналов
*Асинхронный сбор сообщений через Telethon*
- **Функции:** Фильтрация по ключевым словам, нормализация UTC, экспорт в Excel.
- **Стек:** `Telethon` `asyncio` `pandas` `configparser`
- 🔗 [vacancy-telegram-channel-parser](https://github.com/serejka-xaker/vacancy-telegram-channel-parser)

#### 🎬 Автоматизация загрузки видео в TikTok
*Selenium-автоматизация с обходом антибот-защиты*
- **Функции:** Undetected Chromedriver, работа с куки, поддержка прокси.
- **Стек:** `SeleniumBase` `Undetected Chromedriver` `WebDriver`
- 🔗 [tiktok-upload-automation](https://github.com/serejka-xaker/tiktok-upload-automation)

#### 🤖 Автоматизация взаимодействия с Telegram-ботами (MTProto)
*Прямая работа с Telegram API вместо GUI-автоматизации*
- **Функции:** Динамический анализ клавиатуры, мультиаккаунтность.
- **Стек:** `Telethon` `asyncio` `SQLite` `JSON`
- 🔗 [telegram-bot-automation-mtproto](https://github.com/serejka-xaker/telegram-bot-automation-mtproto)

#### 🔧 Оптимизация HTTP-парсера криптобиржи
*Обход защиты Cloudflare через модификацию заголовков*
- **Функции:** User-Agent ротация, тестирование стабильности.
- **Стек:** `requests` `selenium` `Python`
- 🔗 [http-parser-optimization](https://github.com/serejka-xaker/http-parser-optimization)

> 💡 *Полный список проектов доступен во вкладке **Repositories**.*

---

### 💼 Опыт работы

**Python Developer (Freelance)**
*Разработка автоматизации, ботов и парсеров*
- Полный цикл разработки: от архитектуры до деплоя.
- Создание отказоустойчивых систем сбора данных.

**Специалист по информационной безопасности**
*Внедрение DLP, расследование инцидентов, администрирование*
- SearchInform DLP (Astra Linux), Security Onion, UserGate.
- Расследование 300+ инцидентов ИБ.
- Автоматизация аудита (Bash, Python).

---

### 📫 Контакты

- **Telegram:** [@DepartmentofMoney](https://t.me/DepartmentofMoney)

