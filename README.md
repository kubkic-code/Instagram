# 🥊 Martin Sedlák – 50 let v kleci | Instagram Template Gift Web

[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)](https://github.com/kubkic-code/Instagram_template_gift_web)
[![Event](https://img.shields.io/badge/Oktagon-50%20Narozeniny-gold?style=for-the-badge&logo=target)](https://github.com/kubkic-code/Instagram_template_gift_web)
[![BJP](https://img.shields.io/badge/Vibe-BJP%20%23Oktagon100-red?style=for-the-badge)](https://github.com/kubkic-code/Instagram_template_gift_web)

> **Interaktivní zážitkový web stylizovaný do věrného Instagram příspěvku vytvořený jako originální narozeninový dar k 50. narozeninám pro tátu – Martina „The Terminator“ Sedláka.**  
> Soupeř (*Krize 50*) nemá ani tu nejmenší šanci. 💪🔥 #BJP #Oktagon100

---

## 📖 O projektu

Tento projekt je interaktivní mobilní webová aplikace stylizovaná jako reálný **Instagram Dark Mode příspěvek**. Slouží jako vtipný a emotivní rodinný dárek, který mapuje přípravu táty na jeho jubilejní „titulový zápas“ s životním milníkem 50 let.

Projekt vrcholí na posledním slidu exkluzivním **zlatým certifikátem / VIP pozvánkou do O2 arény na turnaj Oktagon MMA**, garantovanou syny Jakubem & Petrem Sedlákovými.

---

## ✨ Hlavní funkce

- 📱 **Autentický Instagram Dark Mode UI:**
  - Horní navigační lišta s logem Instagramu
  - Profilová hlavička s modrou ověřenou fajfkou (`martin_sedlak_bjp_terminator` ✔️)
  - Lokace: *📍 Extrémní tréninkový kemp BJP*
  - Počítadlo lajků: *50 000+ srdíček* od Jiřího Procházky a rodiny

- 🎞️ **Interaktivní Swiper Kolotoč (18 slidů):**
  - Podpora dotykových gest (swipe, touch) na mobilech i myši/klávesnice na desktopu
  - Dynamické počítadlo slidů (`1 / 18`) a spodní tečková navigace
  - **4 optimalizovaná videa** s vlastním přehrávačem na jedno klepnutí (včetně zkonvertovaného H.264/AAC materiálu z archivních nahrávek a AI tréninkových záběrů)
  - **13 fotek** z náročných tréninků, sparingů, dělání váhy i rodinných momentek

- 🎫 **Slide 18 – Narozeninový Oktagon Voucher:**
  - Prémiový zlatý certifikát k 50. narozeninám
  - Zlatý oktagon s číslem 50, VIP lístky do O2 arény
  - Vyražené číslo pozvánky `BJK–0050–TATIK`

- ❤️ **Interaktivní mikrointerakce:**
  - **Double-tap / dvojklik:** animace velkého červeného srdce uprostřed fotky + aktivace lajku
  - **Lajkovací tlačítko:** animace tlukotu srdce (heartbeat) a přepnutí barvy
  - **Komentářové tlačítko:** plynulý scroll dolů přímo do diskuse
  - **Sdílení:** integrace nativního mobilního **Web Share API** s automatickým fallbackem na zkopírování odkazu do schránky
  - **Ukládání do záložek:** toggle bookmark

- 💬 **Hype komentářová sekce:**
  - Věrná replika diskuse pod příspěvkem
  - Komentáře od MMA šampióna Jiřího Procházky (`jiri_bjp_prochazka`), synů (`jakub_sedlak`, `petr_sedlak`), médií (`MMA_shorties`) a fanouškovských stránek
  - Možnost lajkovat jednotlivé komentáře

- 🌐 **Perfektní mobilní sdílení:**
  - Kompletní **Open Graph & Twitter meta tagy** pro atraktivní náhled při odeslání odkazu přes WhatsApp, Messenger nebo SMS

---

## 📂 Struktura repozitáře

```text
├── index.html           # Kompletní webová aplikace (HTML, CSS a JS v jednom souboru)
├── media/               # Optimalizovaná multimediální média
│   ├── *.jpg / *.png    # Fotografie z tréninků, sparingů a oslav
│   ├── *.mp4 / *.MOV    # Tréninková videa ve webových formátech
│   └── og_preview.jpg   # Náhledový obrázek pro sociální sítě
└── README.md            # Dokumentace projektu
```

---

## 🚀 Jak spustit web

Web nevyžaduje žádné složité instalace ani build procesy. Je postaven na čistém Vanilla HTML/CSS/JavaScriptu.

### 1. Lokální spuštění
Jednoduše otevřete soubor `index.html` v libovolném moderním webovém prohlížeči (doporučeno otevřít v mobilním zobrazení nebo přímo v telefonu):

```bash
# Příklad spuštění jednoduchého lokálního serveru (volitelné)
npx serve .
# nebo
python -m http.server 8000
```

### 2. Nasazení přes GitHub Pages (doporučeno pro poslání odkazu)
1. Přejděte do nastavení repozitáře na GitHubu (**Settings** → **Pages**).
2. Pod sekcí **Build and deployment** zvolte:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` / `root`
3. Klikněte na **Save**. Během minutky bude web živě dostupný na URL:  
   `https://kubkic-code.github.io/Instagram_template_gift_web/`

---

## 🛠️ Použité technologie

- **HTML5 & CSS3:** Moderní Dark Mode design systém podle reálné aplikace Instagram, CSS Grid, Flexbox, Glassmorphism efekty.
- **JavaScript (ES6+):** Logika přehrávače videí, Web Share API, clipboard API, obsluha double-tap gest.
- **[Swiper.js 11](https://swiperjs.com/):** Touch-friendly carousel pro plynulé swipování na dotykových obrazovkách.
- **FFmpeg:** Konverze archivních video formátů do kompatibilního H.264/AAC MP4.

---

## 👑 Dedikace

Věnováno tátovi k jeho 50. narozeninám.  
Garantováno a vytvořeno syny **Jakubem & Petrem Sedlákovými**.  
**#BJP · #Oktagon100 · #LviZerouPrvni · #50LetVKleci**
