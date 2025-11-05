# ستيرسو موتورز - صفحة بيع سيارات

مرحبًا! هذا مشروع بسيط لموقع بيع سيارات باللغة العربية، باسم **ستيرسو موتورز**، مع واجهة RTL وتصميم أحمر وأبيض.

## محتويات المشروع
- `index.html` — الصفحة الرئيسية (RTL، عربية).  
- `styles.css` — أنماط CSS بالألوان الأحمر والأبيض.  
- `app.js` — بيانات السيارات وواجهة البحث والتصفية (JavaScript).  
- `images/` — مجلد لصور السيارات (`car1.jpg`, `car2.jpg`, …).  

## طريقة الاستخدام محليًا
1. فك الضغط عن المجلد.  
2. ضع صور السيارات الحقيقية داخل مجلد `images/` بنفس أسماء الملفات أو عدّل الروابط في `app.js`.  
3. افتح `index.html` في المتصفح لتشغيل الموقع محليًا.  
4. لإضافة سيارة جديدة، افتح `app.js` وأضف كائنًا جديد في مصفوفة `cars`.

## رفع المشروع على GitHub و GitHub Pages
1. أنشئ مستودعًا جديدًا على GitHub باسم `sterso-motors` أو أي اسم تحبه.  
2. افتح الطرفية داخل المجلد:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/sterso-motors.git
git push -u origin main
