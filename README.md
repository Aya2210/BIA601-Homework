# BIA601-Homework
# 🧬 BIA601 – تحسين التوصيات بالخوارزميات الجينية


**المقرر:** BIA601 – الخوارزميات الذكية  
**اعداد:** aya_238683 ||  esraa_245951 ||  hassan_116900  ||  Oula_177756   || Khaled_197173 

**الفصل:** S25  

---

## 📌 فكرة المشروع

بناء نظام توصيات ذكي للمتاجر الإلكترونية يعتمد على **الخوارزميات الجينية** المستوحاة من الطبيعة (الانتقاء الطبيعي، التزاوج، الطفرة) لتحسين جودة التوصيات المقدمة للمستخدمين بناءً على:

- تقييمات المنتجات (ratings)
- سلوك المستخدم (مشاهدة، نقر، شراء)

---

## ⚙️ آلية العمل

1. **رفع ملفات البيانات** (users, products, ratings, behavior)
2. حساب **درجة اللياقة (Fitness)** لكل منتج
3. تطبيق **الخوارزمية الجينية**:
   - إنشاء مجتمع أولي من التوصيات
   - تقييم وانتقاء الأفضل
   - تزاوج ودمج التوصيات
   - إضافة طفرات عشوائية
   - تكرار العملية إلى 5 أجيال
4. عرض **أفضل 5 توصيات محسنة**

---

## 🛠️ التقنيات المستخدمة

- HTML5 / CSS3 / JavaScript
- مكتبة **SheetJS (XLSX)** لقراءة ملفات Excel
- FontAwesome للأيقونات
- **Git & GitHub** لإدارة الإصدارات

---

## 📁 هيكلة البيانات

| الملف | المحتوى |
|-------|---------|
| users.xlsx | user_id, age, country |
| products.xlsx | product_id, category, price |
| ratings.xlsx | user_id, product_id, rating |
| behavior.xlsx | viewed, clicked, purchased |

---

## 🚀 كيفية التشغيل

1. تحميل المشروع من GitHub
2. فتح ملف `BIA601.html` في المتصفح
3. رفع الملفات الأربعة
4. الضغط على زر **"تشغيل النظام"**

---

## 📚 المراجع العلمية

- Goldberg, D. E. (1989). *Genetic Algorithms in Search, Optimization, and Machine Learning*
- Mitchell, M. (1998). *An Introduction to Genetic Algorithms*
- Recommender Systems Handbook – Springer (2015)
- [ACM Digital Library](https://dl.acm.org/)
- [IEEE Xplore](https://ieeexplore.ieee.org/)

---

## 🧪 إدارة الإصدارات (Git)

تم استخدام Git لإدارة المشروع:

- عدد الـ Commits: 5+
- الفروع: `main`, `develop`
- إصدار مستقر: `v1.0`

---

**© 2026 –    آية حموش ,إسراء الرفاعي ,خالد الدرة,علا عطايا,حسان عودة| BIA601**
