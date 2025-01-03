# ChessMate Plugin для Obsidian

**ChessMate Plugin** — это плагин для [Obsidian](https://obsidian.md), который позволяет отображать шахматные партии и позиции в формате PGN и FEN прямо в ваших заметках. Плагин использует библиотеку `lichess-pgn-viewer` для рендеринга доски и фигур.

---

## Возможности

- **Отображение шахматных партий**:
  Используйте кодовые блоки с типом `chessmate`, чтобы визуализировать шахматные партии в формате PGN.

- **Кастомизация отображения**:
  Поддерживаются настройки темы доски, фигур и размера.

- **Поддержка шахматной нотации**:
  Воспроизводите и изучайте партии, добавляя текстовые аннотации и комментарии.

---

## Установка

### Автоматическая установка через менеджер плагинов Obsidian
1. Перейдите в раздел **Settings > Community Plugins**.
2. Нажмите **Browse** и найдите "ChessMate Plugin".
3. Установите и активируйте плагин.

### Ручная установка
1. Скачайте файлы `manifest.json`, `main.js` и `styles.css` из последнего релиза в [репозитории](#).
2. Поместите их в папку `.obsidian/plugins/chessmate-plugin/` вашего хранилища.
3. Перезагрузите Obsidian и активируйте плагин в разделе **Settings > Community Plugins**.

---

## Использование

### Отображение шахматной партии
Вставьте в вашу заметку следующий пример:
````
```chessmate
[Event "Пример партии"]
[Site "Obsidian"]
[Date "2024.12.01"]
[Round "?"]
[White "Player1"]
[Black "Player2"]
1. e4 e5 2. Nf3 Nc6 3. Bb5 a6 4. Ba4 Nf6 5. O-O Be7 6. Re1 b5
```
````
