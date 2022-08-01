> **Название проекта**: _Путешествия по России_
> Общее:

    - одностраничный лендинг, реализация в html5, css;
    - расширения: editorconfig; normalize.css; nojekyll;
    - шрифты: 'Inter', 'Inter Black', в качестве альтернативы в page.css указаны 'Arial', sans-serif;
    - адаптивная верстка, заданы минимальная (320px) и максимальная (1280px) ширина страницы;
    - методология БЭМ: файловая структура NESTED;
    - кроссбраузерный код для opera, firefox, chrome, mozilla [https://autoprefixer.github.io/ru/];
    - код проверен валидатором [https://validator.w3.org/nu/#textarea]

---

> **Основное**:

- 3 основные зоны: header, content, footer;
- порядок отображения блоков в лендинге:
  - header
  - lead
  - intro
  - photo-grid
  - places
  - cover
  - footer;
- контент выровнен по сетке (флексбокс);
- блоки photo-grid и places выровнены при помощи grid;
- анимация ссылок задана превдоклассом hover,
  адреса ссылок прописаны везде, кроме меню выбора языка страницы в блоке header;
- подгонка изображений задана свойством object-fit c шириной 100%;
