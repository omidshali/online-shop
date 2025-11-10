# Git Setup Instructions

## 1. Create Remote Repository in GitHub

1. Go to GitHub.com
2. Click "New repository"
3. Enter repository name (e.g., shopping-website)
4. Click "Create repository"

## 2. Connect Local Repository to GitHub

```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/shopping-website.git
git push -u origin main
```

## 3. How to Work with the Project

### Frontend Development (VS Code):

```bash
# Open only frontend folder in VS Code
code frontend

# Run development server
cd frontend
npm run dev

# Commit frontend changes
git add frontend/
git commit -m "frontend: description of changes"
git push origin main
```

### Backend Development (Visual Studio):

```bash
# Open solution file in Visual Studio
# File -> Open -> Project/Solution -> backend/OnlinShop.sln

# Commit backend changes
git add backend/
git commit -m "backend: description of changes"
git push origin main
```

### VS Code Git Integration:

- VS Code automatically shows frontend changes
- Use Source Control panel
- Stage only frontend files

### Visual Studio Git Integration:

- Visual Studio automatically shows backend changes
- Use Git Changes panel
- Stage only backend files

## 4. Best Practices

- Always before starting work: `git pull origin main`
- Commit small and logical changes
- Write clear and descriptive commit messages
- Before push, make sure code compiles
