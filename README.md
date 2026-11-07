# Scrolly: лендинг

React + Vite. Есть переключатель темы «день / ночь» (запоминается в браузере).

## Запуск

```bash
npm install
npm run dev      # разработка, http://localhost:5173
npm run build    # сборка в папку dist
```

## Публикация на GitHub Pages

1. Загрузите все файлы этого проекта в репозиторий (ветка `main`).
2. Settings → Pages → Source: **GitHub Actions**.
3. После пуша workflow `Deploy to GitHub Pages` соберёт сайт и опубликует его.

Если не хотите собирать: готовая сборка лежит в архиве `scrolly-dist.zip`, её файлы кладутся в корень репозитория, а в Pages выбирается ветка `main` и папка `/ (root)`.
