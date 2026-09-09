# Привет, я domovoyproj

Пишу утилиты и сервисы соло — там, где важна скорость, на Rust, там, где не критично, на TypeScript или JS. Часто из одной задачи получается несколько репозиториев вместо одного монолита: у карты — отдельный репозиторий с бэкапом, у личного приложения — отдельное хранилище файлов и т.д.

## Проекты

**EPP** — набор Rust-инструментов для обработки данных и почты на общей платформе лицензирования:
- [xenos](https://github.com/domovoyproj/xenos) 🔒 — потоковая сортировка, дедупликация и фильтрация больших текстовых баз (mmap + Rayon), 8 режимов работы, интерфейс на WebView2.
- [epp-api](https://github.com/domovoyproj/epp-api) 🔒 — сервер лицензирования и биллинга для xenos и mck: авторизация, привязка по HWID, раздача обновлений (Axum, SQLite).
- [mck](https://github.com/domovoyproj/mck) 🔒 — многопоточный чекер почтовых аккаунтов по IMAP/POP3/SMTP с автоопределением серверов и поиском писем по заданным правилам (WebView2).

**Helper** — личное PWA-приложение и его вспомогательные репозитории:
- [helper-app](https://github.com/domovoyproj/helper-app) — трекер питания по фото через Gemini, учёт воды, шагов и настроения, календарь смен, бюджет и долги, менеджер паролей с TOTP, зашифрованный бэкап в облако.
- [helper-files](https://github.com/domovoyproj/helper-files) — публичное файловое хранилище для helper-app с короткими ссылками через TinyURL.
- [helper-backup](https://github.com/domovoyproj/helper-backup) 🔒 — приватное хранилище зашифрованных бэкапов helper-app (AES-256, zero-knowledge).

Остальное:
- [know-your-russia](https://github.com/domovoyproj/know-your-russia) 🔒 — интерактивная карта России с пользовательскими фото и модерацией; работает как сайт, PWA и Android-приложение (Bun, SQLite, Leaflet).
- [momp](https://github.com/domovoyproj/momp) — веб- и десктоп-клиент для Oh My Pi: русская локализация, мониторинг лимитов моделей, файловый менеджер поверх агентских сессий (Next.js, Tauri, Bun).
- [kyd](https://github.com/domovoyproj/kyd) 🔒 — трекер личных долгов с шестью стратегиями погашения (снежный ком, лавина и другие), симулятором сценариев и публичными профилями прогресса (Next.js, Prisma, PostgreSQL).
- [avito-parser](https://github.com/domovoyproj/avito-parser) — мониторинг объявлений Авито с оценкой выгодности лотов через LLM, веб-панелью и Telegram-ботом (FastAPI, Playwright).
- [suvc](https://github.com/domovoyproj/suvc) 🔒 — внутренняя система диспетчеризации для сети велопроката: аренда, акты приёма-передачи, инвентаризация, телематика, голосовые объявления (Bun, SQLite).
- [github-ru](https://github.com/domovoyproj/github-ru) — расширение для браузера, русифицирующее интерфейс GitHub и добавляющее пару удобных кнопок в шапку репозитория.

## Технологии

Rust, TypeScript, Python, JavaScript, Bun, Next.js, Tauri, Axum, Tokio, FastAPI, SQLite, PostgreSQL, Docker.

🔒 — приватный репозиторий