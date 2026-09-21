# Veronika Albero — портфолио

Все файлы лежат в одной папке, без вложенных: `index.html` и 18 фотографий рядом с ним.

## Загрузка на Vercel через GitHub

1. Создайте репозиторий на GitHub и загрузите в его **корень** все файлы из этой папки (index.html + все .jpg).
2. Vercel → **Add New → Project → Import** этот репозиторий.
3. Настройки:
   - Framework Preset: **Other**
   - Build Command: пусто
   - Output Directory: пусто
   - Install Command: пусто
4. **Deploy**. Дальше каждый push в `main` обновляет сайт.

## Важно

- Файлы нельзя переименовывать и раскладывать по подпапкам — пути прописаны в `index.html`.
- Форма в блоке Contact открывает почтовый клиент с готовым письмом. Нужна отправка прямо с сайта — подключается Formspree.
- Домен: Vercel → Project → Settings → Domains.
