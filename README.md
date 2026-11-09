# Arma Daily Sales Report

تطبيق ويب لتسجيل المبيعات والتحصيلات اليومية لمندوبي أرما وعرض التقرير النهائي وتنزيله كصورة JPG.

## المحتوى
- `index.html` — التطبيق كامل في ملف واحد (تسجيل الدخول، الإدخالات، الجدول، التقرير النهائي).
- `vercel.json` — إعدادات النشر على Vercel.

## التشغيل
افتح `index.html` في أي متصفح، أو انشره على Vercel كموقع ثابت (Static) بدون أي Build.

## النشر على Vercel
1. ارفع الملفات على مستودع GitHub.
2. من Vercel: **Add New → Project** واختر المستودع.
3. Framework Preset: **Other** — بدون Build Command — Output Directory: `./`
4. اضغط **Deploy** وستحصل على رابط مثل `https://arma-daily-sales-report.vercel.app`.

## ملاحظات
- الدخول بالإيميل + كود الموزع المسجّل في قاعدة الأكواد داخل `index.html`. كود الأدمن: 102065.
- البيانات تُحفظ على جهاز المستخدم فقط (localStorage) ولا ترسل لأي خادم.
