# Yaroslavna Soldatova — personal site

Одностраничный персональный сайт и CV-артефакты для `Yaroslavna Soldatova`.

## Что лежит в репозитории

- `index.html` — основная страница сайта
- `styles.css` — стили
- `script.js` — анимации появления блоков
- `assets/` — фото и актуальные версии CV
- `scripts/build_cv_docx.py` — генератор `.docx`-версии CV

## CV

Актуальные файлы:

- `assets/Yaroslavna-Soldatova-CV.pdf`
- `assets/Yaroslavna-Soldatova-CV.docx`

Кнопка `Скачать CV` на сайте ведет на PDF из `assets/`.

## Как пересобрать DOCX

Из корня проекта:

```bash
/Users/none/.cache/codex-runtimes/codex-primary-runtime/dependencies/python/bin/python3 scripts/build_cv_docx.py
```

После сборки файл обновится здесь:

```text
assets/Yaroslavna-Soldatova-CV.docx
```

## Git

Основная ветка репозитория: `main`.
