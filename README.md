# КП 2.3 — TaskFlow
Vue 3 + Framework7 + Vite + PWA + Cloudflare Workers.

## Запуск (Windows, cmd у папці проєкту)
```
npm install
npm run dev
```
Відкрити http://localhost:5173/

## Збірка
```
npm run build
npm run preview
```

## GitHub
Створити порожній репозиторій taskflow-demo, потім в папці проєкту:
```
git init
git branch -M main
git add .
git commit -m "Initial commit: TaskFlow Demo PWA"
git remote add origin https://github.com/ВАШ_ЛОГІН/taskflow-demo.git
git push -u origin main
```
НЕ завантажуйте `node_modules`, `dist`, секрети `.env`.

## Cloudflare Workers
Create application -> Continue with GitHub -> repository -> Build `npm run build`, Deploy `npx wrangler deploy`, root `/`, branch main.
URL Workers: https://...workers.dev

Нотатка: для звіту потрібні скриншоти головної, "Про застосунок", GitHub, Cloudflare, Manifest/Service Worker.
