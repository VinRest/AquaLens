# AquaLens Case — GitHub Pages

Портативная система обнаружения микропластика.

## Публикация на GitHub Pages

### Вариант 1 — через браузер (самый простой)

1. Зайди на [github.com](https://github.com) → **New repository**
2. Назови репозиторий, например: `aqualens`
3. Сделай его **Public**
4. Нажми **Create repository**
5. Нажми **Add file → Upload files**
6. Перетащи файл `index.html`
7. Нажми **Commit changes**
8. Перейди в **Settings → Pages**
9. В разделе **Source** выбери ветку `main`, папку `/ (root)` → **Save**
10. Через ~1 минуту сайт будет доступен по адресу:
    ```
    https://<твой-username>.github.io/aqualens/
    ```

---

### Вариант 2 — через Git CLI

```bash
git init
git add index.html README.md
git commit -m "Initial commit: AquaLens landing page"
git branch -M main
git remote add origin https://github.com/<username>/aqualens.git
git push -u origin main
```

Затем включи GitHub Pages в **Settings → Pages → Source: main / root**.

---

## Файлы

| Файл | Описание |
|------|----------|
| `index.html` | Весь сайт в одном файле (HTML + CSS + JS) |

Сайт не требует сборщика, Node.js или зависимостей — работает как есть.
