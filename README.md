
---

# 📡 ZeroTraceSOC — Zamonaviy Server Tahlilchi & Xavfsizlik Monitoring Dasturi

## 🛡️ Kirish

**ZeroTraceSOC** — bu kuchli, tezkor va yengil xavfsizlik monitoring platformasi bo‘lib, serverdagi barcha **kiruvchi/chiquvchi IP traffik**, **loglar**, **server hotirasi**, **request/response** jarayonlari, va **DDoS hujumlarini** doimiy nazorat qilib boradi. U **OPEN CTI**’ga o‘xshash vizual interfeysga ega va qulay ishlaydi.

---

## ⚙️ Texnologiyalar

- **Backend**: `Python`, `Node.js`
- **Frontend**: `React.js`, `Electron.js`
- **Arxitektura**: GUI ilova sifatida Electron orqali desktop ko‘rinishda

---

## 🚀 Asosiy Imkoniyatlar

| Funksiya | Tavsif |
|----------|--------|
| 🔍 **Traffik monitoring** | Serverga kiruvchi va chiquvchi IP manzillarni real vaqtda tahlil qiladi |
| 📄 **Loglar bilan ishlash** | Barcha tizim loglarini o‘qish, tahlil qilish va aniqlik kiritish imkoniyati |
| 💾 **Hotira nazorati** | Server RAM va resurslardan foydalanishni doimiy kuzatish |
| 🌐 **Request/Response tahlili** | HTTP(S) so‘rovlarini tahlil qilish, hujumga olib keluvchi so‘rovlarni ajratish |
| ☠️ **DDoS hujumini aniqlash** | Trafikdagi noodatiy yuklamalarni aniqlab, foydalanuvchini ogohlantirish |
| 🧱 **Paket filtratsiyasi** | Buzilgan yoki noto‘g‘ri formatlangan tarmoq paketlarini aniqlash va bloklash |
| 🎛️ **Vizual interfeys** | OPEN CTI’ga o‘xshash sodda, foydalanuvchiga qulay GUI bilan ta’minlangan |
| 🔋 **Engil resurs iste'moli** | Serverda minimal resurs bilan ishlash imkoniyati – hatto zaif tizimlarda ham tez ishlaydi |

---

## 🖥️ O'rnatish va Ishga Tushurish

### 1. Talablar
- Node.js 16+
- Python 3.10+
- Git
- Docker (ixtiyoriy)

### 2. Klonlash
```bash
git clone https://github.com/your-org/zerotracesoc.git
cd zerotracesoc
```

### 3. Python backendni ishga tushurish
```bash
cd backend
pip install -r requirements.txt
python app.py
```

### 4. React frontendni ishga tushurish
```bash
cd ../frontend
npm install
npm start
```

### 5. Electron GUI ni ishga tushurish
```bash
cd ../desktop
npm install
npm run electron
```

---

## 🧠 Foydalanish bo‘yicha Qo‘llanma

### 🔎 Monitoring
- GUI orqali dashboardni oching.
- **"Live Traffic"** bo‘limidan kiruvchi va chiquvchi IP'larni ko‘rishingiz mumkin.
- DDoS tahdidlar paydo bo‘lsa, tizim real vaqtda sizni ogohlantiradi.

### 📊 Loglar
- `Logs` bo‘limida filtrlar orqali loglarni o‘rganish mumkin.
- Loglarni turli formatlarda eksport qilish mumkin: `.json`, `.txt`, `.csv`

### 🧱 Paketlar tahlili
- `Packets` menyusida har bir paketni ko‘rib chiqish va holatini tekshirish imkoniyati bor.
- Buzilgan paketlar qizil rang bilan belgilanadi.

### 📈 Performance
- Server CPU, RAM, Disk, Network foydalanishini real vaqt grafiklar orqali ko‘rish.

---

## 🌟 Nega ZeroTraceSOC?

✅ Engil, tezkor va samarali  
✅ Professional xavfsizlik darajasidagi monitoring  
✅ GUI interfeysda ishlash oson  
✅ Barcha faoliyatni bir joyda kuzatish imkoniyati  
✅ Kengaytiriladigan arxitektura: boshqa xavfsizlik vositalari bilan integratsiyalash mumkin  
✅ O‘zbek va ingliz tillarida ishlash imkoniyati (ixtiyoriy)

---

## 📬 Aloqa

Savollar yoki takliflar bo‘yicha quyidagi manzillarga murojaat qiling:

📧 Email: `tempiltin.uz@gmail.com`  
🌐 Vebsayt: [www.tempiltin.uz](http://www.tempiltin.uz)

