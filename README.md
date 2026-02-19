# 🎓 QR Certificate Generator Pro
**Developed by Abdul Samad | Shaheed Benazir Bhutto University Nawabshah**

---

## ✅ Features
- 🔳 **QR Code System** — Students scan, enter name, get certificate instantly
- 🖼️ **PNG + PDF** download support
- 🎨 **Custom font, color, size, position** via admin panel
- 📊 **Bulk generation** from .txt names file
- 📈 **Analytics dashboard** with Excel export
- 🔐 **Admin login** for security
- ⚡ **100+ simultaneous users** supported (Streamlit handles concurrency)
- 📱 **Mobile friendly** — works on any device

---

## 🚀 Installation & Run

### Step 1 — Install Python (if not installed)
Download from: https://python.org

### Step 2 — Install Libraries
```bash
pip install -r requirements.txt
```

### Step 3 — Run the App
```bash
streamlit run app.py
```
App opens at: **http://localhost:8501**

---

## ☁️ Deploy to Internet (Free) — Streamlit Cloud

1. Create account at **https://streamlit.io/cloud**
2. Push your code to GitHub
3. Click "New App" → select your repo → deploy
4. Copy the live URL → paste it in the admin panel → Generate QR

---

## 📱 Student Flow (After QR is printed)

```
Student scans QR with phone camera
        ↓
Browser opens → Student enters their name
        ↓
Certificate generated instantly ✅
        ↓
Student downloads PNG or PDF
```

---

## 👨‍💼 Admin Flow

```
1. Open app → Login (default: admin123)
2. Upload certificate template (.png or .jpg)
3. Customize: font size, color, position in sidebar
4. Enter event name (e.g. "AI Workshop 2025")
5. Enter your deployed app URL
6. Click "Generate QR Code"
7. Download & print the QR → Display at event
```

---

## 📁 File Structure
```
certificate_app/
├── app.py              ← Main Streamlit app
├── requirements.txt    ← Python dependencies
└── README.md           ← This file
```

---

## 🔧 Customization Tips

| Setting | How to Change |
|---------|--------------|
| Admin password | Sidebar → Change Password (or edit `admin_password` in code) |
| Default font size | Sidebar slider |
| Text position | Sidebar sliders (H% and V%) |
| Text color | Color picker in sidebar |
| Event name | Sidebar text field |

---

## ❓ FAQ

**Q: Can 100+ students use it at the same time?**  
A: Yes! Streamlit handles each user in a separate session. Deploy on Streamlit Cloud for best performance.

**Q: Does it support Urdu names?**  
A: Yes, the app reads UTF-8 text. For Urdu font rendering, replace `arial.ttf` with a Nastaliq font.

**Q: How to add a second text field (e.g., date or role)?**  
A: Duplicate the `generate_certificate()` text block with different x/y coordinates.

---

## 📞 Support
Developed by: **Abdul Samad**  
University: Shaheed Benazir Bhutto University Nawabshah
