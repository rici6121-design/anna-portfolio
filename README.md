# Анна Кожевникова — портфолио

Одностраничный сайт с видео по скроллу и ноутбуком с кейсами.

## Автосборка

При каждом push в `main` запускается workflow `.github/workflows/pages.yml`:

1. checkout
2. проверка `index.html`
3. выкладка на GitHub Pages

Сайт: https://rici6121-design.github.io/anna-portfolio/

Actions: https://github.com/rici6121-design/anna-portfolio/actions

### Первый раз включить Pages

1. Settings → Pages → Source: **GitHub Actions**.
2. Залейте папки `videos/` и `img/` в корень репозитория.
3. Actions → Deploy Pages → Run workflow.

## Локально

```bash
cd site
python3 -m http.server 8080
```
