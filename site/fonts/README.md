# Шрифты сайта

`index.html` подключает Old Standard TT из этой папки:

- `OldStandardTT-Regular.woff`
- `OldStandardTT-Italic.woff`
- `OldStandardTT-Bold.woff`

Шрифт бесплатный (лицензия OFL, автор Алексей Крюков), скачать его можно на Google Fonts. Google отдаёт `.ttf`: либо переведите файлы в woff, либо замените в начале `index.html` расширения в `src: url(...)` на `.ttf` и `format("truetype")`.
