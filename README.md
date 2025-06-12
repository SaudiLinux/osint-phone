# أداة Dork-Google

أداة مكتوبة بلغة Python للبحث عن Google Dorks من قاعدة بيانات Exploit-DB GHDB (Google Hacking Database).

## المميزات

- البحث في قاعدة بيانات Exploit-DB GHDB
- تصفية النتائج حسب الفئة أو المؤلف
- عرض النتائج بألوان مميزة في الطرفية
- حفظ النتائج تلقائياً في ملف JSON
- معالجة متوازية للبحث السريع

## المتطلبات

- Python 3.7 أو أحدث
- المكتبات المطلوبة:
  - requests
  - beautifulsoup4
  - colorama

## التثبيت

1. تأكد من تثبيت Python على جهازك
2. قم بتثبيت المكتبات المطلوبة:
```bash
pip install -r requirements.txt