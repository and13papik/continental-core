# 📤 Как загрузить Continental Core на GitHub

## Шаг 1️⃣: Создать репозиторий на GitHub

1. Перейди на [github.com](https://github.com)
2. Нажми **"+"** в верхнем углу → **"New repository"**
3. Заполни:
   - **Repository name**: `continental-core`
   - **Description**: `Shift Tracking Dashboard with Firebase sync`
   - **Public** ✓ (чтобы админы могли открыть)
4. Нажми **"Create repository"**

## Шаг 2️⃣: Загрузить файлы (через веб)

### Самый простой способ - через браузер:

1. На странице репозитория нажми **"Add file"** → **"Upload files"**
2. Перетащи или выбери эти файлы:
   - `continental_core.html`
   - `README.md`
   - `.gitignore`
3. Нажми **"Commit changes"**

## Шаг 3️⃣: Загрузить файлы (через Git - для опытных)

Если установлен Git:

```bash
# 1. Клонируй репозиторий
git clone https://github.com/YOUR_USERNAME/continental-core.git
cd continental-core

# 2. Добавь файлы в папку
# Скопируй сюда:
# - continental_core.html
# - README.md
# - .gitignore

# 3. Загрузи
git add .
git commit -m "Initial commit - Continental Core Dashboard"
git push origin main
```

## ✅ Готово!

Теперь админы могут открыть:
- **GitHub Raw ссылка**: 
  ```
  https://raw.githubusercontent.com/YOUR_USERNAME/continental-core/main/continental_core.html
  ```
  (Откроется прямо в браузере)

- **Или скачать файл**:
  ```
  https://github.com/YOUR_USERNAME/continental-core/blob/main/continental_core.html
  ```
  Нажми "Download raw file"

## 🚀 Опционально: GitHub Pages (для удобства)

Если хочешь чтобы был доступен по красивой ссылке:

1. Перейди в **Settings** → **Pages**
2. Выбери **Source**: `main` branch
3. Получишь ссылку: `https://YOUR_USERNAME.github.io/continental-core/`

## 📝 Для админов

Они просто открывают ссылку в браузере и всё работает:
- ✅ Синхронизация через Firebase
- ✅ Сохранение в localStorage
- ✅ Автоматические расчёты

Готово! 🎉
