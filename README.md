# Проект: Оно тебе надо — аукцион вещей, в которые никто не верил

[![GitHub branch](https://img.shields.io/badge/Branch-main-blue)](https://github.com/Alex-Ven/ono-tebe-nado)

## Описание
Этот проект представляет собой веб-сайт аукциона "Оно тебе надо", посвящённого уникальным лотам, которые когда-то считались неудачными или недооценёнными. Сайт демонстрирует базовую структуру HTML-документа и стилизацию с помощью внешних CSS-файлов.

Цель проекта — создать привлекательный и функциональный интерфейс для представления культовых вещей, которые стали значимыми в современной культуре.

## Структура проекта
```
project/
├── index.html          # Основной HTML-файл
├── fonts/
│   └── fonts.css       # Файл с настройками шрифтов
├── styles/
│   ├── global.css      # Глобальные стили
│   └── style.css       # Основной файл стилей
└── images/
    ├── logo-black.svg  # Логотип проекта (чёрный)
    ├── logo-white.svg  # Логотип проекта (белый)
    ├── yt.svg          # Иконка YouTube
    ├── vk.svg          # Иконка ВКонтакте
    └── pinterest.svg   # Иконка Pinterest
```

## Как использовать

### 1. Установка
Для запуска проекта не требуется установка дополнительных зависимостей. Просто склонируйте репозиторий или скачайте файлы проекта.

```bash
git clone https://github.com/Alex-Ven/ono-tebe-nado.git
cd ono-tebe-nado
```

### 2. Запуск
Откройте файл `index.html` в любом современном браузере (например, Google Chrome, Firefox, Safari). Для этого можно:
- Дважды щелкнуть на файл `index.html` в проводнике.
- Или перетащить файл в окно браузера.

### 3. Настройка
Если вы хотите изменить внешний вид сайта:
- Отредактируйте файл `styles/style.css`, чтобы изменить основные стили элементов.
- Отредактируйте файл `styles/global.css`, чтобы изменить глобальные стили.
- Отредактируйте файл `fonts/fonts.css`, чтобы изменить шрифты.

### 4. Добавление контента
Чтобы добавить новый контент на сайт:
- Откройте файл `index.html` в текстовом редакторе (например, VS Code).
- Добавьте или измените HTML-элементы внутри тега `<body>`.

## Файлы проекта

### `index.html`
Основной HTML-файл, содержащий структуру веб-страницы. Включает ссылки на внешние CSS-файлы (`fonts/fonts.css`, `styles/global.css`, `styles/style.css`) и изображения из папки `images`.

Пример содержимого:
```html
<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Оно тебе надо — аукцион вещей, в которые никто не верил</title>
    <link rel="stylesheet" href="./fonts/fonts.css" />
    <link rel="stylesheet" href="./styles/global.css" />
    <link rel="stylesheet" href="./styles/style.css" />
  </head>
  <body>
    <header class="header">
      <!-- Шапка сайта -->
    </header>
    <main>
      <!-- Основной контент -->
    </main>
    <footer class="footer">
      <!-- Подвал сайта -->
    </footer>
  </body>
</html>
```

### `fonts/fonts.css`
Файл, отвечающий за настройку шрифтов. Здесь можно подключить веб-шрифты (например, через Google Fonts) или задать параметры шрифтов для всего сайта.

Пример содержимого:
```css
/* Подключение Fonts */
@font-face {
  font-family: Raleway;
  src:
    url(./Raleway-Regular.woff2) format('woff2'),
    url(./Raleway-Regular.woff) format('woff');
  font-weight: normal;
  font-display: swap;
}

/* Настройка шрифтов */
body {
  font-family: Raleway, sans-serif;
}
```

### `styles/global.css`
Глобальные стили для всего проекта. Здесь можно настроить общие параметры, такие как цвет фона, отступы, шрифты и другие свойства.

Пример содержимого:
```css
/* Общие стили */
body {
  width: 1100px;
  margin: 0 auto;

a {
  color: inherit;
}
```

### `styles/style.css`
Основной файл стилей, который определяет внешний вид элементов страницы. Здесь можно настроить цвета, отступы, размеры и другие свойства.

Пример содержимого:
```css
/* Заголовок */
header {
  display: grid;
  grid-template-columns: 3fr 1fr 3fr;
  gap: 10px;
  justify-items: end;
  align-items: center;
  padding: 94px 24px;
}

/* Футер */
.footer {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: flex-start;
  padding: 93px 50px 100px 50px;
}
```

### `images/`
Папка содержит изображения, используемые на сайте:
- `logo-black.svg`: Чёрная версия логотипа проекта.
- `logo-white.svg`: Белая версия логотипа проекта.
- `yt.svg`: Иконка YouTube.
- `vk.svg`: Иконка ВКонтакте.
- `pinterest.svg`: Иконка Pinterest.

## Лицензия
Этот проект распространяется под лицензией [MIT](LICENSE). Вы можете свободно использовать, изменять и распространять код.

## Автор
Автор проекта: Alexander Venedyukhin  
Контакты: [vened.alex@gmai.com](mailto:vened.alex@gmai.com)  
GitHub: [Alex-Ven](https://github.com/Alex-Ven)

---