Cloud Quiz — версия для Vercel

1. Распакуй архив.
2. Создай репозиторий в GitHub и загрузи в его корень:
   vercel.json
   public/ (со всеми четырьмя файлами)
   README.txt (необязательно)
3. Vercel → Add New → Project → выбери этот репозиторий.
4. Framework Preset: Other. Root Directory: корень репозитория.
   Build Command: пусто. Output Directory: public.
   Эти параметры также заданы в vercel.json.
5. Нажми Deploy.

Не загружай ZIP вместо распакованных файлов.
Если загрузишь папку cloud-quiz-vercel целиком в репозиторий,
выбери её как Root Directory в Vercel.

Другой способ: открой терминал в папке с vercel.json и выполни:
npx vercel --prod

Сайт не требует сборки, npm install, сервера или переменных окружения.
Результаты сохраняются в браузере. На новом домене история результатов
начнётся заново, поскольку у каждого домена своё хранилище.
