# Silent Raid — Android Fullscreen Fixed

هذه الحزمة مبنية من النسخة الأصلية مع تعديلات Android فقط لمعالجة:

- Landscape + Fullscreen/Immersive.
- الحفاظ على مساحة اللعبة الأصلية 800×600 بنسبة 4:3 داخل شاشة الهاتف بدون قص.
- الحفاظ على ملفات الصوت ونظام WebView الأصلي الذي كان يعمل.
- أيقونة التطبيق موجودة.

لا تغيّر ملفات `app/src/main/assets/game/index.html` أو `style.css` أو `script.js` يدويًا قبل الاختبار.

البناء يتم من GitHub Actions عبر `.github/workflows/build-apk.yml`.
