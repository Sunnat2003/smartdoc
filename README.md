# SmartDoc OTM - 1-bosqich

## Ishga tushirish
```bash
python -m venv .venv && source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env                                   # va qiymatlarni to'ldiring

# PostgreSQL'da bazani yarating:
#   createdb smartdoc        (yoki psql ichida: CREATE DATABASE smartdoc;)

python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
Admin panel: http://127.0.0.1:8000/admin/
