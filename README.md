# 🏗️ Muta Peimayesh (موتا پیمایش) - وبسایت شرکت مهندسی نقشه‌برداری / Surveying Engineering Company

<div align="center">
  <img src="https://github.com/user-attachments/assets/efa50cc6-6529-4d32-ae12-6c1af3b4bb83" alt="Muta Peimayesh Logo" width="150"/>

  <br/>
  <h3>مدیریت، نمایش و پیگیری پروژه‌های نقشه‌برداری | Surveying Project Management & Portal</h3>
</div>

<br/>

<div align="center">
  
  ![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-10.0-512BD4?logo=dotnet)
  ![Entity Framework Core](https://img.shields.io/badge/EF_Core-10.0-512BD4?logo=entity-framework)
  ![SQL Server](https://img.shields.io/badge/SQL_Server-2022-CC2927?logo=microsoft-sql-server)
  ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-06B6D4?logo=tailwind-css)
  ![Clean Architecture](https://img.shields.io/badge/Architecture-Clean-FF6F00)
  ![License](https://img.shields.io/badge/License-MIT-green)
  
</div>

---

## 📋 فهرست مطالب | Table of Contents

- [معرفی پروژه | Project Overview](#-معرفی-پروژه--project-overview)
- [ویژگی‌ها و قابلیت‌ها | Features](#-ویژگی‌ها-و-قابلیت‌ها--features)
- [تصاویر | Screenshots](#-تصاویر--screenshots)
- [تکنولوژی‌ها و ابزارهای استفاده شده | Technologies & Tools](#-تکنولوژی‌ها-و-ابزارهای-استفاده-شده--technologies--tools)
- [ساختار پروژه | Project Structure](#-ساختار-پروژه--project-structure)
- [معماری | Architecture](#-معماری--architecture)

---

## 📖 معرفی پروژه | Project Overview

### فارسی 🇮🇷

وبسایت **موتا پیمایش** یک وب‌سایت شرکتی کامل و حرفه‌ای برای شرکت مهندسی نقشه‌برداری است که با مدیریت **مهندس رضا گلبابایی** فعالیت می‌کند. این پروژه با استفاده از معماری تمیز (Clean Architecture) و الگوهای مدرن طراحی شده است.

این وب‌سایت به عنوان یک **درگاه ارتباطی جامع** بین شرکت و مشتریان عمل می‌کند و امکانات زیر را فراهم می‌سازد:

- **بخش عمومی:** معرفی شرکت، خدمات، پروژه‌های انجام شده، نمونه کارها و اطلاعات تماس
- **پرتفولیو:** نمایش پروژه‌های نقشه‌برداری با جزئیات کامل، گالری تصاویر و توضیحات تخصصی
- **پنل کاربری (کلاینت):** مشتریان می‌توانند پس از ورود به حساب کاربری خود، پروژه‌هایشان را مشاهده کرده و فایل‌های مربوطه را دانلود کنند
- **پنل مدیریت:** مدیریت کامل محتوای سایت شامل پروژه‌ها، کاربران، تنظیمات صفحه اصلی، نمونه کارها، نظرات و سایر بخش‌ها

<br/>

### English 🇬🇧

**Muta Peimayesh** is a full-featured corporate website for an Iranian surveying engineering company managed by **Engineer Reza Golbabaei**. The project is built using Clean Architecture and modern software design patterns.

The website serves as a **comprehensive communication portal** between the company and its clients, providing:

- **Public Section:** Company introduction, services, completed projects, portfolio, and contact information
- **Portfolio:** Detailed surveying project showcase with image galleries and technical descriptions
- **Client Portal:** Registered clients can log in to view their projects and download associated files
- **Admin Panel:** Complete content management for projects, users, home settings, portfolio items, comments, and more

---

## ✨ ویژگی‌ها و قابلیت‌ها | Features

### فارسی 🇮🇷

#### 🌐 بخش عمومی (Public)

| ویژگی | توضیح |
|--------|--------|
| **صفحه اصلی** | معرفی شرکت، آخرین پروژه‌ها، خدمات و اطلاعات تماس به صورت یکپارچه |
| **درباره ما** | معرفی تیم، سابقه و افتخارات شرکت |
| **خدمات** | نمایش خدمات تخصصی نقشه‌برداری شامل نقشه‌برداری زمینی، هوایی، هیدروگرافی، ژئودزی و... |
| **نمونه کارها (پرتفولیو)** | نمایش پروژه‌های انجام شده با تصاویر، توضیحات و جزییات فنی |
| **تماس با ما** | فرم ارتباطی و اطلاعات تماس شرکت |
| **طراحی واکنش‌گرا** | نمایش بهینه در تمام دستگاه‌ها (موبایل، تبلت، دسکتاپ) |

#### 🔐 پنل کاربری (Client Portal)

| ویژگی | توضیح |
|--------|--------|
| **ورود/ثبت‌نام** | احراز هویت با امنیت بالا (رمزنگاری PBKDF2) |
| **پروژه‌های من** | مشاهده لیست پروژه‌های اختصاصی هر کاربر |
| **دانلود فایل‌ها** | دانلود فایل‌های مرتبط با پروژه با لینک‌های امن GUID |
| **ویرایش پروفایل** | مدیریت اطلاعات حساب کاربری |
| **تغییر رمز عبور** | تغییر رمز عبور با تأیید امنیتی |

#### 🛠️ پنل مدیریت (Admin Dashboard)

| ویژگی | توضیح |
|--------|--------|
| **مدیریت پروژه‌ها** | افزودن، ویرایش و حذف پروژه‌های نقشه‌برداری |
| **مدیریت کاربران** | ایجاد کاربران جدید، مدیریت دسترسی‌ها و نقش‌ها |
| **تنظیمات صفحه اصلی** | مدیریت محتوای داینامیک صفحه اصلی |
| **مدیریت نمونه کارها** | آپلود و مدیریت گالری تصاویر و نمونه‌کارها |
| **مدیریت فایل‌ها** | آپلود فایل‌های خصوصی و عمومی برای پروژه‌ها |
| **مدیریت نظرات** | بررسی و مدیریت نظرات کاربران |
| **آپلود با نمایش پیشرفت** | نمایش درصد پیشرفت آپلود فایل‌ها با نوار پیشرفت |

<br/>

### English 🇬🇧

#### 🌐 Public Section

| Feature | Description |
|---------|-------------|
| **Home Page** | Unified company introduction, latest projects, services, and contact info |
| **About Us** | Team introduction, company history and achievements |
| **Services** | Specialized surveying services including land surveying, aerial surveying, hydrography, geodesy, and more |
| **Portfolio** | Completed projects showcase with images, descriptions, and technical details |
| **Contact Us** | Contact form and company information |
| **Responsive Design** | Optimized display across all devices (mobile, tablet, desktop) |

#### 🔐 Client Portal

| Feature | Description |
|---------|-------------|
| **Login/Register** | High-security authentication (PBKDF2 hashing) |
| **My Projects** | View user-specific project list |
| **File Downloads** | Download project-related files with secure GUID links |
| **Profile Management** | Account information management |
| **Change Password** | Secure password change with verification |

#### 🛠️ Admin Dashboard

| Feature | Description |
|---------|-------------|
| **Project Management** | Add, edit, and delete surveying projects |
| **User Management** | Create users, manage permissions and roles |
| **Home Settings** | Dynamic home page content management |
| **Portfolio Management** | Upload and manage image galleries and portfolio items |
| **File Management** | Upload private and public files for projects |
| **Comment Management** | Review and manage user comments |
| **Upload Progress** | File upload progress bar with percentage display |

---

## 📸 تصاویر | Screenshots

<div align="center">

### صفحه اصلی | Home Page
<img src="https://github.com/user-attachments/assets/3400f8d4-2188-469b-a774-150f5bb564e0" alt="Home Page Screenshot" width="800"/>

<br/><br/>

### پنل ورود کاربران | Login Page
<img src="https://github.com/user-attachments/assets/c73f5c2e-594c-4f8c-bdb9-b62f8edf5f39" alt="Login Screenshot" width="800"/>

<br/><br/>

### پنل کاربری | Client Dashboard
<img src="https://github.com/user-attachments/assets/b08ccfa6-8546-41dc-a4e1-192b5fed82f5" alt="Client Dashboard Screenshot" width="800"/>

<br/><br/>

### پنل مدیریت | Admin Dashboard
<img src="https://github.com/user-attachments/assets/7e9e524b-79f2-4035-9697-ed8e637d1f9c" alt="Admin Dashboard Screenshot" width="800"/>

<br/><br/>

### مدیریت پروژه‌ها در پنل ادمین | Admin Project Management
<img src="https://github.com/user-attachments/assets/20121065-91ab-418a-a007-93dae02796a4" alt="Admin Projects Screenshot" width="800"/>

<br/><br/>

### صفحه دانلود فایل‌ها | File Download Page
<img src="https://github.com/user-attachments/assets/b2ad1a80-3fca-41ba-8bed-a95ace49dc5a" alt="File Download Screenshot" width="800"/>

<br/><br/>

### صفحه موبایل | Mobile Responsive View
<img src="https://github.com/user-attachments/assets/e7f0deeb-35f0-4f3c-8a4d-ba3c27da2fc0" alt="Mobile View Screenshot" width="800"/>

</div>

---

## 🛠️ تکنولوژی‌ها و ابزارهای استفاده شده | Technologies & Tools

### فارسی 🇮🇷

#### فناوری‌های اصلی

| تکنولوژی | کاربرد |
|-----------|--------|
| **ASP.NET Core 10 MVC** | فریمورک اصلی بک‌اند |
| **Entity Framework Core 8** | ORM و ارتباط با دیتابیس |
| **SQL Server 2026** | پایگاه داده اصلی |
| **C# 12** | زبان برنامه‌نویسی بک‌اند |
| **Clean Architecture** | معماری تمیز در ۵ لایه |
| **AutoMapper** | نگاشت خودکار بین مدل‌ها و ViewModel‌ها |
| **Repository Pattern** | الگوی مخزن برای دسترسی به داده |
| **Service Layer** | لایه سرویس برای منطق کسب و کار |

#### فناوری‌های فرانت‌اند

| تکنولوژی | کاربرد |
|-----------|--------|
| **Tailwind CSS 3** | فریمورک CSS مدرن برای طراحی ظاهری |
| **jQuery** | کتابخانه جاوااسکریپت برای تعاملات سمت کاربر |
| **Font Awesome 6** | آیکون‌های حرفه‌ای |
| **Vazirmatn Font** | فونت فارسی استاندارد و زیبا |
| **Vanilla JavaScript** | اسکریپت‌های سفارشی مانند آپلود با پیشرفت |

#### امنیت

| ابزار | کاربرد |
|-------|--------|
| **Cookie Authentication** | احراز هویت مبتنی بر کوکی با انقضای لغزنده |
| **PBKDF2 Hashing** | رمزنگاری امن رمز عبور کاربران |
| **GUID File Links** | لینک‌های دانلود غیرقابل پیش‌بینی و امن |
| **Public/Private Files** | تفکیک فایل‌های عمومی و خصوصی |

#### ابزارهای توسعه

| ابزار | کاربرد |
|-------|--------|
| **Visual Studio 2026** | IDE اصلی توسعه |
| **Git** | کنترل نسخه |
| **NuGet** | مدیریت پکیج‌های دات‌نت |
| **EF Core Migrations** | مدیریت خودکار ساختار دیتابیس |

<br/>

### English 🇬🇧

#### Core Technologies

| Technology | Usage |
|------------|-------|
| **ASP.NET Core 10 MVC** | Main backend framework |
| **Entity Framework Core 8** | ORM and database communication |
| **SQL Server 2026** | Primary database |
| **C# 12** | Backend programming language |
| **Clean Architecture** | 5-layer clean architecture |
| **AutoMapper** | Automatic mapping between models and ViewModels |
| **Repository Pattern** | Data access abstraction layer |
| **Service Layer** | Business logic separation |

#### Frontend Technologies

| Technology | Usage |
|------------|-------|
| **Tailwind CSS 3** | Modern CSS framework for UI design |
| **jQuery** | JavaScript library for client-side interactions |
| **Font Awesome 6** | Professional icon library |
| **Vazirmatn Font** | Standard and beautiful Persian font |
| **Vanilla JavaScript** | Custom scripts like upload progress bar |

#### Security

| Tool | Usage |
|------|-------|
| **Cookie Authentication** | Cookie-based authentication with sliding expiration |
| **PBKDF2 Hashing** | Secure password hashing |
| **GUID File Links** | Unpredictable and secure download links |
| **Public/Private Files** | Separation of public and private files |

#### Development Tools

| Tool | Usage |
|------|-------|
| **Visual Studio 2026** | Primary development IDE |
| **Git** | Version control |
| **NuGet** | .NET package management |
| **EF Core Migrations** | Automated database schema management |

---

## 📁 ساختار پروژه | Project Structure

```
MutaPeimayesh/                           # Solution Root
│
├── MutaPeimayesh.Web/                   # Presentation Layer (MVC)
│   ├── Controllers/                     # MVC Controllers
│   ├── Views/                           # Razor Views
│   ├── Models/                          # ViewModels مخصوص Web
│   ├── Services/                        # سرویس‌های وب
│   ├── Uploads/                         # فایل‌های آپلود شده
│   └── wwwroot/                         # فایل‌های استاتیک
│
├── MutaPeimayesh.Application/           # Application Layer
│   ├── Common/                          # ابزارهای عمومی
│   ├── Mappings/                        # پیکربندی AutoMapper
│   ├── Services/                        # سرویس‌های اپلیکیشن
│   └── ViewModels/                      # ViewModels
│
├── MutaPeimayesh.Domain/                # Domain Layer
│   ├── Models/                          # موجودیت‌های اصلی
│   └── Repositories/                    # اینترفیس‌های Repository
│
├── MutaPeimayesh.Infrastructure/        # Infrastructure Layer
│   ├── Context/                         # DbContext
│   ├── Migrations/                      # Migration‌های EF Core
│   ├── Options/                         # تنظیمات
│   ├── Repositories/                    # پیاده‌سازی Repository
│   └── Services/                        # سرویس‌های زیرساخت
│
└── MutaPeimayesh.Infra.IoC/             # Dependency Injection
    └── DependencyContainer.cs           # تنظیمات DI
```

---

## 🏛️ معماری | Architecture

### فارسی 🇮🇷

این پروژه از **معماری تمیز (Clean Architecture)** در ۵ لایه مجزا پیروی می‌کند که هر لایه مسئولیت مشخصی دارد:

```
┌─────────────────────────────────────┐
│      MutaPeimayesh.Web              │  🖥️ لایه نمایش (Presentation)
│  (Controllers, Views, wwwroot)      │
├─────────────────────────────────────┤
│      MutaPeimayesh.Application      │  📋 لایه اپلیکیشن (Application)
│  (Services, ViewModels, Mappings)   │
├─────────────────────────────────────┤
│      MutaPeimayesh.Domain           │  🎯 لایه دامنه (Domain)
│  (Entities, Repository Interfaces)  │
├─────────────────────────────────────┤
│      MutaPeimayesh.Infrastructure   │  💾 لایه زیرساخت (Infrastructure)
│  (DbContext, Migrations, Repos)     │
├─────────────────────────────────────┤
│      MutaPeimayesh.Infra.IoC        │  🔗 لایه تزریق وابستگی (IoC)
│  (Dependency Container)             │
└─────────────────────────────────────┘
```

**اصول معماری:**
- **جداسازی دغدغه‌ها (Separation of Concerns):** هر لایه وظیفه مشخصی دارد
- **تزریق وابستگی (Dependency Injection):** وابستگی‌ها از طریق DI Container تزریق می‌شوند
- **وارونگی وابستگی (Dependency Inversion):** لایه‌های بالایی به انتزاع‌ها وابسته هستند نه پیاده‌سازی‌ها
- **قابلیت تست‌پذیری:** جداسازی لایه‌ها امکان تست واحد را فراهم می‌کند
- **قابلیت نگهداری:** تغییر در یک لایه بر لایه‌های دیگر تأثیر نمی‌گذارد

<br/>

### English 🇬🇧

This project follows **Clean Architecture** with 5 distinct layers, each with a specific responsibility:

```
┌─────────────────────────────────────┐
│      MutaPeimayesh.Web              │  🖥️ Presentation Layer
│  (Controllers, Views, wwwroot)      │
├─────────────────────────────────────┤
│      MutaPeimayesh.Application      │  📋 Application Layer
│  (Services, ViewModels, Mappings)   │
├─────────────────────────────────────┤
│      MutaPeimayesh.Domain           │  🎯 Domain Layer
│  (Entities, Repository Interfaces)  │
├─────────────────────────────────────┤
│      MutaPeimayesh.Infrastructure   │  💾 Infrastructure Layer
│  (DbContext, Migrations, Repos)     │
├─────────────────────────────────────┤
│      MutaPeimayesh.Infra.IoC        │  🔗 IoC / DI Layer
│  (Dependency Container)             │
└─────────────────────────────────────┘
```

**Architecture Principles:**
- **Separation of Concerns:** Each layer has a defined responsibility
- **Dependency Injection:** Dependencies are injected via DI Container
- **Dependency Inversion:** Higher layers depend on abstractions, not implementations
- **Testability:** Layer separation enables unit testing
- **Maintainability:** Changes in one layer don't affect others

---

## 📄 مجوز | License

### فارسی 🇮🇷
این پروژه تحت مجوز MIT منتشر شده است.

### English 🇬🇧
This project is licensed under the MIT License.

---

<div align="center">
  
**Made by ![Ali G.Baei](https://github.com/Ali-GBaei/)**

</div>
