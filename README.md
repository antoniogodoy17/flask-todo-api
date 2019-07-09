# Flask To-Do API

## Run this API:

1. Clone this repository to your local machine
```
git clone https://github.com/antoniogodoy17/flask-todo-api.git
cd flask-todo-api
```

2. Install requirements
``` 
cd api
pip install -r requirements.txt
```

3. Create your .env file with the following variables
```
JWT_SECRET_KEY='Some secret phrase'
DB_URL='your mongo db url'
```

4. Run Flask server (by default is running on port 8080)
```
python3 api.py
```