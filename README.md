# 🏠 البيت السعيد للمصاريف

تطبيق ويب متكامل لإدارة مصاريف المنزل، مبني بـ HTML/CSS/JavaScript مع Firebase.

##
## ✨ المميزات
- 🔐 تسجيل دخول بـ Firebase Authentication
- 💰 تسجيل المبالغ الواردة بمصادر متعددة
- 💸 تسجيل المصاريف بتصنيفات ذكية
- 📊 كشف حساب تفاعلي مع رسوم بيانية
- ⚙️ صفحة إعدادات شاملة (عملة، فلترة، ترتيب...)
- 📱 PWA — يمكن تثبيته على الموبايل
- ☁️ مزامنة سحابية فورية عبر Firestore

## 🚀 الرفع على GitHub

```bash
git init
git add .
git commit -m "🏠 البيت السعيد للمصاريف - أول إصدار"
git branch -M main
git remote add origin https://github.com/[username]/[repo-name].git
git push -u origin main
```

ثم فعّل **GitHub Pages** من:
`Settings → Pages → Source: GitHub Actions`

## 🔥 Firebase Setup
1. فعّل **Authentication → Email/Password**
2. أنشئ **Firestore Database**
3. ارفع قواعد الأمان من `firestore.rules`

## 📂 هيكل الملفات
```
├── index.html          # التطبيق الكامل
├── manifest.json       # PWA manifest
├── sw.js               # Service Worker
├── firestore.rules     # قواعد Firestore
├── firestore.indexes.json
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions
```
