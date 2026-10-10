# Домашние задания Аси

Репозиторий содержит учебные Jupyter-ноутбуки по Python и математической статистике.

## Структура

```text
hw_asya/
├── python/
│   ├── tasks_2026-08-20.ipynb
│   └── tasks_2026-08-22_iterables.ipynb
├── matstat/
│   ├── week01_homework.ipynb
│   ├── logo.png
│   └── data/
│       └── youtube_data_short.csv
├── requirements.txt
└── README.md
```

- `python/` — задания по основам Python, функциям, условиям, циклам и итерируемым объектам.
- `matstat/` — домашняя работа по описательной статистике и анализу данных.

## Как скачать проект

Установите [Python](https://www.python.org/downloads/) версии 3.10 или новее и Git. Затем откройте терминал и выполните:

```bash
git clone https://github.com/tlum1/hw_asya.git
cd hw_asya
```

Если проект уже скачан, для получения последних изменений выполните:

```bash
cd hw_asya
git pull
```

## Как создать окружение

Создайте виртуальное окружение в корне проекта:

```bash
python3 -m venv .venv
```

Активируйте его на macOS или Linux:

```bash
source .venv/bin/activate
```

На Windows в PowerShell используйте:

```powershell
.venv\Scripts\Activate.ps1
```

После активации обновите `pip` и установите зависимости:

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

## Как открыть ноутбуки

Запустите JupyterLab из корня проекта:

```bash
python -m jupyter lab
```

В открывшемся окне выберите нужную папку и ноутбук:

- `python/` — домашние задания по Python;
- `matstat/week01_homework.ipynb` — домашняя работа по математической статистике.

Для ноутбука по математической статистике важно сохранить структуру папки `matstat/`: файл данных загружается по относительному пути `data/youtube_data_short.csv`.

После окончания работы остановите JupyterLab сочетанием `Ctrl+C` в терминале и деактивируйте окружение:

```bash
deactivate
```

