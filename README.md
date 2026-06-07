# QR Generator

Минималистичный генератор QR-кодов в браузере. Без серверов, без зависимостей npm — просто один HTML-файл.

## Возможности

- Генерация QR-кода из любого текста или URL
- Выбор размера: 128, 200, 256, 400 px
- Уровень коррекции ошибок: L / M / Q / H
- Произвольные цвета (цвет кода + фон)
- Скачивание в PNG одной кнопкой
- Работает полностью офлайн (после первой загрузки шрифтов)

## Использование

Просто открой `index.html` в браузере. Никаких сборщиков, никакого Node.js.

```
git clone https://github.com/<your-username>/qr-generator.git
cd qr-generator
open index.html   # macOS
# или просто перетащи файл в браузер
```

## Технологии

- [qrcodejs](https://github.com/davidshimjs/qrcodejs) — генерация QR через Canvas
- Google Fonts (Syne + Space Mono)
- Чистый HTML / CSS / JS, без фреймворков

## Лицензия

MIT
