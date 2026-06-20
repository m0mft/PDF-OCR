# PDF OCR Awesome

A fully automated GitHub Actions workflow to extract text from PDF files using Advanced Machine Learning (EasyOCR). Simply push your PDF files to this repository, and it will automatically generate and upload the extracted text to GitHub Releases!

---

## 🇬🇧 English

### Features
- **Advanced Machine Learning**: Uses `EasyOCR` and PyTorch for highly accurate text extraction.
- **Multilingual Support**: Supports Persian (Farsi), Arabic, and English out of the box!
- **Fully Automated**: Automatically triggers whenever a `.pdf` file is pushed to the repository.
- **Manual Trigger**: Can also be run manually from the **Actions** tab.
- **Auto-Grouping**: Logically groups mixed text lines into paragraphs.

### How to Use
1. **Option A: Push a PDF**
   - Simply upload or push any `.pdf` file into this repository.
   - The workflow will automatically start running in the background.
2. **Option B: Manual Trigger**
   - Go to the **Actions** tab.
   - Select the `Advanced PDF OCR (EasyOCR)` workflow.
   - Click **Run workflow**.

Once the workflow finishes, go to the **Releases** section on the right side of the repository to download your extracted `.txt` files!

### Requirements
- No local setup required. Everything runs on GitHub's cloud servers!

---

## 🇮🇷 فارسی (Persian)

### ویژگی‌ها
- **یادگیری ماشین پیشرفته**: استفاده از `EasyOCR` و PyTorch برای استخراج دقیق متن از تصاویر و فایل‌های PDF.
- **پشتیبانی چندزبانه**: پشتیبانی کامل از زبان‌های فارسی، عربی و انگلیسی به صورت پیش‌فرض.
- **کاملاً خودکار**: با آپلود یا پوش (Push) کردن هر فایل `.pdf` در این مخزن، عملیات پردازش به صورت خودکار آغاز می‌شود.
- **اجرای دستی**: امکان اجرای دستی ورک‌فلو از طریق تب **Actions**.
- **پاراگراف‌بندی خودکار**: تشخیص و گروه‌بندی خطوط متن به صورت منطقی برای خروجی خواناتر.

### نحوه استفاده
۱. **روش اول: آپلود فایل PDF**
   - هر فایل `.pdf` دلخواهی را در این مخزن آپلود کنید (از طریق سایت گیت‌هاب یا Git).
   - ورک‌فلو به صورت خودکار در پس‌زمینه شروع به کار می‌کند.
۲. **روش دوم: اجرای دستی**
   - به تب **Actions** بروید.
   - ورک‌فلوی `Advanced PDF OCR (EasyOCR)` را انتخاب کنید.
   - روی دکمه **Run workflow** کلیک کنید.

پس از پایان یافتن پردازش، به بخش **Releases** در سمت راست صفحه مخزن بروید تا فایل‌های متنی (`.txt`) استخراج‌شده را دانلود کنید!

### پیش‌نیازها
- هیچ نیازی به نصب برنامه‌های محلی نیست. همه چیز روی سرورهای ابری گیت‌هاب اجرا می‌شود!