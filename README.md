# 💝 Strona Walentynkowa dla Magico 💝

Interaktywna strona z pytaniem walentynkowym, gdzie przycisk "Nie" ucieka, a "Tak" pokazuje jamnika i serca!

## 🚀 Deployment na Railway

### Krok 1: Zainstaluj Railway CLI (opcjonalnie)
```bash
npm install -g @railway/cli
```

### Krok 2: Deploy przez GitHub (zalecane)

1. Stwórz nowe repozytorium na GitHub
2. Push kod:
```bash
git init
git add .
git commit -m "Initial commit - Strona walentynkowa"
git branch -M main
git remote add origin <twoj-repo-url>
git push -u origin main
```

3. Wejdź na [railway.app](https://railway.app)
4. Kliknij "New Project" → "Deploy from GitHub repo"
5. Wybierz swoje repozytorium
6. Railway automatycznie wykryje Node.js i wdroży aplikację
7. Po deploymencie dostaniesz link do strony!

### Krok 3: Deploy przez Railway CLI

Alternatywnie, z tego folderu:
```bash
railway login
railway init
railway up
```

## 🧪 Testowanie lokalnie

```bash
npm install
npm start
```

Otwórz http://localhost:3000

## 🎨 Funkcje

- ✨ Przycisk "Nie" ucieka przed kursorem
- 💕 Po kliknięciu "Tak" pojawia się jamnik 🐶
- 💖 Spadające serduszka
- 📱 Responsive design
- 🎉 Animacje i efekty

## 💡 Customizacja

Możesz edytować `public/index.html`:
- Zmień kolory w sekcji `background: linear-gradient(...)`
- Zmień tekst w `<h1>` i `.message`
- Dodaj więcej emoji w funkcji `createHearts()`
