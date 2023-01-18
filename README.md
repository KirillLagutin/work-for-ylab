# work-for-ylab
Cafe menu (FastAPI, SQLAlchemy, uvicorn)


## Описание шагов по запуску проекта

### Заходим в файл src/db/database.py,  
 в переменную SQLALCHEMY_DATABASE_URL   
 вставляем строку подключения для своей пустой базы,  
 далее идём в терминал

### В терминале, из папки проекта, прописываем команды:

  ### 1. Создание базы: 
  
     python create_db.py

  ### 2. Запуск сервера:

     uvicorn main:app --reload

  ### 3. Тестируем в Postman.
