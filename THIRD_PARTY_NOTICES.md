# إشعارات المصادر المفتوحة

## نمط عرض تقرير المخاطر

استُفيد في الإصدار 1.2.0 من البنية البرمجية لصفحة لوحة الحوكمة في مشروع:

- المشروع: [noamrazbuilds/ai-governance-register](https://github.com/noamrazbuilds/ai-governance-register)
- الملف المرجعي: [`agr_frontend/pages/1_Dashboard.py`](https://github.com/noamrazbuilds/ai-governance-register/blob/main/agr_frontend/pages/1_Dashboard.py)
- الجزء المستفاد منه: بطاقات الملخص، وترتيب فئات توزيع المخاطر مع ألوان ثابتة، وعرض حالات المتابعة في مخطط ملوّن.
- طريقة المواءمة: نُقلت البنية من Python وStreamlit وPlotly إلى HTML وCSS وJavaScript دون إضافة مكتبات خارجية، لتعمل الأداة محليًا داخل المتصفح.

### ترخيص MIT للمصدر

MIT License

Copyright (c) 2026 Noam Raz and Pleasant Secret Labs

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## خط الشعار

يستخدم شعار الأداة خط IBM Plex Sans Arabic من حزمة Fontsource، والخط منشور وفق SIL Open Font License 1.1. النص الكامل محفوظ في [FONT-LICENSE.txt](./FONT-LICENSE.txt).

## تصدير تقرير PDF

يستخدم الإصدار 1.3.0 مكتبتين مفتوحتي المصدر لتجهيز صفحتي التقرير وتنزيلهما مباشرة باسم ملف محدد:

- [html2canvas 1.4.1](https://www.npmjs.com/package/html2canvas) — ترخيص MIT، والنص محفوظ في [vendor/html2canvas-LICENSE.txt](./vendor/html2canvas-LICENSE.txt).
- [jsPDF 4.2.1](https://www.npmjs.com/package/jspdf) — ترخيص MIT، والنص محفوظ في [vendor/jspdf-LICENSE.txt](./vendor/jspdf-LICENSE.txt).
