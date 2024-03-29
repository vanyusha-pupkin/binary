# Проект «Binary»

---
## Ссылка на сайт - [https://vanyusha-pupkin.github.io/binary/](https://vanyusha-pupkin.github.io/binary/)

## Как использовать

`npm instal`        - установка зависимостей

`npm run build`     - финальная сборка проекта

`npm run start`     - режим: работа над проектом

`npm run deploy`    - публикация содержимого папки build на GitHub Page

`npm run testhtml`  - проверка html кода валидатором W3C


---

## Структура проекта

```bash
.
├── build/            # каталог сборки проекта (создаётся автоматически)
├── src/              # каталог для размещения исходных файлов проекта
│   ├── fonts/        # каталог шрифтов
│   ├── img/          # каталог растровых и векторных изображений
│   ├── js/           # каталог JS файлов
│   ├── scss/         # каталог файлов стилей
│   ├── html          # каталог файлов частей html страниц
│   └── index.html    # файл разметки страницы index.html
├── .gitignore        # файл исключений Git
├── .editorconfig     # файл с настройками для редактора
├── gulpfile.js       # файл gulpfile.js
├── package.json      # файл npm зависимостей и настроек проекта
├── package-lock.json # lock-файл npm
├── README.md         # документация проекта
```
