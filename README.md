# مبانی داده‌کاوی

کتاب درسی متن‌باز «مبانی داده‌کاوی» برای دانشجویان سال‌های پایانی کارشناسی،
بر پایهٔ دو مرجع استاندارد:

- Han, J., Kamber, M., & Pei, J. — *Data Mining: Concepts and Techniques*
- Tan, P.-N., Steinbach, M., & Kumar, V. — *Introduction to Data Mining*

## ساختار مخزن

```
main.tex                 فایل اصلی — همهٔ فصل‌ها را فرامی‌خواند
frontmatter/              پیشگفتار
chapters/                 فصل‌های اصلی کتاب (۰۱ تا ۱۰)
appendices/                پیوست‌ها (پایتون، دیتاست‌ها)
figures/                   تصاویر و نمودارها
bibliography/references.bib   مراجع (BibLaTeX)
.github/workflows/build.yml   ساخت خودکار PDF با هر push
```

## کامپایل محلی

نیازمند توزیع کامل TeX Live (یا MacTeX) به همراه فونت فارسی (مثلاً XB Niloofar یا Vazirmatn):

```bash
latexmk -xelatex -interaction=nonstopmode main.tex
```

## مشارکت

پیشنهادها و اصلاحیه‌ها را از طریق Pull Request یا Issue ارسال کنید.

## مجوز

این اثر تحت مجوز Creative Commons BY-NC-SA 4.0 منتشر می‌شود.
