# 📊 Fandom Activity Analysis & Engagement Forecast: "Love On Hire" (Copy A Bangkok)
### [ไทย] | [English] | [Русский] 

----
## 🇹🇭 [TH] รายงานการตลาด (ไทย)

### 🎯 วัตถุประสงค์ของโครงการ
การวิเคราะห์เชิงธุรกิจเกี่ยวกับกิจกรรมของฐานแฟนคลับต่างประเทศสำหรับซีรีส์ GL เรื่องใหม่ **"Love On Hire | รับจ้างเลิกรัก"** โดยใช้ข้อมูลจริงจากโซเชียลมีเดียเพื่อคาดการณ์ศักยภาพทางการค้าของโครงการ (ยอดขายสินค้าออฟฟิเชียล การจัดสรรความจุของสถานที่จัดงานแฟนมีตติ้ง)

### 📥 ขั้นตอนที่ 1: การเก็บรวบรวมข้อมูล (Scraping)
- **แหล่งข้อมูล:** YouTube (Teaser อย่างเป็นทางการ)
- **วิธีการ:** ใช้ Python และ BeautifulSoup ในการดึงข้อมูลเพื่อหลีกเลี่ยงข้อจำกัดของ API 
- **ขนาดตัวอย่าง:** รวบรวมและจัดโครงสร้างความคิดเห็นจริงจากแฟนคลับทั้งหมด **751 ความคิดเห็น**

### 🧠 ขั้นตอนที่ 2: KPI และการวิเคราะห์ความรู้สึก (Sentiment Analysis)
- **อัตราการมีส่วนร่วม (Engagement Rate - ER):** **4.25%** (เกณฑ์มาตรฐานอุตสาหกรรม > 3% ถือว่ายอดเยี่ยม) ฐานแฟนคลับถูกจัดอยู่ในกลุ่ม *ตื่นตัวสูงมาก (Hyperactive)*
- **ตัวชี้วัดความรู้สึก (โมเดล AI VADER):**
  - เชิงบวก / ตื่นเต้น: **30.1%** (ชื่นชมเคมีของคู่ GL และฉากตลกอย่างล้นหลาม)
  - เชิงปกติ (แฮชแท็ก / อีโมจิ): **61.3%** (แสดงถึงการรวมตัวที่เหนียวแน่นของแฟนคลับ มีการปั่นแฮชแท็กติดเทรนด์อย่างเป็นระบบ)
  - เชิงลบ / วิจารณ์: **8.6%** (ระดับความเห็นเชิงพิษต่ำมาก)

### 🛠️ เครื่องมือที่ใช้ (Tech Stack)
- **ภาษา:** Python 3
- **ไลบรารี:** Pandas, BeautifulSoup4, NLTK (VADER), Matplotlib, Seaborn
- **ระบบพัฒนางาน:** Jupyter Notebook


----

## 🇬🇧 [EN] Marketing Report (English)

### 🎯 Project Objective
Business analysis of the international fanbase activity for the new GL drama **"Love On Hire"** using real social media data to forecast the project's commercial potential (merchandise sales, fan-meeting venue capacity optimization).

### 📥 Phase 1: Data Collection (Scraping)
- **Source:** YouTube (Official Teaser)
- **Method:** Python-based web scraping using BeautifulSoup to bypass API restrictions and region blocks.
- **Sample Size:** **751 authentic fan comments** collected and structured.
### 🧠 Phase 2: KPI & Sentiment Analysis

- **Discovered Engagement Rate (ER):** **4.25%** (Industry benchmark > 3% is considered excellent). The fanbase is classified as *hyperactive*.
- **Sentiment Metrics (VADER AI Model):**
  - Positive / Excitement: **30.1%** (High praise for the GL couple's chemistry and comedic timing).
  - Neutral (Tags / Emojis): **61.3%** (Indicates high fanbase organization, massive hashtag trending behavior).
  - Negative / Criticism: **8.6%** (Extremely low toxicity level).

### 🛠️ Tech Stack
- **Language:** Python 3
- **Libraries:** Pandas, BeautifulSoup4, NLTK (VADER), Matplotlib, Seaborn.
- **Environment:** Jupyter Notebook.

----

## 🇷🇺 [RU] Маркетинговый отчет (Русский)

# 📊 Анализ Фандома и Прогноз Вовлеченности: Лакорн "Love On Hire" (Copy A Bangkok)

## 🎯 Цель проекта
Бизнес-анализ активности международной фан-базы новой GL-драмы **"Love On Hire"** на основе реальных данных из соцсетей для прогнозирования коммерческого потенциала проекта (продажи мерча, заполняемость залов на фан-митингах).

## 📥 Этап 1: Сбор данных (Парсинг)
- **Источник:** YouTube (Официальный тизер)
- **Метод:** Обход блокировок и сбор данных (Scraping) с помощью Python и BeautifulSoup без использования официального API.
- **Объем выборки:** Собрано и структурировано **751 реальный комментарий** фанатов.

## 🧠 Этап 2: KPI и Анализ тональности (Sentiment Analysis)
- **Выявленный Engagement Rate (ER):** **4.25%** (Индустриальный бенчмарк > 3% считается отличным). Фандом классифицирован как *сверхактивный*.
- **Метрики настроения (ИИ-модель VADER):**
- - Позитив/Восторг: **30.1%** (Высокий интерес к химии GL-пары и комедийным сценам).
  - Нейтрально (Теги/Смайлы): **61.3%** (Показатель высокой организованности фандома, массовый вывод тегов в тренды).
  - Критика: **8.6%** (Низкий уровень токсичности).

## 🛠️ Стек технологий
- **Язык:** Python 3
- **Библиотеки:** Pandas, BeautifulSoup4, NLTK (VADER), Matplotlib, Seaborn.
- **Среда разработки:** Jupyter Notebook.