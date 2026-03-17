# Сингулярность — Личный сайт ранобэ

## Как запустить сайт на GitHub Pages

1. Загрузи все файлы в репозиторий `ranobe`
2. Зайди в **Settings** → **Pages**
3. В разделе **Source** выбери ветку `main`, папку `/ (root)`
4. Нажми **Save**
5. Через 1-2 минуты сайт будет доступен по адресу:
   `https://dinea12303-ux.github.io/ranobe/`

## Как добавить новую главу

1. Скопируй файл `chapter.html` → переименуй в `chapter2.html`
2. Замени текст внутри `<div class="chapter-text">` на текст новой главы
3. Обнови заголовок главы (`.ch-label`, `.ch-title`)
4. В `index.html` добавь новую строку в список глав:

```html
<li class="chapter-item">
  <a href="chapter2.html">
    <span class="chapter-num">ГЛ. 2</span>
    <span class="chapter-title">Название главы</span>
    <span class="chapter-new">новая</span>
  </a>
</li>
```

5. Загрузи оба файла на GitHub — глава появится на сайте.

## Структура файлов

```
ranobe/
├── index.html       ← главная страница со списком глав
├── chapter.html     ← Глава 1
├── chapter2.html    ← Глава 2 (создашь сам)
└── README.md        ← эта инструкция
```
