# Коллекция CSS-сниппетов для настройки внешнего вида Obsidian

![](https://img.shields.io/github/v/release/LoocSiL/obsidian-ls-css-collection) ![](https://img.shields.io/github/release-date/LoocSiL/obsidian-ls-css-collection) ![](https://img.shields.io/github/license/LoocSiL/obsidian-ls-css-collection) ![](https://img.shields.io/github/downloads/LoocSiL/obsidian-ls-css-collection/total)

---

## О сборке

Репозиторий содержит CSS-сниппеты для кастомизации Obsidian. Сниппеты поддерживают настройку через плагин Style Settings.

**Файлы:**
- `LS_File Explorer - Background Pills.css` — цветовые плашки для файлов и папок
- `LS_File Explorer - File Type Colors.css` — цветовые метки для файлов по расширениям

---

## Установка

1. Скачайте `.css` файлы из [релизов](https://github.com/LoocSiL/obsidian-ls-css-collection/releases)
2. Поместите их в папку `.obsidian/snippets/` вашего хранилища
3. В Obsidian: `Настройки` → `Внешний вид` → `CSS-сниппеты` → `Обновить` и включите нужные

Для настройки параметров установите плагин [Style Settings](https://github.com/mgmeyers/obsidian-style-settings).

![Окно настройки](images/StyleSettings.png)

---

## Описание сниппетов

### LS File Explorer - Background Pills

Добавляет фоновые плашки (pills) для элементов проводника. Поддерживает два режима отображения:
- inline — плашка только под текстом
- full row — плашка на всю ширину строки

Дополнительно: иконки для папок и файлов, настройка скругления и отступов, перенос длинных названий.

[Полное описание сниппета](<docs/LS File Explorer - Background Pills.md>)

### LS File Explorer - File Type Colors

Раскрашивает названия файлов в проводнике в зависимости от расширения. Доступны категории:
- Файлы Obsidian (.md, .canvas, .excalidraw, .base)
- Вложения (PDF, изображения, видео, аудио)
- Внешние файлы (MS Office, код, остальные)

Для каждой категории можно настроить цвет и включение.

[Полное описание сниппета](<docs/LS File Explorer - File Colors.md>)

---

## Поддержка

Вопросы можно задать в Telegram: [excel_cad_bim_chat](https://t.me/excel_cad_bim_chat)  
Баги и предложения — через [Issues](https://github.com/LoocSiL/obsidian-ls-css-collection/issues)