# Ghid Publicare pe GitBook.com

<h2 align="center"><mark style="color:blue;"><strong>CUM ÎȚI PUI WIKI-UL ONLINE PE GITBOOK (EXACT CA OPTIC GAMING)</strong></mark></h2>

***

Site-ul **https://wiki.opticgaming.ro/** pe care l-ai văzut este găzduit și administrat pe platforma **GitBook** (exact structura pe care am creat-o aici pentru tine). 

Mai jos găsești toți pașii pentru a urca aceste fișiere pe GitBook gratuit, cu domeniu personalizat (ex: `wiki.newliferp.ro` sau `newlife.gitbook.io`), căutare automată, temă Dark Mode și design modern.

---

## 🚀 Metoda Recomandată: Sincronizare cu GitHub (100% Gratuit)

Aceasta este metoda folosită de marile comunități: fișierele stau pe GitHub, iar GitBook le preia automat și le transformă în site-ul wiki în timp real.

### Pasul 1: Creează un cont pe GitHub & GitBook
1. Intră pe [GitHub.com](https://github.com/) și creează un cont gratuit (dacă nu ai deja).
2. Intră pe [GitBook.com](https://www.gitbook.com/) și alege **Sign up with GitHub**.

---

### Pasul 2: Creează un Repository pe GitHub
1. Pe GitHub, apasă pe butonul verde **New Repository** (sau mergi la [github.com/new](https://github.com/new)).
2. Pune-i un nume, de exemplu: `newlife-wiki`.
3. Selectează **Public** (sau Private dacă ai plan compatibil).
4. Apasă **Create repository**.

---

### Pasul 3: Urcă fișierele din folderul `newlife-wiki`
Ai două moduri foarte simple de a urca fișierele generate:

#### Varianta A: Drag & Drop direct în browser (Fără comenzi)
1. În pagina noului repository de pe GitHub, apasă pe **"uploading an existing file"**.
2. Trage fișierele și folderele create din:
   `C:\Users\Cosmin\.gemini\antigravity\scratch\newlife-wiki`
   *(Asigură-te că urci `README.md`, `SUMMARY.md`, `.gitbook.yaml` și toate folderele `regulamente`, `ghid-server`, `tutoriale`, `tarife-and-servicii`).*
3. Apasă pe butonul verde **Commit changes**.

#### Varianta B: Prin Git (Consolă)
Dacă ai Git instalat pe PC:
```bash
cd "C:\Users\Cosmin\.gemini\antigravity\scratch\newlife-wiki"
git init
git add .
git commit -m "Initial NewLife Wiki commit"
git branch -M main
git remote add origin https://github.com/USERUL-TAU/newlife-wiki.git
git push -u origin main
```

---

### Pasul 4: Conectează GitHub la GitBook
1. Deschide [GitBook.com](https://app.gitbook.com/).
2. Apasă pe **New Space** și pune-i numele **NewLife Wiki**.
3. În meniul din stânga al spațiului nou creat, mergi la **Integrations** sau apasă pe **Sync with GitHub**.
4. Autorizează GitBook și selectează repository-ul tău: `newlife-wiki`.
5. Bifează branch-ul: `main`.
6. Apasă **Sync**!
7. 🎉 În câteva secunde, GitBook va citi `SUMMARY.md` și va genera automat tot meniul lateral, toate paginile, căutarea instantă și stilul grafic!

---

## 🎨 Personalizare Design & Aspect (Look-ul Optic Gaming)

În setările GitBook (**Space Settings -> Customization / Branding**):
1. **Logo & Favicon:**
   * Încarcă logo-ul serverului tău NewLife (PNG cu fundal transparent).
   * Încarcă o pictogramă mică de 32x32px pentru tab-ul din browser.
2. **Tema de culori (Primary Accent):**
   * Alege nuanța comunității tale (de exemplu un albastru electric `#2563EB` sau un cyan/neon specific NewLife).
3. **Modul Întunecat (Dark Mode):**
   * Setează modul implicit pe **Dark** (așa cum folosește și Optic Gaming pentru un aspect de gaming curat).
4. **Header Links:**
   * Poți adăuga butoane în antet către:
     * **Discord**: `https://discord.gg/newliferp`
     * **Conectare FiveM**: `fivem://connect/fivem.newlife-rp.ro`
     * **Magazin / Donații**: link-ul tău Tebex/Store.

---

## 🌐 Cum legi propriul tău domeniu (ex: `wiki.newliferp.ro`)

Dacă deții un domeniu web (de exemplu `newliferp.ro` cumpărat de pe Namecheap, ClausWeb, Rotld etc.):
1. În GitBook, mergi la **Settings** -> **Publishing** -> **Custom Domain**.
2. Scrie subdomeniul dorit: `wiki.newliferp.ro`.
3. GitBook îți va arăta o înregistrare DNS de tip:
   * **Type:** `CNAME`
   * **Name / Host:** `wiki`
   * **Value / Target:** `hosting.gitbook.io` (sau adresa afișată pe ecran).
4. Deschide panoul de administrare DNS al domeniului tău (Cloudflare, cPanel etc.) și adaugă înregistrarea CNAME.
5. În 10-30 de minute, certificatul SSL (HTTPS) este generat automat și gratuit de GitBook, iar site-ul tău va fi accesibil direct la `https://wiki.newliferp.ro/`!

---

## ✏️ Cum modifici sau adaugi reguli noi în viitor?

* **Din GitBook Web Editor**: Poți edita orice pagină direct cu mouse-ul în browser pe GitBook (are editor vizual de tip Notion). Modificările se vor salva automat și în repository-ul de pe GitHub!
* **Sau din fișiere locale**: Modifici fișierele `.md` de pe calculatorul tău, dai `git push` și GitBook se actualizează instantaneu.
