# Loxy Portfolio

A clean Flask portfolio with projects, search, contact messages, and an admin dashboard.

## Setup on Windows

```powershell
cd loxy-portfolio
python -m venv .venv
.venv\Scripts\activate
python -m pip install -r requirements.txt
python seed.py
python app.py
```

Open http://127.0.0.1:5000

Admin: http://127.0.0.1:5000/admin/login

Default login:
- Username: admin
- Password: change-me-now

Change the password before publishing the site.


## Browser customization panel

After logging in, open `/admin/customize`. You can edit branding, hero text, colours, About/Contact copy, social links, and homepage section visibility without changing files.
