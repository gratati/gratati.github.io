# Мой персональный сайт

👋 Добро пожаловать на моё цифровое пространство — здесь сходятся **NLP, computer vision, AI-инструменты для бизнеса** и **генеративная музыка как поэтическая практика**.

🌐 Сайт: [https://gratati.github.io](https://gratati.github.io)

---

## 📂 Проекты

### 🤖 [TextEaseBot](https://t.me/TextEaseBot)  
Telegram-бот для упрощения, перевода и критического анализа текстов. Создан как инструмент **осознанного чтения**, а не просто автоматизации.

#### ✅ Возможности:
- Упрощение на 2 уровнях: *средний* и *сильный*  
- Перевод с русского на английский (Helsinki-NLP)  
- Режим **«Фактчекинг»**: разбивка текста на утверждения + оценка достоверности  
- Поддержка `.txt` и `.docx`  
- Пост-обработка: исправление типичных грамматических артефактов  
- Этичные warning’ы об ограничениях ИИ  

#### ⚙️ Технологии:
- **Модель упрощения**: дообученный `RuT5` (хранится на [Яндекс.Диске](https://disk.yandex.ru/d/GcR3ougL6bY6kw))  
- **Эмбеддинги**: `BERT` (для точного сравнения оригинала и упрощённого текста)  
- **Инструменты**: `python-telegram-bot`, `Transformers`, `NLTK`, `spaCy`, `Helsinki-NLP`  
- **Оценка качества**: BLEU, Levenshtein, сравнение длины  

🔗 [GitHub](https://github.com/gratati/TextEaseBot) | 📬 [Попробовать в Telegram](https://t.me/TextEaseBot)  
📄 [Демо (PDF)](/docs/texteasebot.pdf)

> 📝 **Философия**:  
> *«TextEaseBot — это не замена мышлению, а его зеркало. Он не отвечает “что написано”, а помогает спросить: “а правда ли это?”»*

---

### 📊 Анализ тональности  
Веб-приложение для массового анализа отзывов, постов и комментариев — с кластеризацией по скрытым эмоциональным паттернам.

🛠 **Технологии**: `BERT`, `Scikit-learn`, `KMeans`, `Streamlit`  
🔗 [GitHub](https://github.com/gratati/sentiment-analyzer)  
📄 [Демо (PDF)](/docs/анализ_тональности.pdf)

> ⚠️ Демо временно недоступно на Streamlit Cloud.

---

### 🖼️ CV-сегментация игрового поля  
Автоматическая разметка спортивных площадок (футбол, баскетбол) на видео — без ручного труда.

🛠 **Технологии**: `Segment Anything (SAM)`, `U-Net`, `OpenCV`, `Flask`  
🔗 [GitHub](https://github.com/gratati/cv-segmentation-sam-unet) | 🌐 [Демо (Render)](https://cv-segmentation.onrender.com)  
📄 [Демо (PDF)](/docs/cv_segmentation_sam_unet.pdf)

---

### 📱 realtime_object (Android)  
Offline-детекция объектов через камеру и видео из галереи — без интернета, с минимальной задержкой.

🛠 **Технологии**: `Kotlin`, `TensorFlow Lite`, `Camera2 API`, `Firebase`  
🔗 [GitHub](https://github.com/gratati/realtime_object)  
📄 [Демо (PDF)](/docs/object-detection.pdf)

> ✅ Поддержка 80+ классов (люди, животные, транспорт, предметы)  
> 📱 Требуется Android 5.0+  

---

### 📝 AI конструктор документов по шаблону  
Генерация служебных записок, писем, КП и др. по структуре **«проблема → решение»** — быстро, без ошибок, с единым стилем.

🛠 **Технологии**: `Google AI Studio`, `Generative AI`, `Business Process Templates`  
🔗 [Открыть в Google AI Studio](https://aistudio.google.com/apps/drive/1WR-teFQnjFsi54En8GpRjjPux_sUlhAP?showAssistant=true&showPreview=true)  
📄 [Демо (PDF)](/docs/AI%20Constructor.pdf)

---

### 🎧 [Slovolov AI транскрибатор](https://huggingface.co/spaces/Gratati/slovolov-app)  
Транскрибация аудио/видео в текст: загружай файл или YouTube-ссылку — получи готовый текст.

🛠 **Технологии**: `Python`, `Gradio`, `Whisper`, `Hugging Face Spaces`  
🔗 [Hugging Face Space](https://huggingface.co/spaces/Gratati/slovolov-app)  
📄 [Демо (PDF)](/docs/Slovolov_app.pdf)

> ⚠️ HF не поддерживает прямую обработку YouTube — требуется предзагрузка файла. Скорость зависит от CPU/GPU.

---

## 🎵 AI-музыка  
Генеративные треки через [Producer.ai](https://producer.ai) — цифровые ритуалы, медитации, поэтические исследования звука.

| Трек | Жанр | Особенности |
|------|------|-------------|
| **Mystica** | Ritual Ambient · Hang Drums · Whisper Vocals | Медитативный ритуал, инструмент без слов |
| **Mysterious Tide** | Trip-hop · Chillout · Hawaiian Lap Steel | Меланхоличный дрейф, теплые гитары |
| **Flight of Life** | Psychedelic Rock · Swirling Organ | Энергичный полёт, атмосфера 1979 г. |
| **Dance Queen** | Urban Beats · Warm Piano | Городская энергия, тёплая грация |
| **Shadows and Flame** | Epic Symphonic Rock · Choir | Кинематографичный масштаб, борьба теней и света |
| **Roots in the Sky** | Ethno Fusion · Duduk · RU Ritual Vocals | Земные корни и небесные ветви, голос из сна |
| **Carnival Drift** | Synthwave · Neon Groove · Retro-Futurism | Ночной город, неон, воспоминания из будущего |
| **Яблоко в руке** | **Art Pop · Trip-Hop · Ethereal Russian Poetry** | 🍎 *Трек о простоте как чуде: осень, чай, яблоко — целый мир в мелочах.* Лирика — полный цикл (куплеты–припев–бридж–аутро). |
| **Code of Desire** | **Industrial Glitch Electro-Pop · Dark Ambient · Cyber-Mystic** | 💻 *«Глитч-ведьма на границе ночи»* — метафора цифрового самовыражения. Строка `if (desire) { play(); }` — манифест тела и кода. |

🎧 Все треки доступны для прослушивания прямо на сайте.

---

## 📄 Демонстрации (PDF)
- `/docs/texteasebot.pdf`
- `/docs/cv_segmentation_sam_unet.pdf`
- `/docs/анализ_тональности.pdf`
- `/docs/object-detection.pdf`
- `/docs/AI%20Constructor.pdf`
- `/docs/Slovolov_app.pdf`

---

## 🛠️ Стек

| Категория | Инструменты |
|----------|-------------|
| **Языки** | Python, Kotlin, JavaScript |
| **NLP / GenAI** | RuT5, BERT, Whisper, Helsinki-NLP, Google AI Studio |
| **CV / ML** | SAM, U-Net, TensorFlow Lite, PyTorch, OpenCV |
| **Фронтенд** | HTML/CSS/JS, Streamlit, Gradio, Flutter |
| **Бэкенд** | Flask, Firebase |
| **Инфра** | Hugging Face Spaces, Render, Docker, GitHub Pages |

---

## 🌍 Запуск локально

```bash
git clone https://github.com/gratati/gratati.github.io.git
cd gratati.github.io
# Откройте index.html в браузере (двойной клик или)
open index.html

📁 Для воспроизведения музыки:
Обложки: music/*.jpg
Аудио: music/audio/*.mp3
(включая Яблоко в руке.mp3, Carnival Drift.mp3, Code of Desire.mp3)

📬 Контакты

Telegram: @mentvork
Email: gratati49@gmail.com
GitHub: github.com/gratati
© 2025 gratati
«Пишу код, который думает — и музыку, которая чувствует» 🌿
