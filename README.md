# TeleSupport Hub 📞

A cloud-based telecom customer support portal built with **Flask** and hosted on **AWS RDS (MySQL)**.

## 🚀 Features

- 🔐 Secure Customer & Agent Authentication with role-based sessions
- 🎫 Raise & View Support Tickets (by priority)
- 🛒 Browse & Purchase Service Plans
- 📋 Ticket History for Customers
- ☁️ AWS RDS MySQL with Connection Pooling
- 🎨 Modern Glassmorphism UI (Dark Mode)

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python, Flask |
| Database | MySQL on AWS RDS |
| Frontend | HTML5, CSS3 (Glassmorphism) |
| Templating | Jinja2 |
| DB Driver | mysql-connector-python (pooling) |

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Shwetu09/TeleSupport-Hub-Cloud-based-telecom-support-with-Flask-on-AWS.git
   cd TeleSupport-Hub-Cloud-based-telecom-support-with-Flask-on-AWS
   ```

2. **Install dependencies:**
   ```bash
   pip install flask mysql-connector-python
   ```

3. **Configure the database** in `app.py`:
   ```python
   dbconfig = {
       "host": "YOUR_RDS_ENDPOINT",
       "user": "YOUR_USERNAME",
       "password": "YOUR_PASSWORD",
       "database": "telesupporthub",
       "port": 3306
   }
   ```

4. **Run the application:**
   ```bash
   python app.py
   ```

5. Open your browser at `http://localhost:5000`

## 🗄️ Database Schema

- `customers` — Customer registration data
- `agents` — Support agent credentials
- `categories` — Available service plans
- `tickets` — Customer support requests
- `orders` — Service purchase records


## 👩‍💻 Developed By

**Shweta Bhosale**

---
> Cloud-based telecom support system — Flask on AWS
