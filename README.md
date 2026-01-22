# **Обработка естественных языков**
**Задача:**
  Определение текста (классификация твитов по эмоциям).
  
  В работе использовался датасет, содержащий тексты сообщений и соответствующие им метки эмоций. (sadness (0), joy (1), love (2), anger (3), fear (4), and surprise (5))  
Датасет предварительно разделён на обучающую (`train.csv`), валидационную (`val.csv`) и тестовую (`test.csv`) выборки.

**Код:**

<img width="668" height="599" alt="image" src="https://github.com/user-attachments/assets/23b8baaf-6408-44df-921f-a376ab333ec0" />
<img width="553" height="535" alt="image" src="https://github.com/user-attachments/assets/34cfeebf-b0ee-4a42-a985-d1be2f8abd32" />
<img width="597" height="475" alt="image" src="https://github.com/user-attachments/assets/a0a1d6ef-584f-4f21-ac71-b19a59578ed7" />
<img width="1130" height="648" alt="image" src="https://github.com/user-attachments/assets/85e776a6-e7e6-4fa6-977f-425916e28e94" />
<img width="929" height="537" alt="image" src="https://github.com/user-attachments/assets/4777d00f-d554-4e56-9994-def468f59ea2" />
<img width="601" height="420" alt="image" src="https://github.com/user-attachments/assets/bedbdeb9-4134-462c-87c1-befc98816877" />
<img width="991" height="237" alt="image" src="https://github.com/user-attachments/assets/6bc64a38-d4df-454f-bc08-76ccb509728d" />
<img width="538" height="860" alt="image" src="https://github.com/user-attachments/assets/6cafa40e-b477-4ed6-af69-979467e79c75" />

**Задача:**
  N-грамм модели.
  
  Реализованы биграммные и триграммные модели, проведена оценка качества с использованием перплексии и выполнена генерация текста.
  
**Код:**

<img width="671" height="602" alt="image" src="https://github.com/user-attachments/assets/b57919ab-ecee-4b80-a376-74d5772cd843" />
<img width="494" height="557" alt="image" src="https://github.com/user-attachments/assets/76402119-8401-4619-9686-222eaa89cc7a" />
<img width="599" height="578" alt="image" src="https://github.com/user-attachments/assets/016ec580-9558-4c1b-9f69-af6b0ecf9088" />
<img width="1317" height="596" alt="image" src="https://github.com/user-attachments/assets/b8660dfd-c555-4f0e-a0bd-a0280fbb9584" />
<img width="725" height="551" alt="image" src="https://github.com/user-attachments/assets/455d0e45-55d6-48a6-8986-9c4e61fb73ec" />
<img width="436" height="545" alt="image" src="https://github.com/user-attachments/assets/d260eb76-59dc-4de5-b4ac-02482e1938e8" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/6c9a8e6b-e5de-46da-8217-29c64dca1be6" />

**Задача:**
  Определение частей речи в тексте.
  
  В работе используется библиотека pymorphy3, реализующая алгоритмы морфологического анализа русского языка. В результате морфологического анализа было установлено, что в тексте преобладают существительные.
  
**Код:**

<img width="1526" height="551" alt="image" src="https://github.com/user-attachments/assets/40c04e8d-8dde-457d-bae3-1c18678447ce" />
<img width="1125" height="457" alt="image" src="https://github.com/user-attachments/assets/d35e499b-682d-4365-9adf-dff1a1d8a28d" />
<img width="312" height="615" alt="image" src="https://github.com/user-attachments/assets/33922fad-8971-4f75-be2c-e11f9ad6b220" />
<img width="870" height="634" alt="image" src="https://github.com/user-attachments/assets/711dc63e-8f47-48cd-a497-fb9ef8713c80" />

**Задача:**
  Грамматический разбор текста.
  
  В данной работе выполнен грамматический разбор русского текста с использованием библиотеки spacy и модели ru_core_news_sm. Разбор включает: морфологический анализ (часть речи, лемма, грамматические признаки), синтаксический анализ (зависимости между словами), визуализацию синтаксического дерева.
  
**Код:**

<img width="1538" height="704" alt="image" src="https://github.com/user-attachments/assets/0d8ae6a7-ef36-402f-9a38-70095a6a812f" />
<img width="826" height="463" alt="image" src="https://github.com/user-attachments/assets/69208312-2605-4609-85f6-658b2c8ed575" />
<img width="559" height="605" alt="image" src="https://github.com/user-attachments/assets/c618bc6c-25df-455e-982d-ebb1b210f086" />
<img width="1683" height="683" alt="image" src="https://github.com/user-attachments/assets/3db62ad5-1801-4f18-b894-0f5109d460b5" />


















