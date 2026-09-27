# هنرجو یار v2 — GitHub Pages / PWA

نسخه بازطراحی‌شده بر اساس طرح مرجع انتخاب‌شده: سبز تیره، سبز ملایم، سفید/کرم، کارت‌های نرم و ناوبری پایین.

## انتشار با گوشی
1. محتویات این پوشه را در ریشه Repository قرار بده؛ `index.html` باید در ریشه باشد.
2. GitHub → Settings → Pages → Source: Deploy from a branch → Branch: شاخه‌ای که فایل‌ها را داخل آن گذاشتی → `/(root)` → Save.
3. پس از انتشار، لینک GitHub Pages را باز کن.
4. لینک HTTPS سایت را می‌توان برای PWA Builder استفاده کرد.

## نکته
میکروفون در مرورگر نیاز به HTTPS و اجازه Microphone دارد. تشخیص pitch و ضربه برای تمرین/کوک آموزشی است و جای ارزیابی استاد را نمی‌گیرد.


## Android Studio
پوشه `android-studio` یک پروژه Android آماده دارد. در Android Studio همین پوشه را Open کن. WebView از `WebViewAssetLoader` استفاده می‌کند و دسترسی میکروفون برای تیونر/تمرین در Manifest و MainActivity پیش‌بینی شده است.

Debug APK: `app/build/outputs/apk/debug/app-debug.apk`
