# Портфолио Андрея

Статический сайт-портфолио (HTML, CSS, JavaScript). Сборка не нужна.

## Структура
- `index.html` — страница
- `styles.css` — стили
- `script.js` — прокрутка, подсветка меню, просмотр фото
- `quiet-residence.jpg`, `linea-apartment.jpg`, `casa-terra.jpg` — фотографии проектов (лежат в корне, их нужно загрузить вместе с остальными файлами)
- `vercel.json` — настройки Vercel

## Запуск локально
Откройте `index.html` в браузере или выполните `npx serve .`

## Публикация на GitHub
1. Создайте на github.com новый репозиторий (например `portfolio`).
2. В папке проекта выполните:
   ```
   git init
   git add .
   git commit -m "Первая версия портфолио"
   git branch -M main
   git remote add origin https://github.com/ВАШ_ЛОГИН/portfolio.git
   git push -u origin main
   ```
   Или нажмите «Add file → Upload files» в репозитории и перетащите все файлы.

## Публикация на Vercel
1. Зайдите на vercel.com и войдите через GitHub.
2. «Add New → Project», выберите репозиторий.
3. Framework Preset: **Other**. Build Command и Output Directory оставьте пустыми.
4. Нажмите **Deploy**. Через минуту сайт будет доступен по ссылке вида `https://portfolio-xxxx.vercel.app`.

Каждый `git push` в `main` автоматически обновляет сайт.

## Что поправить перед отправкой работодателю
- Добавьте в `index.html` свои реальные интерьерные работы, когда они появятся.
- Проекты Quiet Residence, Linea Apartment и Casa Terra помечены как демонстрационные. Не выдавайте их за выполненные заказы.
- Укажите только те навыки, которыми действительно владеете.
