[README.md](https://github.com/user-attachments/files/25769742/README.md)
# حكايا – موقع القصص التاريخية

موقع HTML/CSS/JS جاهز للرفع على GitHub Pages أو Netlify.

## 📁 هيكل الملفات

```
hikaya/
├── index.html      ← الصفحة الرئيسية (نقطة الدخول الوحيدة - SPA)
├── styles.css      ← جميع التنسيقات
├── scripts.js      ← منطق JavaScript
├── stories.json    ← بيانات القصص
└── README.md       ← هذا الملف
```

## 🚀 الرفع على GitHub Pages

1. أنشئ مستودع جديد على GitHub
2. ارفع جميع الملفات إليه
3. اذهب إلى **Settings → Pages**
4. اختر **Branch: main** واضغط **Save**
5. الموقع سيكون متاحاً على: `https://yourusername.github.io/hikaya`

## 🌐 الرفع على Netlify

1. اسحب مجلد `hikaya` بالكامل إلى [netlify.com/drop](https://app.netlify.com/drop)
2. سيُنشر الموقع فوراً على رابط Netlify مجاني

## 💰 إضافة Google AdSense

ابحث في الملفات عن التعليقات التي تبدأ بـ `GOOGLE ADSENSE` وأضف كودك في المواضع المحددة:

1. **`index.html` (الرأس):** أضف سكريبت AdSense الرئيسي
2. **الصفحة الرئيسية:** بانر علوي + بانر سفلي
3. **صفحة القصة:** إعلان داخل المقالة
4. **صفحة التصنيف:** بانر علوي

## ➕ إضافة قصص جديدة

افتح ملف `stories.json` وأضف قصة بالصيغة:

```json
{
  "id": 11,
  "title": "عنوان القصة",
  "category": "حروب",
  "icon": "⚔️",
  "image": "https://رابط-الصورة.jpg",
  "excerpt": "مقدمة قصيرة للقصة...",
  "content": "النص الكامل للقصة\n\nفقرة ثانية هنا...",
  "date": "100 م",
  "readTime": "5 دقائق"
}
```

**التصنيفات المتاحة:** `حروب` | `ملوك` | `غرائب` | `أحداث يومية`

## ✨ الميزات

- ✅ تصميم Responsive يعمل على الهاتف والتابلت والحاسوب
- ✅ تحميل القصص من JSON ديناميكياً
- ✅ بحث فوري داخل القصص
- ✅ تصفية حسب التصنيف
- ✅ تأثيرات انتقال سلسة بين الصفحات
- ✅ مواضع AdSense محددة وجاهزة
- ✅ تنقل بين القصص (سابق/تالي)
- ✅ خطوط عربية احترافية (Amiri + Cairo + Noto Naskh)
- ✅ جاهز للرفع على GitHub Pages / Netlify مباشرة
