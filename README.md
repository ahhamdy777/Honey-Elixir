# إكسير العسل · Honey Elixir

الموقع الرسمي لشركة **إكسير العسل** لإنتاج العسل الطبيعي ومنتجات خلية النحل – مطوبس، كفر الشيخ، مصر.

The official website of **Honey Elixir**, a producer of natural honey and hive products in Motobas, Kafr El-Sheikh, Egypt.

---

## عن الموقع | About the site

- موقع بلغتين (عربي / English) يعمل على الموبايل والتابلت واللابتوب، ويدعم الوضع الليلي.
- متجر بأسعار المنتجات وأحجامها، مع سلة طلبات تُرسل الطلب مباشرة على واتساب.
- صفحة تفاصيل لكل منتج: الفوائد، طريقة الاستخدام، المكونات، الحفظ والصلاحية.
- أقسام: قصتنا، الرؤية والرسالة، رحلة العسل، الخطة المستقبلية، فريق العمل، الدعم، تواصل معنا.

A bilingual (Arabic / English), mobile-friendly site with a product shop, full product details, and a cart that sends orders by WhatsApp.

## المنتجات | Products

| المنتج | Product | الأحجام |
|---|---|---|
| عسل نوارة البرسيم | Clover Blossom Honey | 1 كجم · 700 · 500 · 250 · 30 جم |
| عسل زهرة الموالح | Citrus Blossom Honey | 1 كجم · 700 · 500 · 250 · 30 جم |
| عسل الطاقة بالمكسرات | Energy Honey with Nuts | 1 كجم · 500 · 250 · 30 جم |
| شهد النحل | Honeycomb | 1 كجم · 500 جم |
| غذاء الملكات | Royal Jelly | 10 · 5 جم |
| حبوب اللقاح | Bee Pollen | 30 جم |
| البروبوليس | Propolis | 30 جم |
| طلع النخيل | Date Palm Pollen | 30 جم |
| شمع العسل الطبيعي | Natural Beeswax | 250 جم |
| طرود النحل | Bee Packages | 3 براويز – محلي / تصدير |

## الملفات | Files

```
index.html   ← الموقع كاملاً في ملف واحد (كل الصور والخطوط مدمجة بداخله)
README.md    ← هذا الملف
```

The whole site is a single self-contained `index.html` – no other folders or assets are needed.

## النشر على GitHub Pages | Publishing

1. أنشئ مستودعاً جديداً (Repository) عاماً على GitHub، مثلاً باسم `honey-elixir`.
2. اضغط **Add file → Upload files** وارفع الملفين `index.html` و `README.md` في الصفحة الرئيسية للمستودع (بدون مجلدات).
3. اضغط **Commit changes**.
4. افتح **Settings → Pages**، واختر من **Source**: `Deploy from a branch`، ثم الفرع `main` والمجلد `/ (root)`، واضغط **Save**.
5. بعد دقيقة إلى دقيقتين سيظهر رابط الموقع بالشكل:
   `https://<اسم-المستخدم>.github.io/honey-elixir/`
6. استخدم هذا الرابط لعمل كود الـ QR وإضافته على الملصقات والكارت والبروشور.

**English:** create a public repo → upload `index.html` and `README.md` to the root → *Settings → Pages* → deploy from branch `main`, folder `/ (root)` → your site appears at `https://<username>.github.io/<repo>/`.

## التعديل | Editing

- **الأسعار والأحجام:** افتح `index.html`، وابحث عن `const P=[` – كل منتج في سطر واحد، والأحجام بالشكل `["1kg",220,"برطمان زجاج"]` (الحجم، السعر بالجنيه، نوع العبوة).
- **رقم واتساب الطلبات:** ابحث عن `const WA="201009305770"`، وأيضاً عن `wa.me/201009305770` في الأزرار.
- بعد أي تعديل، ارفع الملف مرة أخرى على GitHub بنفس الاسم `index.html` وسيتحدّث الموقع تلقائياً.

## التواصل | Contact

- **المدير:** حمادة سعد عبد الحميد الصعيدي
- **واتساب:** 010 0930 5770
- **البريد:** Honey.Elixir@outlook.com
- **فيسبوك:** https://www.facebook.com/share/1FHBLbjVvg/
- **العنوان:** مطوبس – كفر الشيخ – مصر

## الدعم | Supported by

تأسست الشركة عام 2026 ضمن **مشروع تعزيز الزراعة الذكية مناخياً والتنوع البيولوجي الزراعي لرفع القدرة على التكيف لدى المجتمعات الريفية الأكثر احتياجاً في الأراضي القديمة والجديدة بصعيد مصر والوجه البحري**.

- **الجهة المنفذة:** منظمة الأغذية والزراعة للأمم المتحدة (الفاو)
- **الجهة المانحة:** حكومة كندا
- **الشريك الوطني:** وزارة الزراعة واستصلاح الأراضي

*Founded in 2026 under the project "Promoting Climate Smart Agriculture and Agricultural Biodiversity for Enhancing the Adaptive Capacity of Vulnerable Rural Communities in Old and New Lands of Upper and Lower Egypt" – implemented by FAO, funded by the Government of Canada, with the Ministry of Agriculture and Land Reclamation.*

---

© 2026 Honey Elixir · إكسير العسل. جميع الحقوق محفوظة.
