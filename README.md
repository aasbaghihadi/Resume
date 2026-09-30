# سایت شخصی هادی اسبقی

سایت ایستا (HTML/CSS/JS) بدون Backend و Build، آماده برای GitHub Pages.

## ساختار
```
index.html  style.css  script.js  assets/profile-1.jpg  assets/profile-2.jpg
```

## اجرا روی سیستم
فایل `index.html` را در مرورگر باز کنید. فونت Vazirmatn از Google Fonts بارگذاری می‌شود؛ بدون اینترنت از فونت سیستم استفاده می‌شود.

## تصاویر
- `assets/profile-1.jpg`: پرتره Hero
- `assets/profile-2.jpg`: بخش درباره (سیاه‌وسفید، با هاور رنگی می‌شود)
برای تعویض، فایل جدید را با همین نام جایگزین کنید (ترجیحاً زیر ۳۰۰KB).

## تغییر اطلاعات
- متن‌ها: مستقیماً در `index.html`
- رنگ‌ها: متغیرهای بالای `style.css` (`--navy`, `--teal`, ...)
- **لینک LinkedIn:** در `index.html` عبارت `YOUR-LINKEDIN` را عوض کنید.
- **آدرس سایت:** `YOUR-USERNAME` و `YOUR-REPO` را در تگ canonical و og:image عوض کنید.
- شماره تماس عمداً درج نشده است؛ اگر خواستید، در بخش `.contact` اضافه کنید.

## انتشار روی GitHub Pages
1. در GitHub یک Repository بسازید (مثلاً `hadi-asbaghi`).
2. همه فایل‌ها را در ریشه آپلود کنید یا:
```bash
git init && git add . && git commit -m "Personal site"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```
3. Settings ← Pages ← Source: `Deploy from a branch` ← Branch: `main` / `(root)` ← Save.
4. بعد از حدود یک دقیقه: `https://USERNAME.github.io/REPO/`
