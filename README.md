##

1. Create venv environment if required
   `python -m venv venv` 

2. Activate venv `venv\Scripts\activate`

3. `pip install -r requirements.txt`
   
4. `cd keycloak_integration`

5. `py manage.py createsuperuser`
   
6. `py manage.py runserver`
   
7. Goto http://localhost:8000

### To start keycloak locally
8. `docker compose up -d auth`
   
9.  goto http://localhost:8080 Credentials admin:admin
    
10. Copy paste the client secret and enter into http://localhost:8000/admin Social Keycloak