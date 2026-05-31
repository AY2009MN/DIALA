# المزامنة مع GitHub - اختبار الرياضيات ديالا

## المستودع
```
https://github.com/AY2009MN/DIALA
```

## الملفات الأساسية
| الملف | الوصف |
|---|---|
| `index.html` | التطبيق الرئيسي (HTML + CSS + JS) |
| `manifest.json` | ملف تعريف PWA للتثبيت |
| `sw.js` | Service Worker للتشغيل دون اتصال |
| `.gitignore` | استثناءات Git |

## سير العمل

### تعديل الملفات محلياً
1. عدّلي الملفات في مجلد `DIALA`
2. اختبر التعديلات بفتح `index.html` في المتصفح

### رفع التعديلات إلى GitHub
```bash
git add .
git commit -m "شرح التعديل"
git push
```

### تحميل آخر التعديلات من GitHub
```bash
git pull
```

### تفعيل GitHub Pages (مرة واحدة فقط)
اذهبي إلى:
```
https://github.com/AY2009MN/DIALA/settings/pages
```
- Source → **Deploy from a branch**
- Branch → **main** → **/(root)**
- Save

بعد التفعيل، التطبيق سيكون متاحاً على:
```
https://ay2009mn.github.io/DIALA/
```
عند الدفع لاحقاً إلى `main`، يتم نشر التحديث تلقائياً.

## تثبيت التطبيق على التابلت
1. افتحي الرابط على متصفح التابلت
2. اضغطي على **"📲 تثبيت التطبيق"** في شاشة الترحيب
3. أو من قائمة المتصفح → Add to Home screen
4. التطبيق يعمل دون اتصال بعد التثبيت
