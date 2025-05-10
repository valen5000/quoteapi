
FROM python:3.9-slim
WORKDIR /app
# Copy only necessary files first (improves caching)
COPY requirements.txt .
COPY . .
EXPOSE 5000
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
