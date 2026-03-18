# Kuro Cursor Packs

هذا الريبو يحتوي على حزم أسهم لتطبيق Kuro.

## الصيغة
يوجد ملف `catalog.json` في الجذر ويحتوي قائمة الحزم وروابطها.

كل حزمة داخل `packages/<id>/` وتحتوي:
- `cursor.png`
- `preview.png`
- `package.zip` (يضم الملفات أعلاه)

## إضافة حزمة جديدة
1. أنشئ مجلد داخل `packages/`.
2. ضع ملف `cursor.png` (و`preview.png` اختياريًا).
3. أعد توليد `package.zip`.
4. حدث `catalog.json` بروابط raw.
