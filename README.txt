ساخت APK (بدون هاست)
====================
روش ۱ - با GitHub (بدون نصب چیزی روی کامپیوتر):
1) یک مخزن (repository) خصوصی در GitHub بساز و همهٔ این فایل‌ها (با پوشهٔ .github) را در آن آپلود کن.
2) به تب Actions برو؛ کار «Build APK» خودش اجرا می‌شود (حدود ۵ تا ۱۰ دقیقه).
3) پس از سبز شدن، وارد آن اجرا شو و از بخش Artifacts فایل habits-apk را دانلود کن.
4) داخل آن app-debug.apk است؛ آن را به گوشی بفرست و نصب کن (اجازهٔ «نصب از منابع ناشناس» لازم است).

روش ۲ - روی کامپیوتر با Node.js و Android Studio:
   npm install
   npx cap add android
   npx cap sync android
   npx cap open android     (سپس در Android Studio: Build ← Build APK)

نکته: این APK از نوع debug است؛ برای استفادهٔ شخصی مشکلی ندارد، برای انتشار در مارکت باید امضا شود.
