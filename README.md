<p align="center">
  <img src="assets/banner.png" alt="Vladislav — Fullstack Engineer" width="100%" />
</p>

# Владислав

Backend / fullstack-разработчик: Node.js и TypeScript. Делаю серверные системы, интеграции с внешними API, Telegram-приложения и автоматизацию. Кишинёв.

### Как я работаю

- **Изменения — через PR**: в описании проблема, решение, чем проверено и что сознательно отложено.
- **Решения записываю** в журнал (ADR): контекст, отвергнутые варианты, цена решения.
- **Тестирую поведение, а не строки**: e2e на настоящей базе, проверка, что тест ловит регрессию.
- **Безопасность по умолчанию**: доступ к данным ограничен владельцем, секреты только в окружении, конфигурация проверяется при старте.
- **Строгие типы и CI**: `strict` TypeScript, линтер без warning, сборка и тесты на каждый PR.

### Проекты

| Проект | О чём | Стек |
|---|---|---|
| [**Capy**](https://github.com/akoody/Capy) | Telegram Mini App для личных финансов с голосовым ассистентом. Модульный монолит, доступ к данным по владельцу, LLM-провайдеры с fallback, e2e на MongoDB, [журнал решений](https://github.com/akoody/Capy/tree/main/docs/adr) | NestJS, MongoDB, React |
| [**Pitch Signal**](https://github.com/akoody/pitch-signal) | Объяснимая аналитика футбольных трендов: угловые, карточки, фолы, удары. Монорепо: API, веб, доменное ядро и адаптеры провайдеров данных | Fastify, PostgreSQL, React |
| [**Tracecase**](https://github.com/akoody/tracecase) | Расследование инцидентов в бэкенде с доказательствами: локальные инструменты, воспроизводимые сценарии отказов и набор оценок | TypeScript, pnpm workspaces |
| [**OrderHub**](https://github.com/akoody/orderhub) | Сервис заказов и платежей: идемпотентность запросов и доставка событий через outbox | TypeScript, PostgreSQL, Prisma |
| [**Verde Market**](https://github.com/akoody/verde-market) | Маркетплейс фермерских продуктов: заказы у нескольких продавцов, кабинет фермера и модерация, транзакции MongoDB, защита от повторного списания | Next.js, MongoDB |
| [**TransCheck Bot**](https://github.com/akoody/transcheck-bot) | Мониторинг USDT-переводов в BEP20 и TRC20: RPC с резервными пулами, ретраи, обработка лимитов | Node.js, Telegram Bot API |

### Стек

**Backend:** Node.js, TypeScript, NestJS, Fastify, Express · **Данные:** PostgreSQL, MongoDB, Redis, Prisma · **Frontend:** React, Next.js, Vite · **Инфраструктура:** Docker, GitHub Actions, nginx

### Связь

[Telegram](https://t.me/akoodyy) · [vladislav.c282005@gmail.com](mailto:vladislav.c282005@gmail.com) · [vladislavc.online](https://vladislavc.online)
