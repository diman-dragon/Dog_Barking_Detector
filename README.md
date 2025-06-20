
---

# 🐶 Dog Barking Detector

This project is a simple system for automatically detecting dog barking in audio recordings using Python, Librosa, Pydub, and audio signal processing techniques.

## 🔍 Overview

The goal of the project is to analyze an audio file and identify segments containing dog barking. Key steps include:

- Splitting audio into segments
- Extracting loud peaks
- Visualizing amplitude graphs
- Exporting detected barking segments to separate files

## 📦 Libraries Used

- `librosa` — for extracting audio features
- `pydub` — for segmenting and exporting audio fragments
- `numpy`, `matplotlib` — for visualization and processing
- `scipy` — for signal smoothing
- `concurrent.futures` — for multithreading to speed up analysis

## 🚀 Getting Started

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook Dog_Barking_Detector.ipynb
```

3. Select an `.mp3` or `.wav` audio file and follow the steps in the notebook cells.

## 📁 Project Structure

```
Dog_Barking_Detector/
├── Dog_Barking_Detector.ipynb
├── output_segments/           # exported segments with barking
├── audio/                     # input audio files
└── README.md
```

## 📈 Results

- Segments with barking are saved as separate files
- Amplitude graphs are visualized
- Processing logs for each segment are displayed

## ⚙ Parameters

- `threshold_db` — loudness threshold (default: -30 dB)
- `segment_length_sec` — length of analyzed segments (default: 60 seconds)

## 📌 Notes

- Supports long audio files (up to several hours)
- Multithreading is implemented for faster processing

## 📜 License

MIT License

---

Author: diman-dragon

---








# 🐶 Dog Barking Detector

Этот проект представляет собой простую систему для автоматического обнаружения лая собаки на аудиозаписях с помощью Python, Librosa, Pydub и методов обработки аудиосигналов.

## 🔍 Описание

Цель проекта — анализировать аудиофайл и обнаруживать участки, где слышен лай собаки. Основные шаги:

- Разбиение аудио на фрагменты
- Извлечение громких пиков
- Визуализация амплитудных графиков
- Экспорт выявленных фрагментов с лайем в отдельные файлы

## 📦 Используемые библиотеки

- `librosa` — извлечение аудио-фич
- `pydub` — нарезка и экспорт фрагментов
- `numpy`, `matplotlib` — визуализация и обработка
- `scipy` — сглаживание сигнала
- `concurrent.futures` — многопоточность для ускорения анализа

## 🚀 Запуск

1. Установи зависимости:
```bash
pip install -r requirements.txt
```

2. Запусти Jupyter Notebook:
```bash
jupyter notebook Dog_Barking_Detector.ipynb
```

3. Выбери аудиофайл `.mp3` или `.wav`, следуй шагам в ячейках.

## 📁 Структура проекта

```
Dog_Barking_Detector/
├── Dog_Barking_Detector.ipynb
├── output_segments/           # экспортированные фрагменты с лайем
├── audio/                     # входные аудиофайлы
└── README.md
```

## 📈 Результаты

- Сохраняются участки с лаем в виде отдельных файлов
- Визуализируются графики амплитуды
- Отображается лог обработки каждого фрагмента

## ⚙ Параметры

- `threshold_db` — порог громкости (по умолчанию -30 dB)
- `segment_length_sec` — длина анализируемых фрагментов (по умолчанию 60 сек)

## 📌 Заметки

- Поддерживаются длинные аудиофайлы (до нескольких часов)
- Предусмотрена многопоточность для ускорения обработки

## 📜 Лицензия

MIT License

---

Автор: diman-dragon
