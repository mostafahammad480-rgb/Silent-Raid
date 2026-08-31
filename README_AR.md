# SILENT RAID — نسخة Android

هذا المشروع يغلف نسخة HTML/CSS/JavaScript الأصلية داخل WebView لتعمل كتطبيق Android.

## البناء

استخدم workflow: `.github/workflows/build-apk.yml`.

شغّله يدويًا من GitHub Actions وأدخل tag مثل `v1.0.0`. workflow يبني APK، يحفظ نسخة Artifact، ثم ينشر APK وملف SHA-256 في GitHub Release.

للتجربة الشخصية يكفي APK الـdebug. للتوزيع النهائي استخدم مفتاح Release خاصًا تملكه أنت.
