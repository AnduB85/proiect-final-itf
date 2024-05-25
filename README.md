<h3>DESCRIERE:</h3>

- **In proiectul meu  am construit un site web de prezentare a filmelor, dezvoltat folosind framework-ul Django ,  în limbajul de programare Python. Aplicația permite utilizatorilor să caute filme, să vizualizeze detalii despre acestea și să acceseze pagina de contact și alte informații relevante.**

<h3>SCREENSHOT API FILME:</h3>


<img src="https://i.imgur.com/utsBcdN.png" alt="sc">

<h3>TEHNOLOGII SI TOOL-URI UTILIZATE :</h3>

- **Framework:** Django
- **Limbaj de programare:** Python
- **IDE (Integrated Development Environment):** Pycharm
- **Frontend:** HTML, CSS
- **Baza de date:** SQLite 
- **Altele:**  GitHub pentru hosting cod

<h3>INSTRUCTIUNI DE INSTALARE SI RULARE A PROIECTULUI :</h3>

- **Importam proiectul prin clonarea urmatorului repository in care se afla acesta:**

git clone https://github.com/AnduB85/proiect-final-itf.git
- **Se creeaza un mediu virtual:** 

python -m venv venv

- **Se activeaza mediul virtual:** 

pentru Windows: .\venv\Scripts\activate

pentru macOS/Linux: source venv/bin/activate

- **Se instaleaza dependintele Python:** 

pip install -r requirements.txt

- **Pentru migrarea bazei de date folosim urmatoarele comenzi:**

python manage.py makemigrations

python manage.py migrate

- **Pentru a avea acces la interfața de administrare, se creează un superuser:**

python manage.py createsuperuser

- **Rulam serverul de dezvoltare Django cu urmatoarea comanda:**

python manage.py runserver

- **Testarea aplicatiei se face accesând URL-ul corespunzător  http://127.0.0.1:8000/**




