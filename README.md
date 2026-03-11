# ЛР1: Анализ и прогнозирование временных рядов (розничные продажи)

## Содержимое
- `lab1_retail_sales_time_series.ipynb` — решение (EDA, декомпозиции, ARIMA/SARIMAX, метрики, анализ остатков)
- `retail_sales_mock_data.csv` — исходные данные
- `requirements.txt` — зависимости

## Запуск

```bash
python -m venv .venv
# Windows PowerShell:
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
pip install notebook
jupyter notebook
```

## Публикация на GitHub (получить ссылку)

```bash
git init
git add .
git commit -m "Lab1: time series analysis and forecasting"

# далее создайте репозиторий на GitHub, затем:
git branch -M main
git remote add origin <YOUR_REPO_URL>
git push -u origin main
```

