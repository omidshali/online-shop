# Shopping Website

An online shopping website with separate frontend and backend architecture.

## Project Structure

```
shopping-website/
├── frontend/          # Next.js TypeScript application
├── backend/           # ASP.NET Core Web API (Onion Architecture)
├── .gitignore         # Git ignore rules for root
└── README.md          # Documentation
```

## Development Workflow

### Frontend Development (VS Code)

1. Open VS Code
2. Open the `frontend` folder
3. Use the following commands in terminal:

```bash
cd frontend
npm run dev
```

### Backend Development (Visual Studio)

1. Open Visual Studio
2. Open the `.sln` file in `backend` folder
3. Build and run the project

### Git Commands

#### Frontend Changes (from VS Code):

```bash
# In VS Code terminal
git add frontend/
git commit -m "frontend: description of changes"
git push origin main
```

#### Backend Changes (from Visual Studio):

```bash
# In Visual Studio Package Manager Console or Command Prompt
git add backend/
git commit -m "backend: description of changes"
git push origin main
```

#### All Changes (from any editor):

```bash
git add .
git commit -m "update: general description of changes"
git push origin main
```

## Development Environment

- **Frontend**: VS Code + Next.js + TypeScript
- **Backend**: Visual Studio + ASP.NET Core + Onion Architecture
- **Version Control**: Git + GitHub

## Default Ports

- Frontend: http://localhost:3000
- Backend: https://localhost:7000 (or port specified in launchSettings.json)
