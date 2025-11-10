# Shopping Website

یک وب‌سایت فروشگاه آنلاین با معماری جداگانه frontend و backend.

## ساختار پروژه

```
shopping-website/
├── frontend/          # Next.js TypeScript application
├── backend/           # ASP.NET Core Web API (Onion Architecture)
├── .gitignore         # Git ignore rules for root
└── README.md          # Documentation
```

## Development Workflow

### Frontend Development (VS Code)
1. VS Code را باز کنید
2. پوشه `frontend` را باز کنید
3. در terminal از دستورات زیر استفاده کنید:
```bash
cd frontend
npm run dev
```

### Backend Development (Visual Studio)
1. Visual Studio را باز کنید
2. فایل `.sln` در پوشه `backend` را باز کنید
3. پروژه را build و run کنید

### Git Commands

#### Frontend Changes (از VS Code):
```bash
# در VS Code terminal
git add frontend/
git commit -m "frontend: توضیح تغییرات"
git push origin main
```

#### Backend Changes (از Visual Studio):
```bash
# در Visual Studio Package Manager Console یا Command Prompt
git add backend/
git commit -m "backend: توضیح تغییرات"
git push origin main
```

#### همه تغییرات (از هر ویرایشگر):
```bash
git add .
git commit -m "update: توضیح کلی تغییرات"
git push origin main
```

## محیط توسعه

- **Frontend**: VS Code + Next.js + TypeScript
- **Backend**: Visual Studio + ASP.NET Core + Onion Architecture
- **Version Control**: Git + GitHub

## پورت‌های پیش‌فرض

- Frontend: http://localhost:3000
- Backend: https://localhost:7000 (یا پورت تعین شده در launchSettings.json)