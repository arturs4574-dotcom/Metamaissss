# Spēle: "Kauliņš"

## Versijas
- v1.0 – Ideja
- v2.0 – Apraksts un prasības
- v3.0 – Testi

## 1. Spēles apraksts
Spēlētājs met metamā kauliņa metienu un pārvietojas uz priekšu.
Spēles mērķis ir sasniegt 10. lauciņu.

## 2. Prasību specifikācija

### Funkcionālās prasības
1. Tiek izmantots viens sešpusīgs metamais kauliņš.
2. Spēlētājs pārvietojas par uzmesto skaitli.
3. Spēle beidzas, kad sasniegts 10. lauciņš.

### Nefunkcionālās prasības
1. Spēle ir viegli saprotama.
2. Spēle darbojas bez kļūdām.

## 3. Struktūrskice
Sākums → Mest kauliņu → Pārvietoties →  
Ja pozīcija ≥ 10 → Uzvara  
Citādi → Turpināt spēli

## 4. Testpiemēru kopa
- Tests 1: 8 + 2 → uzvara
- Tests 2: 4 + 3 → pozīcija 7