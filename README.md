# Закрывающий тег

Финальный проект модулей вёрстки курса Яндекс Практикум.

## О проекте

Проект представляет собой рефлексию учебного пути в веб-разработке. Восемь карточек описывают разные этапы обучения - от первого знакомства с HTML и CSS до финального проекта с анимациями и сложной вёрсткой.

## Технологии

- HTML5 (семантическая разметка)
- CSS3 (Grid, Flexbox, CSS Variables, Animations)
- JavaScript (обработка событий, DOM-манипуляции)
- Адаптивная вёрстка
- CSS-фильтры для изображений
- SVG-анимации
- Вариативные шрифты (Inter Variable)

## Особенности реализации

- Анимированная иконка лайка с SVG
- Модальное окно на element `<dialog>`
- Прогрессивное улучшение через `@supports`
- Mix-blend-mode для эффектов кнопок
- Фиксированный фон с эффектом параллакса
- Fluid typography с использованием `clamp()`
- Accessibility атрибуты (ARIA, semantic HTML)

## Структура файлов

```
├── fonts/              # Вариативный шрифт Inter и Press Start 2P
├── images/             # Изображения карточек
├── scripts/            # JavaScript для like-функциональности
├── styles/
│   ├── globals.css     # CSS Reset
│   ├── variables.css   # CSS Custom Properties
│   ├── style.css       # Основные стили компонентов
│   └── animations.css  # Keyframe анимации
├── svg/                # SVG-иконки (floppy disk, heart)
└── index.html          # Главная страница
```

## Ссылки

Репозиторий проекта: https://github.com/AyratFaradzhov/zakrivayuschiy-teg-f.git

Проект опубликованный в gh-pages: https://ayratfaradzhov.github.io/zakrivayuschiy-teg-f/
