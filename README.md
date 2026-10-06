# Canteen Management — GitHub Pages Demo

هذه نسخة تجريبية Static يمكن نشرها مباشرة على GitHub Pages وفتحها من الهاتف.

## التشغيل
1. ارفع ملفات المجلد إلى Repository.
2. من Settings → Pages اختر Deploy from a branch.
3. اختر `main` و`/ (root)`.
4. افتح الرابط الناتج.

## مهم
هذه النسخة التجريبية تستخدم LocalStorage داخل المتصفح بدل Node.js + SQLite، لأن GitHub Pages يستضيف ملفات Static ولا يشغّل Node.js أو SQLite server.

النسخة النهائية المحلية التي تعتمد على Node.js + SQLite تبقى مناسبة لجهاز الكنتين والسيرفر الداخلي.
