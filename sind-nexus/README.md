# 🛡️ SIND NEXUS v4.0

**Voice-Powered AI Companion Platform**

منصة ذكاء اصطناعي صوتي متقدمة — GeoMemory، VoiceDNA، Emotional Core، Hologram، ورفيقك الذكي بـ 4 شخصيات.

---

## 🚀 الميزات

| النظام | الوصف |
|--------|-------|
| 🌍 **GeoMemory** | ذاكرة جغرافية ذكية تحفظ السياقات المكانية |
| 🎙️ **VoiceDNA Isolator** | بصمة صوتية فريدة لكل مستخدم |
| 💙 **Emotional Core** | كشف المشاعر في الوقت الفعلي |
| 🤖 **Generative Companion** | 4 شخصيات: عاشق، طبيب، مرشد، محلل |
| 🎭 **Voice Persona Engine** | 5 شخصيات صوتية + تسجيل مخصص |
| 🌐 **Language Matrix** | 47 لغة مع ترجمة فورية |
| 👁️ **Hologram System** | هولوغرام تلقائي عند المكالمات |
| 🔔 **Proactive Alerts** | تنبيهات ذكية لرفع مستوى الحياة |
| ☎️ **Voice Calls** | مكالمات صوتية مع هولوغرام |
| 🧠 **Conscious Systems** | ذكاء اصطناعي واعٍ ذاتياً |

---

## 📦 التثبيت المحلي

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/sind-nexus.git
cd sind-nexus

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate   # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the server
uvicorn main:app --reload

# 5. Open browser
# http://localhost:8000
```

---

## 🌐 النشر على Render (Zero Config)

### الخطوة 1: رفع الكود على GitHub

```bash
git init
git add .
git commit -m "SIND NEXUS v4.0 Initial Release"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/sind-nexus.git
git push -u origin main
```

### الخطوة 2: الربط بـ Render

1. اذهب إلى [render.com](https://render.com) وسجل دخولك بحساب GitHub
2. اضغط **"New +"** → **"Web Service"**
3. اختر مستودع **sind-nexus**
4. Render سيكتشف تلقائياً:
   - **Environment:** Python
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `uvicorn main:app --host 0.0.0.0 --port $PORT`
5. اضغط **"Create Web Service"**
6. انتظر 2-3 دقائق...
7. ✅ **رابطك جاهز!** `https://sind-nexus.onrender.com`

> **ملاحظة:** لا حاجة لتعديل أي إعدادات — Render يكتشف `Procfile` و `render.yaml` تلقائياً!

---

## 📱 بناء APK تلقائياً (GitHub Actions)

عند كل `push` إلى الفرع `main`:
- GitHub Actions يبني APK تلقائياً
- يُرفع في **Releases**
- يمكنك تحميله مباشرة!

---

## 🔌 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/` | GET | Frontend Interface |
| `/api/activate` | GET | تفعيل النظام |
| `/api/status` | GET | حالة النظام |
| `/api/geomemory/store` | POST | حفظ ذاكرة جغرافية |
| `/api/voice/fingerprint` | POST | إنشاء بصمة صوتية |
| `/api/emotion/detect` | POST | كشف المشاعر |
| `/api/companion/chat` | POST | محادثة الرفيق |
| `/api/translate` | POST | الترجمة |
| `/ws/voice/{user_id}` | WS | قناة صوتية WebSocket |

---

## 🛡️ عبارة التفعيل

قل أو اكتب:
> **"سند نكسس اونلاين"**

---

## 📄 الترخيص

MIT License - مفتوح المصدر بالكامل.

---

**Built with ❤️ for the future of AI companions.**
