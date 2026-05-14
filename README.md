[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/G22Vs7Up)
# 🎓 Examination - Elevhanteringssystem
---

## 📝 Uppgiftsbeskrivning

**Fil att arbeta i:** `main.c`

Du ska skapa ett system som hanterar **5 elever** och deras resultat från **13 olika prov** under ett läsår. Programmet ska läsa in namn och poäng, räkna ut medelvärden och filtrera ut specifika resultat.

**Specifikation i korthet:**

- **Indata:** 5 rader. Varje rad har formatet: `Namn p1 p2 p3 ... p13`.
- **Namn:** Engelska förnamn (a-z), max 10 tecken.
- **Poäng:** Heltal 0-10.

Totalt kan du få **100 poäng** på den automatiska rättningen.

### 🚫 Regler & Begränsningar (Viktigt!)

För att det automatiska rättningssystemet ska fungera måste du följa dessa regler strikt:

1. **Ingen extra text:** Programmet får **INTE** skriva ut text som "Mata in namn:" eller "Resultatet är:". Endast namnen på eleverna ska skrivas ut.
2. **Exakt utskrift:** Varje namn ska skrivas ut på en egen rad.
3. **Versaler:** Alla namn ska skrivas ut med Stor Begynnelsebokstav (t.ex. "Alice"), oavsett hur de matades in.
4. **Inläsning:** Använd med fördel `scanf()` för att hantera inmatningen.

### Funktionella Krav & Poängsättning

Din kod rättas i steg. Även om du har småfel (t.ex. fel stor bokstav) kan du få poäng för logiken.

#### 1. Grundläggande funktionalitet (20p)

- **(20p)** Koden ska kompilera och köra utan att krascha när testdata matas in.

#### 2. Analys: Högst medelpoäng (30p)

- **(15p) Logik:** Programmet identifierar korrekt _vilken_ elev som har högst medelpoäng (oavsett stor/liten bokstav).
- **(15p) Format:** Namnet skrivs ut korrekt med stor begynnelsebokstav (t.ex. "Charlie").

#### 3. Analys: Under gruppens snitt (30p)

- **(15p) Logik:** Programmet räknar ut totala medelvärdet och identifierar _vilka_ elever som ligger under detta (oavsett stor/liten bokstav).
- **(15p) Format:** Namnen skrivs ut med stor begynnelsebokstav och i samma ordning som de matades in (t.ex. "Bob" och "Dave").

---

## Inlämning & Video (20p)

Förutom koden ska du spela in en kort skärminspelning där du demonstrerar din lösning.

1.  Spela in när du visar din lösning och berättar om hur den fungerar.
2.  Döp filen till exakt: vedio.mp4
3.  Lägg filen i rotmappen (samma ställe som denna README).
4.  **OBS:** Filen får inte vara större än 100MB.

---

## 🚀 Hur du testar din kod

Detta projekt använder automatisk rättning. Du har två sätt att se dina poäng:

### Alternativ 1: Köra testerna lokalt (Rekommenderas!)

Du kan köra exakt samma tester som GitHub använder direkt i din terminal. Detta ger dig snabbast feedback.

1. Öppna en terminal i mappen.
2. Skriv följande kommando:

```bash
make test

