# RATZ-10-11-2024

<div align="center">Система классификации электрокортикограмм</div>

### ⭐ Описание

Данная **Система классификации электрокортикограмм** предназначена для автоматического анализа и распознавания ритмической активности мозга во время сна. Она помогает ускорить процесс анализа за счет автоматизации, что существенно уменьшает временные затраты, связанные с ручной разметкой данных.

Проект создан для изучения и классификации различных фаз сна у лабораторных крыс, используя искусственный интеллект, что позволяет обнаружить и изучить уникальные особенности ритмической активности мозга.

### ❗ Проблематика

1. Изучение особенностей ритмической активности головного мозга во время сна.
2. Времязатратность ручной разметки данных.
3. Необходимость в использовании ИИ для автоматизации процессов анализа и классификации.

### 💻 Технологический стек

Проект разработан на языке *Python* и использует следующие библиотеки и фреймворки:
- **Streamlit** — для создания пользовательского интерфейса.
- **KERAS** — для построения и обучения модели нейронной сети.
- **Pandas** и **Scikit-Learn** — для работы с данными и их предобработки.
- **MNE-Python** — для анализа и обработки сигналов EEG.

### 📊 Данные

- **Количество объектов**: 51 800 000 записей электрокортикограмм.
- **Разделение данных**:
  - **Обучающая выборка**: данные 5 классов крыс (800 000 записей).
  - **Валидационная выборка**: данные 1 класса крыс (200 000 записей).
  - **Тестовая выборка**: крыса "золотой стандарт" для тестирования модели.
  
### 🤖 Модель

Для классификации используется сверточная нейронная сеть (CNN) с 5 слоями, обученная на 15 эпохах. Модель обучена с целью высокой точности классификации и минимизации ложных срабатываний.

- **Метрика качества (Accuracy)**: 0.7

### 🛠️ Установка и запуск

Установите *Python*, если он еще не установлен.

Запуск производится с файла `app.bat`.
