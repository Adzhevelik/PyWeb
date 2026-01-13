# Отчет по заданию 2.2

## Выполненные задачи

### 1. Кастомная тема

Создана собственная тема с использованием HTML, CSS, JavaScript и Jinja2.

Структура:
- `custom_theme/main.html` - основной шаблон
- `custom_theme/partials/header.html` - header
- `custom_theme/partials/footer.html` - footer
- `custom_theme/assets/css/custom.css` - стили
- `custom_theme/assets/js/custom.js` - скрипты

Дизайн: розовая цветовая схема, флэт-дизайн, овальные формы.

### 2. Метаданные

Добавлены мета-теги в `main.html`:
- description
- author
- keywords

### 3. Автоматизация сборки

Настроен GitHub Actions workflow для:
- Минификации CSS через PostCSS
- Минификации JS через Terser
- Сборки сайта через MkDocs
- Деплоя на GitHub Pages

Файлы конфигурации:
- `package.json` - npm зависимости и скрипты
- `postcss.config.js` - настройки PostCSS
- `.github/workflows/deploy.yml` - пайплайн CI/CD

## Результат

Сайт: https://adzhevelik.github.io/PyWeb/

Репозиторий: https://github.com/Adzhevelik/PyWeb

## Технологии

Python 3.11, MkDocs, HTML5, CSS3, JavaScript, PostCSS, Terser, GitHub Actions, GitHub Pages