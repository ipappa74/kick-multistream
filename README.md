# Kick Multistream

<p align="center">
  <img src="https://img.shields.io/github/stars/ipappa74/kick-multistream?style=flat&color=5aff2f&label=Stars" />
  <img src="https://img.shields.io/github/issues/ipappa74/kick-multistream?color=5aff2f&label=Issues" />
  <img src="https://img.shields.io/github/last-commit/ipappa74/kick-multistream?color=5aff2f&label=Last%20Commit" />
  <img src="https://img.shields.io/badge/License-MIT-5aff2f" />
  <img src="https://img.shields.io/badge/Kick%20Theme-Neon-5aff2f" />
</p>

## 🎯 Yleiskuvaus

**Kick Multistream** on kevyt, nopea ja täysin selainpohjainen monistriimityökalu Kick.com‑alustalle.  
Sen avulla voit katsoa useita striimejä samanaikaisesti, avata chatin, järjestellä slotteja, tallentaa suosikkeja ja seurata LIVE‑tilaa reaaliajassa.

Projekti toimii **ilman backendia** – pelkkä HTML + CSS + JavaScript.

---

## 🚀 Ominaisuudet

### 🎥 Monistriimaus
- 1–9 striimiä yhtä aikaa  
- Automaattinen grid‑asettelu  
- Zoomaa yksittäinen striimi koko näkymään  
- Drag & drop ‑järjestely

### 💬 Kick‑chat‑integraatio
- Chat avautuu striimin oikealle puolelle  
- Tila säilyy sivun uudelleenlatauksissa  
- Ei peitä videota eikä katoa taakse

### 🔇 Mute / Unmute – tila säilyy
- Jokaisella slotilla oma mute‑tila  
- Tallentuu localStorageen  
- Uusi striimi aloittaa aina mutella (oletus)

### ⭐ Suosikit
- Lisää kanavia suosikkeihin  
- LIVE‑kanavat nousevat listan kärkeen  
- Automaattinen LIVE‑lataus  
- Kick‑henkiset neon‑radiobuttonit

### 🟢 LIVE‑status + katsojamäärät
- LIVE / OFFLINE ‑badge  
- Neon‑pulsseilla animoitu LIVE‑tila  
- Katsojamäärä näkyy reaaliajassa  
- Päivittyy automaattisesti 20–60 sek välein

### ➕ Placeholder
- Neon‑vihreä plus‑ikoni
- Avaa “Lisää striimi” ‑dialogin

---

## 🧩 Tekninen rakenne

### Käytetyt teknologiat
- **HTML5**
- **CSS3** (Kick‑henkinen neon‑UI)
- **JavaScript (vanilla)**
- **Kick API** (LIVE‑status + katsojamäärät)
- **Kick Player Embed**

### Tallennus (localStorage)
- `kick-state` → kanavat, mute‑tilat, chat‑tilat, layout  
- `kick-favs` → suosikkikanavat  
- `kick-auto-load-channels` → automaattinen LIVE‑lataus  

---

## 🛠 Käyttö

### 1. Lisää striimi
- Klikkaa slotin plus‑merkkiä  
- Syötä kanavan nimi  
- Striimi latautuu

### 2. Avaa chat
- Paina **Chat**  
- Paneeli avautuu oikealle  

### 3. Mute / Unmute
- Paina **Mute / Unmute**  
- Tila tallentuu ja säilyy reloadissa

### 4. Suosikit
- Lisää suosikki → **+ Lisää**  
- Klikkaa suosikkia → latautuu slottiin  
- Oikea klikkaus → poistaa suosikin  

### 5. Drag & Drop
- Vedä slottia → järjestä uudelleen  
- Kaikki tilat siirtyvät mukana
