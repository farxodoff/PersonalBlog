# 📝 PersonalBlog

**PersonalBlog** — bu **C# va .NET** platformasida ishlab chiqilgan shaxsiy blog loyihasi bo‘lib, unda foydalanuvchilar maqolalar yozishi, tahrirlashi va o‘qishi mumkin. Loyiha **backend** bilimlarni mustahkamlash va real loyihada .NET texnologiyalarini qo‘llash maqsadida yaratilgan.

---

## 🚀 Texnologiyalar

Loyihada quyidagi texnologiyalar ishlatilgan:

* **C#**
* **.NET (ASP.NET Core)**
* **Entity Framework Core**
* **MS SQL Server / PostgreSQL**
* **LINQ**
* **RESTful API**
* **Dependency Injection**
* **MVC / Web API arxitekturasi**

---

## 📂 Loyihaning asosiy imkoniyatlari

* 📰 Blog postlarni yaratish, tahrirlash va o‘chirish (CRUD)
* 👤 Foydalanuvchi bilan ishlash (Author)
* 🗂️ Kategoriyalar orqali postlarni guruhlash
* 🔍 Postlarni qidirish
* 📅 Postlar uchun sana va muallif ma’lumotlari
* 🛡️ Clean Code va qatlamli arxitektura (Layered Architecture)

---

## 🏗️ Arxitektura

Loyiha quyidagi qatlamlar asosida qurilgan:

```
PersonalBlog
│
├── PersonalBlog.API        → Controllerlar (API)
├── PersonalBlog.Core       → Entity va Interface’lar
├── PersonalBlog.Infrastructure → EF Core, DbContext, Repository
└── PersonalBlog.Application → Business logic (Services)
```

---

## 🗄️ Ma’lumotlar bazasi

* **Code First** yondashuvi ishlatilgan
* Migratsiyalar orqali database boshqariladi
* Entity Framework Core asosida ishlaydi

---

## ▶️ Ishga tushirish (Run qilish)

1. Repository’ni klon qiling:

```bash
git clone https://github.com/username/PersonalBlog.git
```

2. Loyihani oching:

```bash
cd PersonalBlog
```

3. Database migratsiyasini bajaring:

```bash
dotnet ef database update
```

4. Loyihani ishga tushiring:

```bash
dotnet run
