# DRF-REACT
A React frontend consuming a REST API made using Django REST Framework.

## Local Setup
Setup of the project consists of setting the backend and frontend apps.

### Backend Setup
```bash
git clone git@github.com:nickmwangemi/DRF-REACT.git
cd DRF-REACT
```

Change into backend directory and install project dependencies.
```bash
cd backend
pip install -r requirements.txt
```

Setup database, createsuperuser and start local dev server.
```bash
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Crack open the API browser at [http://127.0.0.1:8000/api](http://127.0.0.1/api)

### Frontend Setup
```bash
cd frontend
npm install
npm start
```
The frontend should be available at [http://localhost:3000](http://localhost:3000)
