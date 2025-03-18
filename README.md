# ML_api
Базовый Fast API сервис для ML модели на данных о выживших на Титанике

1) Проходитесь в файле __train.ipynb__ по пунктам Обучение и Инференс *(создаете файл model.pkl)*
2) Запускаете файл __app_api.py__
3) В пункте Тест API в файле __train.ipynb__ проверяете работоспособность сервиса

---

## Docker
``` 
docker build -t titanic-service:latest .

docker run -d --name titanic-service -p 5000:5000 titanic-service:latest
 ```

## Streamlit
```
streamlit run streamlit_app.py
```
