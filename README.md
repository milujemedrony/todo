# MilujemeDrony – Prehľad TODO projektu

Tento repozitár slúži ako prehľad stavu a plánovaných úloh pre všetky repozitáre v projekte **milujemedrony**.

⚠️ **Kvôli skúškovému teraz nestíham programovať naplno, no projekt stále pravidelne "skúmam"** A nezostáva nám veľa :)

> **Poznámka**  
> Projekt vyvíjam sám popri štúdiu. Ide o side-project bez pevného harmonogramu.  
> Motivácia: vytvoriť alternatívu, pretože existujúce riešenia (napr. Mamdron) mi nevyhovujú.

---

## Stav repozitárov

### 1. `main-web` — **WIP** (nezverejnené)
Hlavná verejná webová stránka.

**Stav**
- Landing page (hero, základná štruktúra) — ✅ Hotové
- Blog — ✅ Hotové
- Editor Blogov — ✅ Hotové
- Admin webpage — ✅ Hotové

**TODO**
- Kontaktná stránka

**Do budúcna**
- Statická mapa zón aj pre Webové rozhranie (asi nie teraz)

---

### 2. `geozones-manager` — **WIP** https://geozones.milujemedrony.sk/
Webová aplikácia na správu geozón pre drony.

**Stav**
- Autentifikácia — ✅ Hotové  
- Úprava geozón — ✅ Hotové  
- Nahrávanie geozón — ✅ Hotové  
- API na sťahovanie geozón — ✅ Hotové  
- Live preview — ✅ Hotové  
- Úprava metadát — ✅ Hotové

**TODO**:
- Odstrániť ts-ignore
- Pridať map tiles generaciu
---

### 3. `mobile` — **WIP** (nezverejnené)
Mobilná aplikácia.

**Stav**
- Autentifikácia — ✅ Hotové  
- Zobrazovanie geozón — ✅ Hotové  
- Zobrazovanie mapy — ✅ Hotové (možný Prechod na iný mapový systém)
- Zobrazovanie aktuálneho počasia — ✅ Hotové
- Nastavenie letovej zóny — ✅ Hotové
- Pridanie vlastnej zóny — ✅ Hotové
- Zobrazenie informácii o geozóne — ✅ Hotové
- Podrobné informácie o geozóne (kontakt číslo, prevádzkové hodiny etc...) — ✅ Hotové
- Nastavenie informácíi o vašom drone — ✅ Hotové

**TODO**
- Android support — ✅/🍊 WIP - Aplikácia, má hotový základ pripravený na spustenie pre Android. Avšak nie všetky funkcie aplikácie sú, ešte dokončené, tým pádom niesu na Androide, najskôr sa robí iOS :)
- Sťahovanie geozón
- Zobrazenie flight history vaších zón - 🍊 - Finálne úpravy
- Opraviť dark/light mode
- Implementovať Remote ID "finder?"
- Zdroje aplikácie (weather data... zone data...)
- Google/Apple login
- Registrácia do Aplikácia (NEPOVINNÁ!) - Fixnut inputy na ostatne veci ako (meno atd..) - 🍊 - Finálne úpravy
- Forgot password - 🍊 - Finálne úpravy

---

### 4. `api.milujemedrony.sk` — **WIP** http://api-dev.milujemedrony.sk/
Backend API pre celý ekosystém.

**Stav**
- Autentifikácia používateľov — ✅ Hotové  
- Prijímanie dát z letových zón — ✅ Hotové
- Odosielanie dát letových zón — ✅ Hotové
- Registrácia používateľov — ✅ Hotové
- Zabudnuté heslo — ✅ Hotové  

**TODO**
- ked sa flightzone dokonci/cancelne tak sa ulozi let do flighthistory a vymaze z flightzones db (vypocitaj actual time)
- Also aby sa ukladal drone ID nie drone name, a nepojde zmazat drone ked je aktivna flight zone

**Plánované / nápady do budúcna**
- Verejné profily
- Nahrávanie fotiek
- Ďalšie verejné endpointy


---

### 5. `api-verify` — **Dokončené** https://api-verify.milujemedrony.sk/
Webová UI stránka, pre registráciu/obnovu hesla.

Nechcel som to dávať do main-webu, keďže tam sú už blogy :)

**TODO**
- Všetko potrebné

---

### 6. `comming-soon-page` — **Dokončené** https://milujemedrony.sk/
Dočasná „coming soon“ stránka.

---

## Všeobecné informácie
- Jeden vývojár
- Vedľajší projekt popri štúdiu
- Bez pevného roadmapu a termínov
- Funkcionalita a rozsah sa môžu meniť

---

_Aktualizované manuálne_
