# Базовый образ
FROM python:3.13-slim

# Установка рабочей директории
WORKDIR /app

# Копируем зависимости и приложение
COPY requirements.txt requirements.txt
COPY app/ app/

# Устанавливаем зависимости
RUN pip install --no-cache-dir -r requirements.txt

# Указываем команду для запуска приложения
CMD ["python", "app/app.py"]
