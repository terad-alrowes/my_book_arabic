# مصمم الكتب الاحترافي | Professional Book Designer

<div align="center">

![Hero Banner](https://private-us-east-1.manuscdn.com/sessionFile/YiPA6bEytl1nu9JttRYLzs/sandbox/18HfV2hniBAtfX9Iuhtyjr-img-1_1770726667000_na1fn_aGVyby1iYWNrZ3JvdW5k.png?x-oss-process=image/resize,w_1920,h_1920/format,webp/quality,q_80&Expires=1798761600&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvWWlQQTZiRXl0bDFudTlKdHRSWUx6cy9zYW5kYm94LzE4SGZWMmhuaUJBdGZYOUl1aHR5anItaW1nLTFfMTc3MDcyNjY2NzAwMF9uYTFmbl9hR1Z5YnkxaVlXTnJaM0p2ZFc1ay5wbmc~eC1vc3MtcHJvY2Vzcz1pbWFnZS9yZXNpemUsd18xOTIwLGhfMTkyMC9mb3JtYXQsd2VicC9xdWFsaXR5LHFfODAiLCJDb25kaXRpb24iOnsiRGF0ZUxlc3NUaGFuIjp7IkFXUzpFcG9jaFRpbWUiOjE3OTg3NjE2MDB9fX1dfQ__&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=ikpV6y5N986KBcOgKlzzT7ql1dbNCunT5TZC4UWVPmmDeBBtr8JeMjt7VNTcNH~3ixKNeXkJQOJcl6YqbiGVkI09i1MmCbe2aoYbHYpWy2-VxtxfIi1kF17oX2o991C9YUrazo8g~o2DNKVEpQ37ySL-KkgCVbrAfs0dQzS7F7tGZCazPerLS5PaRG-NfVBMU8XjZsbGq5SWOUFJRvJxQ4rv2g5dtTtiBIKDzuLzERkJBshRb8eHsH2op11XjA~WLs~HtrZ4jV~RCBat3MUGlmPee45bJfTRJ7sq~jMU0cxw~hVChuHvBCvO6GM5ianMyaYuNl1M~MLECzYw05bajw__)

**منصة ويب شاملة لتصميم وإنتاج الكتب الرقمية والمطبوعة**

**A comprehensive web platform for designing and producing digital and print books**

[العربية](#العربية) • [English](#english)

</div>

---

## العربية

### نظرة عامة

**مصمم الكتب الاحترافي** هو تطبيق ويب متقدم مصمم لتمكين المؤلفين والكتّاب من إنشاء كتب احترافية جاهزة للنشر. يتميز التطبيق بدعم كامل للغتين العربية والإنجليزية، مع واجهة مستخدم جميلة مستوحاة من الطبيعة تُعرف بـ "الحديقة الأدبية الرقمية".

### الميزات الرئيسية

- ✨ **دعم متعدد اللغات**: دعم كامل للعربية والإنجليزية مع RTL/LTR
- 📝 **محرر نصوص غني**: محرر متقدم مبني على TipTap مع تنسيقات شاملة
- 📚 **إدارة الفصول**: نظام متكامل لإدارة وترتيب الفصول
- 🎨 **تصميم عضوي**: واجهة جميلة بألوان طبيعية دافئة
- 📄 **تصدير PDF احترافي**: توليد ملفات PDF عالية الجودة مع غلاف وفهرس
- 🌐 **عمل دون اتصال**: حفظ محلي للبيانات في المتصفح
- 🔒 **خصوصية كاملة**: لا توجد خوادم خارجية، جميع البيانات محلية

### التقنيات المستخدمة

| التقنية | الاستخدام |
|---------|-----------|
| **React 19** | مكتبة واجهة المستخدم |
| **TypeScript** | لغة البرمجة الأساسية |
| **TailwindCSS 4** | إطار عمل التصميم |
| **TipTap** | محرر النصوص الغني |
| **Zustand** | إدارة الحالة |
| **jsPDF** | توليد ملفات PDF |
| **html2canvas** | تحويل HTML إلى صور |
| **Vite** | أداة البناء والتطوير |
| **Wouter** | التوجيه (Routing) |

### البنية المعمارية

```
client/
├── src/
│   ├── components/      # المكونات القابلة لإعادة الاستخدام
│   │   ├── ui/         # مكونات shadcn/ui
│   │   └── RichTextEditor.tsx  # محرر النصوص
│   ├── pages/          # صفحات التطبيق
│   │   ├── Home.tsx    # الصفحة الرئيسية
│   │   ├── Editor.tsx  # صفحة المحرر
│   │   └── NotFound.tsx
│   ├── store/          # إدارة الحالة
│   │   └── bookStore.ts  # حالة الكتاب
│   ├── lib/            # المكتبات المساعدة
│   │   └── pdfGenerator.ts  # توليد PDF
│   ├── contexts/       # React Contexts
│   ├── hooks/          # Custom Hooks
│   ├── App.tsx         # المكون الرئيسي
│   ├── main.tsx        # نقطة الدخول
│   └── index.css       # الأنماط العامة
├── public/             # الملفات الثابتة
└── index.html          # HTML الرئيسي
```

### التثبيت والتشغيل

#### المتطلبات الأساسية

- Node.js 18+ أو أحدث
- pnpm 8+ (أو npm/yarn)

#### خطوات التثبيت

```bash
# استنساخ المستودع
git clone <repository-url>
cd book-designer

# تثبيت الاعتماديات
pnpm install

# تشغيل خادم التطوير
pnpm dev

# بناء للإنتاج
pnpm build

# معاينة البناء
pnpm preview
```

### الاستخدام

1. افتح المتصفح وانتقل إلى `http://localhost:3000`
2. انقر على "ابدأ الآن" للانتقال إلى المحرر
3. قم بإعداد معلومات الكتاب من "إعدادات الكتاب"
4. أضف الفصول واكتب المحتوى
5. صدّر الكتاب بصيغة PDF

### التخصيص

#### تغيير الألوان

يمكنك تخصيص لوحة الألوان من ملف `client/src/index.css`:

```css
:root {
  --primary: oklch(0.48 0.08 140); /* Warm Olive Green */
  --background: oklch(0.89 0.03 85); /* Sandy Beige */
  /* ... المزيد من الألوان */
}
```

#### تغيير الخطوط

لتغيير الخطوط، قم بتحديث ملف `client/index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont&display=swap" rel="stylesheet" />
```

ثم حدّث المتغيرات في `index.css`:

```css
@theme inline {
  --font-heading-ar: 'YourArabicFont', serif;
  --font-body-ar: 'YourArabicFont', serif;
}
```

### المساهمة

نرحب بالمساهمات من الجميع! إذا كنت ترغب في المساهمة:

1. قم بعمل Fork للمستودع
2. أنشئ فرعًا جديدًا (`git checkout -b feature/amazing-feature`)
3. قم بإجراء التغييرات والالتزام بها (`git commit -m 'Add amazing feature'`)
4. ادفع إلى الفرع (`git push origin feature/amazing-feature`)
5. افتح Pull Request

### الترخيص

هذا المشروع مرخص تحت رخصة MIT - انظر ملف [LICENSE](LICENSE) للتفاصيل.

### الدعم

إذا واجهت أي مشكلة أو كان لديك اقتراح:

- افتح Issue في GitHub
- راجع [دليل المستخدم](USER_GUIDE.md) للحصول على مساعدة مفصلة

---

## English

### Overview

**Professional Book Designer** is an advanced web application designed to empower authors and writers to create professional, publication-ready books. The application features full support for Arabic and English languages, with a beautiful nature-inspired user interface known as the "Digital Literary Garden."

### Key Features

- ✨ **Multilingual Support**: Full Arabic and English support with RTL/LTR
- 📝 **Rich Text Editor**: Advanced TipTap-based editor with comprehensive formatting
- 📚 **Chapter Management**: Integrated system for managing and organizing chapters
- 🎨 **Organic Design**: Beautiful interface with warm natural colors
- 📄 **Professional PDF Export**: High-quality PDF generation with cover and table of contents
- 🌐 **Offline Capable**: Local data storage in browser
- 🔒 **Complete Privacy**: No external servers, all data is local

### Technology Stack

| Technology | Purpose |
|-----------|---------|
| **React 19** | UI library |
| **TypeScript** | Primary programming language |
| **TailwindCSS 4** | Design framework |
| **TipTap** | Rich text editor |
| **Zustand** | State management |
| **jsPDF** | PDF generation |
| **html2canvas** | HTML to image conversion |
| **Vite** | Build tool and dev server |
| **Wouter** | Routing |

### Architecture

```
client/
├── src/
│   ├── components/      # Reusable components
│   │   ├── ui/         # shadcn/ui components
│   │   └── RichTextEditor.tsx  # Text editor
│   ├── pages/          # Application pages
│   │   ├── Home.tsx    # Landing page
│   │   ├── Editor.tsx  # Editor page
│   │   └── NotFound.tsx
│   ├── store/          # State management
│   │   └── bookStore.ts  # Book state
│   ├── lib/            # Utility libraries
│   │   └── pdfGenerator.ts  # PDF generation
│   ├── contexts/       # React Contexts
│   ├── hooks/          # Custom Hooks
│   ├── App.tsx         # Main component
│   ├── main.tsx        # Entry point
│   └── index.css       # Global styles
├── public/             # Static files
└── index.html          # Main HTML
```

### Installation & Setup

#### Prerequisites

- Node.js 18+ or newer
- pnpm 8+ (or npm/yarn)

#### Installation Steps

```bash
# Clone the repository
git clone <repository-url>
cd book-designer

# Install dependencies
pnpm install

# Run development server
pnpm dev

# Build for production
pnpm build

# Preview build
pnpm preview
```

### Usage

1. Open browser and navigate to `http://localhost:3000`
2. Click "Start Now" to go to the editor
3. Set up book information from "Book Settings"
4. Add chapters and write content
5. Export the book as PDF

### Customization

#### Changing Colors

You can customize the color palette in `client/src/index.css`:

```css
:root {
  --primary: oklch(0.48 0.08 140); /* Warm Olive Green */
  --background: oklch(0.89 0.03 85); /* Sandy Beige */
  /* ... more colors */
}
```

#### Changing Fonts

To change fonts, update `client/index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont&display=swap" rel="stylesheet" />
```

Then update variables in `index.css`:

```css
@theme inline {
  --font-heading-ar: 'YourArabicFont', serif;
  --font-body-ar: 'YourArabicFont', serif;
}
```

### Contributing

We welcome contributions from everyone! If you'd like to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make changes and commit (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Support

If you encounter any issues or have suggestions:

- Open an Issue on GitHub
- Check the [User Guide](USER_GUIDE.md) for detailed help

---

<div align="center">

**Built with ❤️ by Manus AI**

**مصنوع بـ ❤️ بواسطة Manus AI**

</div>


