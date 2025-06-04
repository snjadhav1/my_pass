# my_paas_app

This is a simple web application deployed on **Google Cloud App Engine (PaaS)** using **Flask** and **Gunicorn**. It serves a basic HTML page to demonstrate how to deploy Python apps on Google Cloud's Platform-as-a-Service environment.

---

## 🚀 Deployment Steps

### 1️⃣ Open Google Cloud Shell  
👉 [Click to open](https://shell.cloud.google.com)

---

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/Saniya-Bhosale/my_paas_app.git
cd my_paas_app
```

---

### 3️⃣ (Optional) Install Dependencies Locally for Testing

```bash
pip install -r requirements.txt
python3 main.py
```

> ⚠️ You’ll only see output in the shell — this is just for optional local testing, not required for deployment.

---

### 4️⃣ Deploy to App Engine (PaaS)

```bash
gcloud app deploy
```

✅ When prompted for a region, choose: `asia-south1` (Mumbai)

---

### 5️⃣ Open the Deployed App

```bash
gcloud app browse
```

---

## 🔎 After Deployment

You’ll get a live URL like:

```
https://my-paas-app-xxxxx.ew.r.appspot.com/
```

When you visit it, your app will display:

> **Hello from Google Cloud PaaS!**  
> And show an alert saying: **"Running on PaaS!"**

---

## 📝 Technologies Used

- Python 3.9
- Flask 2.2.5
- Gunicorn
- Google App Engine (PaaS)

---

## 📂 Project Structure

```
my_paas_app/
├── index.html
├── main.py
├── app.yaml
└── requirements.txt
```

---

## ✅ Done!
