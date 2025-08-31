# SubtleGram 🎬

Интерактивный анализатор субтитров для изучения английского языка. Загружайте субтитры, кликайте на фразы и получайте детальный анализ с объяснениями сленга, идиом и грамматики.

![Nuxt](https://img.shields.io/badge/Nuxt-4-00DC82?style=for-the-badge&logo=nuxt.js&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-3-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 🚀 Стек технологий

### Frontend
- **Nuxt 4** - Vue.js фреймворк с SSR/SSG
- **Vue 3** - Прогрессивный JavaScript фреймворк
- **TypeScript** - Типизированный JavaScript
- **Tailwind CSS** - Utility-first CSS фреймворк
- **Pinia** - Современное управление состоянием для Vue

### Архитектура
- **Feature-Sliced Design (FSD)** - Архитектурная методология
- **Монолитный frontend** - Vue.js приложение

## 📁 Структура проекта

```
subtleGram/
├── front/                 # Nuxt приложение
│   ├── src/
│   │   ├── app/          # Приложение (layouts, providers, styles)
│   │   ├── entities/     # FSD: бизнес-сущности
│   │   ├── features/     # FSD: функциональности
│   │   ├── shared/       # FSD: переиспользуемый код
│   │   └── pages/        # Страницы приложения
│   ├── nuxt.config.ts    # Конфигурация Nuxt
│   ├── tailwind.config.ts # Конфигурация Tailwind
│   └── package.json      # Зависимости frontend
└── back/                 # Backend (планируется)
    └── ...              # Express API сервер
```

## ✨ Основные возможности

- 📄 Загрузка SRT файлов - Поддержка стандартных субтитров
- 🎯 Интерактивный анализ - Кликабельные фразы и предложения
- 🤖 ИИ объяснения - Детальный разбор грамматики и значений
- 🔍 Поиск по субтитрам - Быстрый поиск нужных моментов
- 📱 Responsive дизайн - Работает на всех устройствах
- ⚡ Гибридная обработка - Фоновый анализ для ускорения

## 🛠 Установка и запуск

### Frontend
```bash
cd front
npm install
npm run dev
```

Приложение будет доступно на http://localhost:3000

### Сборка для продакшена
```bash
npm run build
npm run preview
```

## 📝 Roadmap

- [ ] Базовая структура проекта ✅
- [ ] Парсинг SRT файлов
- [ ] ИИ анализ фраз
- [ ] Интерактивный UI
- [ ] Поиск по субтитрам
- [ ] Мобильная версия
- [ ] Кэширование анализов

## 🤝 Contributing

Проект находится в активной разработке. Pull requests приветствуются!

## 📄 License

MIT License
