📝 MyBlog

MyBlog — bu `Python` dasturlash tilida, `Django` freymvorki yordamida yaratilgan oddiy, foydalanuvchiga qulay blog ilovasi. Ushbu loyiha `PyCharm` muhitida ishlab chiqilgan.

🚀 Loyihaning imkoniyatlari

- 👤 Foydalanuvchi ro'yxatdan o'tishi va tizimga kirishi
- 🖼️ Foydalanuvchi post yaratishi (faqat ro'yxatdan o‘tganlardan keyin)
- 📌 Har bir postda:
  - Rasm (image)
  - Sarlavha (title)
  - To‘liq matn (body)
- 📋 Postlar ro‘yxatida:
  - Sarlavha
  - Muallif (author)
  - Joylashtirilgan sana
  - Matnning qisqacha qisqarmasi

---

🛠 Texnologiyalar

- `Python`
- `Django`
- `HTML / CSS` (Django templatelar orqali)
- `SQLite` (default DB)
- `PyCharm` IDE

---

📷 Ekranlar (Screenshots)

> (Agar xohlasangiz, loyihangizdan olingan skrinshotlar joylashtiring)

---

🔧 O‘rnatish

Repozitoriyani yuklash
```bash
git clone https://github.com/jaloliddinomonboev/MyBlog.git
cd MyBlog
```

Virtual muhit yaratish
```bash
python -m venv venv
venv\Scripts\activate   # Linux/Mac: source venv/bin/activate
```

Kerakli kutubxonalarni o‘rnatish
```bash
pip install -r requirements.txt
```

Migratsiyalarni bajarish
```bash
python manage.py migrate
```

Serverni ishga tushurish
```bash
python manage.py runserver
```
