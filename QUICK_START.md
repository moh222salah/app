# ⚡ البدء السريع - تطبيق منطقتي

## 🚀 خطوات سريعة للتشغيل

### 1. فتح المشروع
```bash
cd mantiqati-app
```

### 2. تثبيت الحزم
```bash
npm install
```

### 3. تشغيل التطبيق

#### Android
```bash
npm run android
```

#### iOS
```bash
cd ios && pod install && cd ..
npm run ios
```

---

## 📂 الملفات المهمة

### أساسية
- ✅ `README.md` - دليل شامل للمشروع
- ✅ `INSTALLATION_GUIDE.md` - تعليمات التثبيت التفصيلية
- ✅ `PROJECT_SUMMARY.md` - ملخص ما تم إنجازه
- ✅ `QUICK_START.md` - هذا الملف

### الكود
- ✅ `App.js` - نقطة البداية
- ✅ `src/` - جميع أكواد التطبيق
  - `constants/theme.js` - الألوان والتصميم
  - `redux/store.js` - إدارة الحالة
  - `services/api.js` - جميع الـ APIs
  - `screens/` - جميع الشاشات
  - `components/` - المكونات القابلة لإعادة الاستخدام

---

## 🎨 التخصيص السريع

### تغيير الألوان
```javascript
// src/constants/theme.js
export const COLORS = {
  primary: '#1a237e',    // غير هذا للون الأساسي
  secondary: '#ffd700',  // غير هذا للون الثانوي
  // ...
};
```

### تغيير عنوان API
```javascript
// src/constants/config.js
export const BASE_URL = 'https://api.mantiqati.com/api/v1';
```

---

## 🔑 المتطلبات

### للتطوير
- Node.js 18+
- npm أو yarn
- Android Studio (للأندرويد)
- Xcode (للآيفون - Mac فقط)

### APIs المطلوبة (اختياري)
- Google Maps API Key
- Firebase Project
- Paymob/Fawry Account (للدفع)

---

## 📱 الشاشات المُنفذة

### جاهزة 100%
- ✅ Splash Screen (شاشة البداية)
- ✅ Login Screen (تسجيل الدخول)
- ✅ Home Screen (نبض المنطقة)
- ✅ Purchase Detail Screen (تفاصيل العملية)

### جاهزة للتطوير
- ⏳ OTP Screen
- ⏳ Orders Screen
- ⏳ Profile Screen
- ⏳ Notifications Screen
- ⏳ Supervisor Dashboard

---

## 🐛 حل المشاكل السريع

### المشكلة: لا يعمل npm install
```bash
# حل 1: حذف node_modules
rm -rf node_modules
npm install

# حل 2: استخدام yarn
yarn install
```

### المشكلة: Build فشل
```bash
# Android
cd android && ./gradlew clean && cd ..
npm run android

# iOS
cd ios && pod install && cd ..
npm run ios
```

### المشكلة: Metro لا يعمل
```bash
npm start -- --reset-cache
```

---

## 📞 المساعدة

راجع الملفات التالية للمزيد من التفاصيل:
1. `README.md` - دليل شامل
2. `INSTALLATION_GUIDE.md` - تعليمات مفصلة
3. `PROJECT_SUMMARY.md` - ملخص المشروع

---

**استمتع بالتطوير! 🚀**
