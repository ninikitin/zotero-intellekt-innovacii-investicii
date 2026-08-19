# CSL-стили для журнала «Интеллект. Инновации. Инвестиции»

Стили [Citation Style Language](https://citationstyles.org/) для оформления библиографии в [Zotero](https://www.zotero.org/) по требованиям научного журнала **«Интеллект. Инновации. Инвестиции»** (ISSN 2077-7175, Оренбургский государственный университет).

## Что в репозитории

| Файл | Назначение |
|---|---|
| `intellekt-innovacii-investicii.csl` | Раздел **«Литература»** — ГОСТ Р 7.0.5-2008, числовые ссылки `[N]`, список по алфавиту. |
| `intellekt-innovacii-investicii-references-harvard.csl` | Раздел **«References»** — Harvard system of referencing (романизация/транслитерация). |

## Установка в Zotero

1. Скачайте нужный `.csl` (кнопка **Code → Download raw file** на странице файла, или **Raw** → сохранить как `*.csl`).
2. Zotero → **Настройки → Cite → Styles → «+»** → выберите скачанный файл.
3. В плагине Word/LibreOffice выберите стиль при вставке библиографии.

## Особенности

- Ссылки в тексте: `[5]`, `[9, с. 14]`, при перечислении — через точку с запятой `[5; 9]`.
- Список сортируется по алфавиту; номера `[N]` присваиваются по алфавитному порядку.
- Автоматически выводятся DOI, EDN (поле «Loc. in archive») и «дата обращения».
- Отступ первой строки (красная строка 1.25 см) задаётся в Word/LibreOffice через стиль абзаца «Список литературы» (в CSL это не настраивается).

Подробные инструкции по заполнению полей — в файлах `Инструкция*.md`.

## Лицензия

Стили распространяются под лицензией [Creative Commons Attribution-ShareAlike 3.0](http://creativecommons.org/licenses/by-sa/3.0/).
Файл `intellekt-innovacii-investicii.csl` создан на основе стиля [GOST R 7.0.5-2008 (numeric)](https://github.com/citation-style-language/styles/blob/master/gost-r-7-0-5-2008-numeric.csl) из официального репозитория CSL.
