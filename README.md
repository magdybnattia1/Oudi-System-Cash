# Oudi System Cash

نظام كاشير وإدارة مبيعات باللغة العربية، مجهز للعمل كتطبيق Windows باستخدام Electron.

## تشغيله أثناء التطوير

يتطلب Node.js إصدار LTS حديثًا.

```bash
npm install
npm start
```

## بناء ملف EXE

على Windows:

```bash
npm install
npm run build:win
```

سيظهر ملف التثبيت داخل مجلد `dist`.

## البناء التلقائي من GitHub

كل Push إلى فرع `main` أو تشغيل يدوي لسير العمل سيبني نسخة Windows ويرفع ملف التثبيت كـ Artifact باسم `Oudi-System-Cash-Windows`.

## ملاحظة مهمة عن البيانات

النسخة الحالية تخزن بياناتها محليًا داخل تخزين التطبيق (Local Storage). لا تحذف بيانات التطبيق أو مجلد بياناته قبل أخذ نسخة احتياطية من داخل البرنامج.
