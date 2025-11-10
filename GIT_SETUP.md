# Git Setup Instructions

## 1. ایجاد Remote Repository در GitHub
1. به GitHub.com بروید
2. "New repository" کلیک کنید
3. نام repository را وارد کنید (مثلاً: shopping-website)
4. "Create repository" کلیک کنید

## 2. اتصال Local Repository به GitHub
```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/shopping-website.git
git push -u origin main
```

## 3. نحوه کار با پروژه

### Frontend Development (VS Code):
```bash
# باز کردن فقط پوشه frontend در VS Code
code frontend

# اجرای development server
cd frontend
npm run dev

# Commit کردن تغییرات frontend
git add frontend/
git commit -m "frontend: توضیح تغییرات"
git push origin main
```

### Backend Development (Visual Studio):
```bash
# باز کردن solution file در Visual Studio
# File -> Open -> Project/Solution -> backend/OnlinShop.sln

# Commit کردن تغییرات backend
git add backend/
git commit -m "backend: توضیح تغییرات"
git push origin main
```

### VS Code Git Integration:
- VS Code خودکار تغییرات frontend را نشان می‌دهد
- از Source Control panel استفاده کنید
- فقط فایل‌های frontend را stage کنید

### Visual Studio Git Integration:
- Visual Studio خودکار تغییرات backend را نشان می‌دهد
- از Git Changes panel استفاده کنید
- فقط فایل‌های backend را stage کنید

## 4. Best Practices
- همیشه قبل از شروع کار: `git pull origin main`
- تغییرات کوچک و منطقی commit کنید
- پیام‌های commit واضح و توصیفی بنویسید
- قبل از push، مطمئن شوید که کد compile می‌شود