<div align="center">

<img src="public/favicon.png" alt="SoofT Logo" width="90" />

# 🏆 SoofT Academy Management System
### سوفت | نظام إدارة الأكاديميات الرياضية الاحترافي

**نظام SaaS سحابي متكامل ومتعدد المستأجرين لإدارة الأكاديميات والنوادي الرياضية في المنطقة العربية**
**A complete multi-tenant cloud SaaS platform for professional sports academies & training clubs across the MENA region**

<br/>

[![Build](https://img.shields.io/badge/Build-Passing-22c55e?style=for-the-badge&logo=vite&logoColor=white)](#-local-development)
[![License](https://img.shields.io/badge/License-Proprietary-lightgrey?style=for-the-badge)](#-license)
[![Live](https://img.shields.io/badge/Live-academy.sooftit.com-0f3d2e?style=for-the-badge&logo=googlechrome&logoColor=white)](https://academy.sooftit.com)

<br/>

[![React](https://img.shields.io/badge/React-18.3-61dafb?style=flat-square&logo=react&logoColor=white)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178c6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Vite](https://img.shields.io/badge/Vite-5-646cff?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev)
[![Tailwind](https://img.shields.io/badge/Tailwind-3-38bdf8?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Supabase](https://img.shields.io/badge/Supabase-Cloud-3ECF8E?style=flat-square&logo=supabase&logoColor=white)](https://supabase.com)

</div>

---

## 🌍 العربية

### نظرة عامة

**SoofT** هو نظام سحابي احترافي ومتعدد المستأجرين (Multi-tenant SaaS) مصمم خصيصًا لتحويل إدارة الأكاديميات والنوادي الرياضية في المنطقة العربية إلى تجربة رقمية متكاملة وذكية. يدعم النظام اللغة العربية بشكل كامل (RTL افتراضيًا) مع دعم كامل للغة الإنجليزية، ويوفر عزلًا تامًا للبيانات على مستوى المؤسسة مع صلاحيات دقيقة مفروضة من قاعدة البيانات مباشرة.

---

### ✨ الوحدات والمميزات الرئيسية

#### 👥 إدارة اللاعبين
- تسجيل بالاسم الرباعي (بالعربية والإنجليزية)
- التحقق التلقائي من الرقم القومي المصري (استخراج تاريخ الميلاد والنوع والمحافظة)
- حساب العمر تلقائيًا وتحديد الفئة العمرية
- رفع الصور الشخصية والمرفقات (إثباتات — شهادات — وثائق)
- طباعة كروت التعريف (ID Cards) بقوالب قابلة للتخصيص الكامل
- استيراد بيانات اللاعبين من Excel مع معاينة ومراجعة قبل الحفظ
- تصدير البيانات إلى Excel
- اختصارات لوحة المفاتيح: F1 جديد، F2 إضافة، F3 تعديل، F4 حذف، F5 بحث، F7 طباعة

#### 🎯 إدارة الأنشطة
- هيكل هرمي من 4 مستويات: **نشاط رئيسي → نشاط فرعي → فئة عمرية → مستوى**
- تعيين المدربين لكل نشاط
- إدارة الجداول الزمنية والأوقات لكل مستوى

#### 💳 إدارة الاشتراكات
- إنشاء وإدارة الاشتراكات المرتبطة باللاعبين والأنشطة
- فواتير تلقائية مع دعم الضرائب والخصومات
- تجميد الاشتراكات بشكل فردي أو جماعي مع تمديد تلقائي للتواريخ
- تقارير إيرادات تفصيلية (يومية — أسبوعية — شهرية — سنوية)
- متابعة المبالغ المستحقة والمتأخرة
- إشعارات واتساب تلقائية قبل انتهاء الاشتراك

#### ✅ الحضور والانصراف
- تسجيل الحضور بالباركود (QR Code / Barcode)
- تسجيل يدوي مع اختيار التاريخ والوقت
- سجل حضور كامل مع إمكانية التصفية والتصدير
- تقارير الغياب والانتظام

#### 🏟️ إدارة الحجوزات
- حجز الملاعب والمنشآت مع التحقق من التعارض في المواعيد
- تتبع المدفوعات والمبالغ المتبقية لكل حجز
- تقارير الإشغال والإيرادات من الحجوزات
- إرسال تأكيد الحجز عبر واتساب

#### 💰 إدارة المصروفات
- تصنيف هرمي للمصروفات (فئة رئيسية — فئة فرعية)
- رفع صور الفواتير والإيصالات
- تقارير المصروفات مع فلترة حسب الفترة والفئة
- تصدير تقارير المصروفات إلى Excel

#### 👨‍🏫 إدارة المدربين
- ملفات تعريفية كاملة للمدربين مع الصور
- رفع الشهادات والمؤهلات
- ربط المدربين بالأنشطة والمستويات
- إدارة جداول المدربين

#### 📊 التقارير والتحليلات المتقدمة
- **لوحة التحكم الرئيسية (Dashboard):** مؤشرات KPI لحظية — رسوم بيانية تفاعلية — ملخص إيرادات
- **Player Insights:** تحليل عمقي لأداء وسلوك كل لاعب
- **إدارة المنقطعين (Inactive Subscribers):** رصد اللاعبين الغائبين وإرسال رسائل إعادة تفعيل
- **تقرير الإيرادات الأسبوعية:** رسم بياني ديناميكي قابل للتضمين في صفحات التسويق
- **مراقبة الأداء (Performance Monitor):** تتبع Web Vitals — LCP / FCP / TTFB — أحجام الحزم — أوقات تحميل كل صفحة

#### 📱 تكامل واتساب
- تكامل مع WhatsApp Business API
- إرسال رسائل فردية أو مجمعة لمجموعات محددة
- قوالب رسائل قابلة للتخصيص (تذكير — ترحيب — تهنئة — تسويق)
- متغيرات ديناميكية في القوالب (اسم اللاعب — تاريخ الانتهاء — المبلغ)
- لوحة إدارة حملات الرسائل مع تتبع الحالة

#### 🔐 نظام الصلاحيات المتقدم
- مصفوفة صلاحيات دقيقة لكل وحدة: **عرض — إضافة — تعديل — حذف — طباعة — تصدير**
- الصلاحيات مفروضة من قاعدة البيانات (RLS) وليس فقط من الواجهة
- أدوار مدمجة: `super_admin` — `admin` — أدوار مخصصة قابلة للإنشاء
- مراجعة كاملة لكل تغيير في الصلاحيات (Audit Log)

#### 🏢 دعم تعدد الفروع
- عزل تام للبيانات على مستوى المؤسسة (Multi-tenant)
- إدارة فروع متعددة ضمن نفس المؤسسة
- تقارير موحدة أو مفصلة لكل فرع

#### 🤖 المساعد الذكي (AI Assistant)
- **Chatbot تسويقي** لصفحات الهبوط والتواصل مع الزوار
- **Chatbot إداري** للإجابة على أسئلة الإدارة مع احترام الصلاحيات
- تحليل البيانات واقتراح الرؤى

#### ⚙️ الإعدادات والتخصيص
- إعدادات المؤسسة (الاسم — الشعار — العنوان — بيانات التواصل)
- تخصيص شامل (اللون الرئيسي — اسم الأكاديمية — العملة)
- إعداد البيانات الأولية (الأنشطة — الفئات — الأدوار)
- **Danger Zone:** حذف البيانات وإعادة الضبط (للمدير فقط)

#### 🖨️ الطباعة والتصدير
- طباعة تقارير احترافية مباشرة من المتصفح
- تصدير كل الجداول إلى Excel بنقرة واحدة
- قوالب بطاقات التعريف قابلة للتخصيص الكامل وطباعتها دفعة واحدة

#### 🌐 دعم ثنائي اللغة والوضع المظلم
- عربي (RTL) وإنجليزي (LTR) مع تبديل فوري بدون إعادة تحميل
- الأرقام إنجليزية دائمًا (0-9) في كل اللغات
- وضع مظلم / فاتح / تلقائي
- خطوط: **Cairo** (عربي) و **Inter** (إنجليزي)
- ألوان: **أخضر غابي عميق** + **ذهبي ملكي**

#### 📲 تطبيق ويب تقدمي (PWA)
- قابل للتثبيت على iOS وAndroid وسطح المكتب
- أيقونات لجميع الأحجام والمنصات
- متوافق مع معايير PWA (Lighthouse PWA Score)

---

### 🔒 البنية الأمنية

| الطبقة | التفاصيل |
|--------|----------|
| **RLS** | كل جدول مقيّد بـ Row-Level Security — قراءة بيانات مؤسسة أخرى مستحيلة فيزيائيًا |
| **الصلاحيات** | دالة `has_permission()` تُفحص من داخل سياسات RLS |
| **تشفير PII** | الرقم القومي والهاتف مشفران باستخدام `pgcrypto` |
| **Audit Logs** | سجل كامل لكل تعديل مع Before/After JSONB و IP و وقت |
| **التخزين** | دلو خاص للصور والمرفقات مع Signed URLs |
| **Edge Functions** | تحقق JWT + `has_permission()` قبل أي عملية حساسة |

---

## 🌍 English

### Overview

**SoofT** is a professional, multi-tenant cloud SaaS purpose-built for managing sports academies in the MENA region. It delivers first-class bilingual Arabic (RTL default) and English support, with branch-level data isolation, a fine-grained permission matrix enforced at the database layer (Supabase RLS), and a rich feature set covering every aspect of academy operations — from player onboarding and subscription billing to AI-assisted analytics and WhatsApp automation.

---

### ✨ Core Modules

| Module | Highlights |
|--------|-----------|
| 👥 **Players** | 4-part names · Egyptian National ID validation · auto age calculation · photos & attachments · ID card printing · Excel import/export |
| 🎯 **Activities** | 4-level hierarchy (Main → Sub → Age Category → Level) · trainer assignment · schedule management |
| 💳 **Subscriptions** | Auto-invoicing · tax & discounts · bulk freeze with auto date extension · revenue reports · overdue tracking |
| ✅ **Attendance** | Barcode (QR/barcode) or manual check-in · full history · absence reports |
| 🏟️ **Bookings** | Conflict-aware court scheduling · payment tracking · WhatsApp confirmations |
| 💰 **Expenses** | Hierarchical categories · receipt image uploads · filtered reports · Excel export |
| 👨‍🏫 **Trainers** | Full profiles · certifications · activity linking · schedule management |
| 📊 **Analytics** | KPI dashboard · Player Insights · Inactive Subscribers management · Weekly Revenue widget · Performance Monitor (Web Vitals) |
| 📱 **WhatsApp** | Business API integration · individual & bulk messaging · dynamic message templates · campaign tracking |
| 🔐 **Permissions** | 6-action matrix (view/add/edit/delete/print/export) per module · DB-enforced RLS · full audit trail |
| 🏢 **Multi-Branch** | Complete data isolation · per-branch or consolidated reports |
| 🤖 **AI Assistant** | Marketing chatbot · permission-aware admin analytics chatbot |
| ⚙️ **Settings** | Academy branding · role management · initial data setup · Danger Zone |
| 🖨️ **Print & Export** | Printable reports · Excel export on every table · customizable ID card templates |
| 🌐 **i18n** | Arabic RTL / English LTR · instant toggle · English digits always |
| 🌙 **Theming** | Dark / Light / System · Cairo + Inter fonts · Deep Forest Green + Royal Gold |
| 📲 **PWA** | Installable on iOS, Android, Desktop · Lighthouse PWA compliant |

---

## 🛠️ Tech Stack

| Layer | Technology | Version |
|------|------------|---------|
| UI Framework | React | `^18.3.1` |
| Language | TypeScript | `^5` |
| Build | Vite + `@vitejs/plugin-react-swc` | `^5` / `^3.11` |
| Routing | React Router | `^6.30` |
| Styling | Tailwind CSS + tailwindcss-animate + Typography | `^3` |
| UI Primitives | shadcn/ui on Radix UI | latest |
| Icons | lucide-react | `^0.462` |
| Data Fetching | TanStack Query | `^5.83` |
| Forms | react-hook-form + zod + @hookform/resolvers | `^7.61` / `^3.25` |
| Charts | Recharts | `^2.15` |
| Virtual Tables | @tanstack/react-virtual | `^3.13` |
| Dates | date-fns + react-day-picker | `^3.6` / `^8.10` |
| Excel | xlsx | `^0.18` |
| Notifications | sonner + Radix Toast | `^1.7` |
| Theming | next-themes | `^0.3` |
| Barcode | jsbarcode + qrcode | `^3.12` / `^1.5` |
| Backend | Supabase (PostgreSQL · Auth · Storage · Edge Functions · Realtime) | Cloud |
| Email | Resend (via Edge Function) | — |
| Tooling | Bun · ESLint 9 · Vitest · Testing Library | latest |

---

## 🚀 Local Development

### 1. Prerequisites

| Tool | Min version | Install |
|------|-------------|---------|
| Node.js | 18+ (20 LTS recommended) | https://nodejs.org |
| Bun *(recommended)* | 1.0+ | `curl -fsSL https://bun.sh/install \| bash` |
| Git | any | https://git-scm.com |

> You can use `npm`, `pnpm`, or `yarn` instead of Bun — just replace `bun` with the equivalent.

### 2. Clone & Install

```bash
git clone https://github.com/<your-org>/<your-repo>.git
cd <your-repo>

bun install
# or: npm install
```

### 3. Environment Variables

The project ships with a pre-generated `.env` file:

```env
VITE_SUPABASE_URL=https://<project-ref>.supabase.co
VITE_SUPABASE_PUBLISHABLE_KEY=<anon-key>
VITE_SUPABASE_PROJECT_ID=<project-ref>
```

> 🔒 Do not edit `.env` manually. Runtime secrets (e.g., `RESEND_API_KEY`, `PII_ENCRYPTION_KEY`) live in the Supabase Cloud dashboard and are only available to Edge Functions — they are never exposed to the client.

### 4. Run the Dev Server

```bash
bun run dev
# → http://localhost:8080
```

### 5. Common Scripts

| Command | What it does |
|--------|--------------|
| `bun run dev` | Start Vite dev server with HMR (port `8080`) |
| `bun run build` | Production build → `dist/` (no source maps) |
| `bun run build:dev` | Dev-mode build (with source maps, no minify) |
| `bun run preview` | Serve the production build locally |
| `bun run lint` | ESLint over the entire project |
| `bun run test` | Run the Vitest suite once |
| `bun run test:watch` | Vitest in watch mode |

---

## 🌐 Deployment (Apache / cPanel Shared Hosting)

### Build

```bash
bun run build
# Output: dist/
```

### Deploy

1. Upload the entire contents of `dist/` to your hosting's `public_html` (or subdomain root).
2. Upload the `.htaccess` file provided in this repository — **this file is critical**.
3. The `.htaccess` sets correct MIME types (`.mjs` → `application/javascript`), enables gzip, sets security headers, and handles the SPA fallback.

> ⚠️ Without the `.htaccess` MIME type fix, Apache serves `.mjs` files as `text/plain`, causing the browser to block ES module loading and showing a blank page.

### What the `.htaccess` provides

- ✅ **MIME types** for `.js`, `.mjs`, `.webmanifest`, `.woff2` — fixes blank page
- ✅ **HTTPS redirect** (301 permanent)
- ✅ **Security headers** — CSP, HSTS, X-Frame-Options, X-Content-Type-Options, Permissions-Policy
- ✅ **Gzip compression** — 60–80% smaller transfers
- ✅ **Long-term caching** for hashed assets (1 year) + `no-cache` for `index.html`
- ✅ **Source map blocking** — `.map` files are inaccessible from the web
- ✅ **Directory listing disabled**

---

## 🔒 Security Architecture

SoofT enforces security in defense-in-depth layers.

### 1. Multi-Tenant Isolation via Row-Level Security

Every table has RLS enabled with explicit `SELECT / INSERT / UPDATE / DELETE` policies, organization-scoped via a `SECURITY DEFINER` helper:

```sql
CREATE POLICY "org_select" ON public.players
  FOR SELECT TO authenticated
  USING (organization_id = public.get_user_org(auth.uid()));
```

Cross-tenant reads are **physically impossible** — even a misbehaving client cannot bypass RLS.

### 2. Fine-Grained Permission Matrix

```sql
SELECT has_permission(auth.uid(), 'players', 'export');
```

The `has_permission(_user_id, _module, _action)` function is called from RLS policies. Frontend permission gating is cosmetic — the database is the source of truth.

### 3. Column-Level PII Encryption

| Column | Table | Reason |
|--------|-------|--------|
| `national_id` | `players` | Egyptian National ID — regulated PII |
| `phone` | `players`, `guardians` | Personal contact data |
| `iban` | `payments` | Financial identifiers |
| WhatsApp tokens | `organization_secrets` | Credentials — never exposed to client |

Encrypted at rest with `pgcrypto`, decrypted only via `SECURITY DEFINER` functions.

### 4. Audit & Compliance

- `audit_logs` — Before/After JSONB snapshots for every sensitive change + `actor_id` + IP + timestamp
- `permission_audit_log` — Dedicated stream for role/permission changes
- `event_log` — Real-time in-app feed for high-severity events
- **Retention:** 12 months by default, extensible to 24–36 months

### 5. Storage Buckets

| Bucket | Public | Access |
|--------|--------|--------|
| `academy-logos` | ✅ | Public CDN |
| `user-avatars` | ✅ | Public CDN |
| `player-photos` | 🔒 | RLS-scoped, org-level only |
| `player-attachments` | 🔒 | Signed URLs, finance permission required |
| `expense-invoices` | 🔒 | Signed URLs, finance permission required |

---

## 📂 Project Structure

```
src/
├── pages/
│   ├── marketing/          # Public: Home, Features, Solutions, About, Contact
│   └── admin/              # Authenticated dashboard modules (all lazy-loaded)
├── components/             # Shared UI (ModuleLayout, DataTable, FormField…)
├── contexts/               # Language (i18n + RTL), Theme, Auth
├── hooks/                  # usePrintReport, useShortcuts, usePageTitle…
├── lib/                    # excel, pdf, validators, message templates, perfMonitor
└── integrations/
    └── supabase/           # Auto-generated client & types — DO NOT EDIT
supabase/
├── functions/              # Edge functions: backups, WhatsApp, AI, email
└── migrations/             # SQL migrations (schema + RLS policies)
public/
├── manifest.webmanifest    # PWA manifest
├── sitemap.xml             # SEO sitemap
├── robots.txt              # Crawler rules
└── *.png                   # PWA icons (192, 512, maskable, Apple touch)
```

---

## 🧪 Testing

```bash
bun run test          # one-off run
bun run test:watch    # interactive watch mode
```

Stack: **Vitest + @testing-library/react + @testing-library/jest-dom**.  
Tests live next to their components in `__tests__/` folders.

---

## 🌐 Live

🔗 **Production:** [https://academy.sooftit.com](https://academy.sooftit.com/)
🔗 **Corporate:** [https://sooftit.com](https://sooftit.com/)

---

## 👨‍💻 Developer & Company

<div>

**Ahmed — Sooft IT Solutions**  
مطور متخصص في بناء حلول برمجية متكاملة وعملية لأصحاب الأعمال والمؤسسات في المنطقة العربية.

> كل مشروع ناجح يبدأ بفكرة… لكن الفكرة تحتاج نظامًا يحوّلها إلى واقع.  
> في **Sooft IT Solutions** نساعدك على تحويل أفكارك وعملياتك اليومية إلى حلول برمجية وتقنية عملية، سهلة الاستخدام، وقابلة للتطوير حسب طبيعة عملك.

### خدماتنا

- 🖥️ برامج ديسك توب
- 🌐 أنظمة ويب ولوحات تحكم
- 📱 تطبيقات موبايل (Android & iOS)
- 🛒 متاجر إلكترونية وربط Shopify وسلة
- 🤖 حلول ذكاء اصطناعي وشات بوت
- ⚙️ أتمتة أعمال باستخدام n8n
- 🏥 أنظمة مبيعات، مخازن، عيادات، سناتر، مدارس، عقارات، وصيانة
- 📊 إدخال بيانات وتنظيم ملفات وتقارير
- 👥 فريق عمل عن بُعد لمتابعة العملاء والرد على الرسائل (WhatsApp / Facebook / Instagram / TikTok)

### التواصل

| القناة | الرابط |
|--------|--------|
| 🌐 Website | [sooftit.com](https://sooftit.com) |
| 📘 Facebook | [facebook.com/sooftitsolution](https://www.facebook.com/sooftitsolution) |
| 🎬 YouTube | [youtube.com/@sooftitsolutions](https://www.youtube.com/@sooftitsolutions) |
| 💼 Mostaql | [mostaql.com/u/asooft](https://mostaql.com/u/asooft) |
| 💼 Khamsat | [khamsat.com/user/ahmed-sooft](https://khamsat.com/user/ahmed-sooft) |
| 💼 Upwork | [upwork.com/freelancers/~01c9fd960a4fd2054a](https://www.upwork.com/freelancers/~01c9fd960a4fd2054a) |
| 📧 Email | [sales@sooftit.com](mailto:sales@sooftit.com) |
| 💬 WhatsApp | [+201015881992](http://wa.me/+201015881992) |

</div>

---

## 📄 License

Proprietary — © سوفت للبرمجيات وحلول التقنية / SoofT Software Solutions. All rights reserved.  
Unauthorized copying, distribution, or modification is strictly prohibited.  
Contact [sales@sooftit.com](mailto:sales@sooftit.com) for commercial licensing inquiries.

---

<div align="center">

**Made with 💚 for the sports academies community**  
**صُنع بـ 💚 لمجتمع الأكاديميات الرياضية**

[academy.sooftit.com](https://academy.sooftit.com) · [sooftit.com](https://sooftit.com) · [sales@sooftit.com](mailto:sales@sooftit.com)

</div>
