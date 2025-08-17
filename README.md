📩 مشروع Contact Us بسيط (Laravel)

نظرة عامة

هذا مشروع بسيط لنموذج Contact Us مبني باستخدام Laravel.
يسمح للمستخدمين بإرسال رسائلهم، ويتم حفظها في قاعدة البيانات.

📝 الميزات

نموذج اتصل بنا (Contact Form)

حفظ الرسائل في قاعدة البيانات

تحقق من صحة البيانات (Validation)

إعادة توجيه المستخدم مع رسالة نجاح بعد الإرسال

🛠️ التثبيت

استنساخ المشروع:

git clone https://github.com/yourusername/contact-us.git
cd contact-us

تثبيت التبعيات:

composer install
npm install
npm run dev

إعداد ملف البيئة:

cp .env.example .env
php artisan key:generate

تشغيل المايجريشن:

php artisan migrate

تشغيل السيرفر:

php artisan serve

💻 الاستخدام

الوصول إلى نموذج الاتصال: /contact

إرسال البيانات ستتم معالجتها وحفظها في جدول contact_us

بعد الإرسال ستظهر رسالة نجاح للمستخدم

📂 هيكل المشروع

app/
├─ Http/
│  ├─ Controllers/
│  │  └─ ContactController.php
├─ Models/
│  └─ ContactUs.php
routes/
├─ web.php
resources/
├─ views/
│  └─ contact.blade.php
database/
├─ migrations/

🔐 الأمان

التحقق من صحة البيانات (Validation)

حماية المسارات باستخدام CSRF

🤝 المساهمة

يمكنك عمل فورك للمشروع وتقديم طلبات السحب.

📄 الترخيص


المشروع مفتوح المصدر ومجاني للاستخدام.

👨‍💻 المطور
تم تطوير هذا المشروع بالكامل بواسطة Mohamed Soliman باستخدام Laravel.

