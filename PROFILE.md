# Profil uzla — Jawra

**ID uzla:** NODE-001 · **Verzia profilu:** 0.1 · **standard:** v0.1 (štandard profilu uzla siete Forge)
**Dátum poslednej aktualizácie:** 2026-09-01

> Jawra je samostatná podnikateľská entita, ktorá na sieti Forge ponúka kapacitu 3D tlače
> a vlastné modely. Podniká vo vlastnom mene a na vlastnú zodpovednosť; Forge je bezplatná
> platforma bez podielu na tržbách uzla.

---

## 3.1 Identifikácia uzla

| Pole | Hodnota |
|---|---|
| ID uzla (Forge) | NODE-001 |
| Názov uzla | Jawra |
| Prevádzkovateľ | *(názov entity — doplní prevádzkovateľ)* |
| IČO | *(doplní prevádzkovateľ)* |
| Sídlo / pôsobnosť | Slovensko *(sídlo doplní prevádzkovateľ)* |
| Dátum založenia uzla | 2026-09-01 |

## 3.2 Kapacita

| Pole | Hodnota |
|---|---|
| Stroje | *(počet a typ / technológia, napr. 1× FDM)* |
| Dostupná kapacita | *(hod./týždeň alebo ks/týždeň — orientačne)* |

## 3.3 Materiály

- *(zoznam materiálov, napr. PLA, PETG)*
- Farby a materiály na vyžiadanie: *(poznámka)*

## 3.4 Pracovný objem

| Stroj | Max. rozmery (mm) | Obmedzenia geometrie |
|---|---|---|
| *(stroj 1)* | *(X × Y × Z)* | *(ak sú)* |

## 3.5 Ponuka

- Tlač na zákazku (kusová výroba podľa dodaného modelu)
- Vlastný katalóg modelov — *(odkaz na katalóg doplní prevádzkovateľ)*
- *(ďalšie služby: modelovanie, postprocessing…)*

## 3.6 Cenník — štruktúra

Konkrétne hodnoty vedie prevádzkovateľ mimo tohto profilu; tu je len štruktúra.

| Položka | Jednotka | Spôsob určenia ceny | Poznámka |
|---|---|---|---|
| Tlač na zákazku | hod. / g | vzorec | čas tlače + materiál |
| Model z katalógu | ks | pevná | podľa katalógu |
| Postprocessing | hod. | na vyžiadanie | |
| Doprava | ks | pevná / na vyžiadanie | |

## 3.7 Lehoty

| Pole | Hodnota |
|---|---|
| Typická lehota dodania | *(doplní prevádzkovateľ)* |
| Expres | *(áno / nie, podmienky)* |
| Potvrdenie lehoty | pri potvrdení cenovej ponuky |

## 3.8 Kontakt

| Pole | Hodnota |
|---|---|
| Zodpovedná osoba | *(doplní prevádzkovateľ)* |
| Kanál | *(e-mail / formulár / web)* |
| Preferovaný kanál | *(doplní prevádzkovateľ)* |

## 3.9 Stav dostupnosti

**Stav:** `neprijíma` — uzol sa pripravuje na spustenie.
**Dátum poslednej aktualizácie profilu:** 2026-09-01

---

## Change log

| Dátum | Verzia | Zmena |
|---|---|---|
| 2026-09-01 | 0.1 | Prvá verzia profilu podľa štandardu Forge v0.1; identifikácia uzla a štruktúra sekcií, hodnoty čakajú na doplnenie prevádzkovateľom |
