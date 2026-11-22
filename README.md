# محرر الصور — مشروع أندرويد

التطبيق ده صفحة الويب بتاعة المحرر (في app/src/main/assets/index.html) جوه WebView، مع جسر بيحفظ الصورة المعدلة في معرض الصور (Pictures/PhotoEditor).

## الطريقة 1: من غير Android Studio (GitHub Actions)
1. اعمل حساب على github.com وأنشئ Repository جديد (Private أو Public).
2. ارفع كل محتويات الفولدر ده (لازم فولدر `.github` يترفع كمان).
3. افتح تبويب **Actions** ← **Build APK** ← **Run workflow**.
4. بعد حوالي 5 دقايق نزّل الملف `PhotoEditor-apk` من آخر تشغيل، وفك الضغط هتلاقي `app-debug.apk`.
5. ثبّته على الهاتف (اسمح بالتثبيت من مصادر غير معروفة لو طلب).

## الطريقة 2: Android Studio
1. افتح الفولدر ده في Android Studio واستنى الـ Sync.
2. Build ← Build Bundle(s) / APK(s) ← Build APK(s).

## ملاحظات
- أقل إصدار أندرويد 10 (API 29).
- الأيقونة (وردة بتلات ملوّنة) رسم أصلي، ومعمولة كـ Adaptive Icon فبتتقص صح على أي شكل أيقونة.
- المشروع ده ماتبنيش على جهازي، فلو ظهر خطأ في البناء ابعتلي نص الخطأ.
