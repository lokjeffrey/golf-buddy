# ⛳ Golf Buddy

Data-gedreven golf trainingsapp voor de driving range, putting green en chip-oefeningen.

## Functies

- **62 oefeningen** verdeeld over 6 categorieën (Drive, Approach, Chip, Putt Kort/Medium/Lang)
- **Zwakteanalyse** op basis van Garmin-statistieken of handmatige invoer
- **4 trainingssessies** gegenereerd op maat per sessieduur
- **Progressietracking** met grafiek over maximaal 10 metingen

---

## 🚀 Publiceren via GitHub Pages (gratis URL)

Volg deze stappen om de app bereikbaar te maken op je telefoon via een vaste URL.

### Stap 1 – GitHub account

Ga naar [github.com](https://github.com) en maak een gratis account als je er nog geen hebt.

### Stap 2 – Nieuwe repository aanmaken

1. Klik rechtsboven op **+** → **New repository**
2. Naam: `golf-buddy`
3. Zet op **Public**
4. Klik **Create repository**

### Stap 3 – Code uploaden

Optie A – Via de browser (makkelijkst):
1. Open je nieuwe repository op GitHub
2. Klik **Add file** → **Upload files**
3. Sleep `index.html` en `manifest.json` naar het venster
4. Klik **Commit changes**

Optie B – Via Git (aanbevolen voor updates):
```bash
cd C:\Users\lokje\Documents\antigravity\Golf-Buddy
git remote add origin https://github.com/JOUW-GEBRUIKERSNAAM/golf-buddy.git
git branch -M main
git push -u origin main
```

### Stap 4 – GitHub Pages inschakelen

1. Ga in je repository naar **Settings** (rechtsboven)
2. Klik in de linkerkolom op **Pages**
3. Onder **Source**: kies `Deploy from a branch`
4. Branch: `main` / Folder: `/ (root)`
5. Klik **Save**

### Stap 5 – Jouw URL

Na ±1 minuut is de app beschikbaar op:
```
https://JOUW-GEBRUIKERSNAAM.github.io/golf-buddy
```

Sla deze URL op als bladwijzer op je telefoon, of kies **"Voeg toe aan beginscherm"** in je browser voor een app-icoon.

---

## Updates publiceren

Nadat je wijzigingen hebt aangebracht in `index.html`:

**Via browser:** Upload het bestand opnieuw via **Add file → Upload files** op GitHub.

**Via Git:**
```bash
git add .
git commit -m "Update oefeningen"
git push
```

GitHub Pages verwerkt de update automatisch binnen ~1 minuut.

---

## Categorieën & Benchmarks

| Categorie | Statistiek | Benchmark |
|-----------|-----------|-----------|
| 🏌️ Drive | Fairways Hit % | ≥ 50% |
| 🎯 Approach | GIR % | ≥ 35% |
| 🏌 Chip/Pitch | Up-and-Down % | ≥ 35% |
| 🎱 Putting | Gem. putts/hole | ≤ 1.9 |
| 🎱 Putt Kort | 3-putt % (<3m) | ≤ 15% |
| 🎱 Putt Medium | 3-putt % (3-6m) | ≤ 25% |
| 🎱 Putt Lang | 3-putt % (>6m) | ≤ 40% |
