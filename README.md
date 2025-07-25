# 🧾 Техническое задание

## Позиция: React Developer (Frontend Developer)
**Формат работы:** Удалённо (полная или частичная занятость)  
**Компания:** Era Developers Studio

---

## 🎯 Цель задания
Разработать прототип панели управления чат-ботами — одностраничное приложение (SPA), демонстрирующее навыки кандидата в работе с современным фронтенд-стеком и архитектурными подходами.

---

## ⚙️ Технические требования

### 📌 Стек технологий:
- React.js (18+)
- Next.js (13+) с App Router
- TypeScript
- zustand или Redux Toolkit
- CSS Modules / SCSS или Tailwind CSS
- SSR (Next.js или Vite SSR)
- (опционально) Astro

---

## 📐 Функциональность

1. **Главная страница**
   - Список чат-ботов с названием, описанием, статусом.
   - Переход к странице конкретного бота по маршруту `/bot/[id]`.

2. **Создание нового бота**
   - Страница или модальное окно с формой (React Hook Form или аналог).
   - Обязательная валидация полей.

3. **Редактирование бота**
   - Возможность редактировать параметры существующего бота.
   - Данные сохраняются в глобальное состояние или мок-API.

4. **Хранилище состояния**
   - Использовать zustand или Redux Toolkit.
   - Имитировать API (моки или in-memory хранилище).

5. **Обработка ошибок и загрузок**
   - Индикация загрузки и ошибок при запросах или действиях.

---

## 🧩 Архитектура проекта

- Использование методологии Feature-Sliced Design (FSD) (если есть опыт).
- Алиасы: `@app`, `@pages`, `@widgets`, `@features`, `@entities`, `@shared`.
- Разделение бизнес-логики, компонентов, UI и API.

---

## 🎨 UI/UX требования

- Современный минималистичный интерфейс.
- Можно использовать UI-библиотеки: AntDesign
- Удобная и логичная навигация.
- Корректная типизация всех компонентов.
- Семантичная верстка, внимание к доступности.

---

## ✅ Критерии оценки

- Чистота и читаемость кода.
- Архитектура и структура проекта.
- Использование современных best practices.
- Типизация и переиспользуемость компонентов.
- Работа с состоянием и навигацией.
- Уровень реализации UX и UI.

---

## 📤 Что предоставить:

- Ссылка на репозиторий (GitHub, GitLab и т.д.)
- README: краткое описание проекта, инструкция по запуску
- (Опционально) Ссылка на деплой (Vercel, Netlify и др.)
