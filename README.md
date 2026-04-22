# Neck Trainer — изометрика шеи

Тренажёр изометрических упражнений для шейного отдела. Адаптирован при грыже C5/C6.

## Деплой на Railway

### Через GitHub (рекомендуется)

1. Залей этот репозиторий на GitHub:
   ```bash
   git init
   git add .
   git commit -m "init"
   git remote add origin https://github.com/ТВО_ИМЕНО/neck-trainer.git
   git push -u origin main
   ```

2. Зайди на [railway.app](https://railway.app) → New Project → Deploy from GitHub repo

3. Выбери репозиторий `neck-trainer`

4. Railway автоматически определит Node.js и запустит `npm start`

5. Зайди в Settings → Generate Domain — получишь публичный URL

### Локальный запуск

```bash
npm install
npm start
```

Открой [http://localhost:3000](http://localhost:3000)

## Упражнения

- Давление вперёд
- Давление назад  
- Давление влево (осторожно — сторона грыжи)
- Давление вправо
- Chin tuck — подбородок назад

## Параметры по умолчанию

- Удержание: 10 сек
- Пауза: 4 сек
- Повторов: 6

Всё настраивается в интерфейсе.
