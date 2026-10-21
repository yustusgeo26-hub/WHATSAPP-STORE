# Yustus Store — Modern WhatsApp Storefront

Responsive fashion storefront with WhatsApp checkout, FastAPI/SQLite API, and admin dashboard.

## Run locally

```cmd
cd backend
python -m venv .venv
.venv\Scripts\activate.bat
pip install -r requirements.txt
set ADMIN_PASSWORD=replace-with-a-strong-password
set DEVELOPER_PASSWORD=replace-with-another-strong-password
python -m uvicorn main:app --reload
```

Visit http://127.0.0.1:8000/ and http://127.0.0.1:8000/admin.html. Configure production secrets before deployment. Do not commit database files, uploaded customer data or virtual environments.
