---
layout: post
---

# Inledning av Nätverkskabel

---

### TP-kabel/Nätverkskabel

TP står för Twisted Pair vilket innebär att de åtta ledarna i kabeln är tvinnade parvis. Detta spelar stor roll för kabelns elektriska egenskaper.

- **Mjuk kabel** är mångkardelig, vilket innebär att de åtta ledarna i sin tur består av många tunna trådar (kardeler). Den mjuka kabeln används till anslutningskablar (patchkablar). Vid montering av RJ45-kontakter ska mjuk kabel användas.
- **Solid kabel** är lite stelare då den är enkelkardelig (enkeltrådade ledare). Solid kabel används vid fast installation. För att kunna slitsa/kontaktera kabeln i plint krävs solid kabel. Plintar för slitsning sitter i alla nätverksuttag och patchpaneler.

---

### RJ45-kontakten

Bortsett från fiberlösningar används uteslutande RJ45-kontakter på nätverkskablar. Kontakten har stift för åtta ledare, och vid montering måste ett speciellt pressverktyg användas. RJ45-kontakten finns i både skärmat och oskärmat utförande beroende på om den ska sitta på en UTP- eller FTP-kabel. Den skärmade är lätt att känna igen eftersom den har ett hölje av metall längst ut, medan den oskärmade är genomskinlig.

---

### Koppling av RJ45

Inkoppling av ledarna kan göras enligt två olika strukturer, där skillnaden är ordningen som ledarna placeras efter. De tekniska namnen på dessa strukturer är T568A och T568B där den sistnämnda är vanligast i Sverige. Vilken av strukturerna som väljs spelar ingen roll så länge kabeln får samma koppling i båda ändar.

---

### Färgkodning

Paren i en TP-kabel har varsin färg: orange, grön, blå och brun. Den ena ledaren är helfärgad och den andra är vit med ett streck av den aktuella färgen. Denna färgkodning används för att på ett enkelt sätt kunna särskilja de olika ledarna.

---

### Korskoppling

När två likadana enheter ska anslutas direkt till varandra ska kablaget vara korskopplat. Idag är de flesta nätverksenheter utrustade med en funktion som kallas Auto-negotiation (MDI/MDIX). Med den funktionen på någon av enheterna kommer det eventuella behovet av en korskoppling att lösas automatiskt, oavsett om enheterna är sammanlänkade med en rak eller korskopplad kabel. Saknas funktionen kan en rak kabel korskopplas med hjälp av en korskopplingsadapter.

---

## Olika sorters av nätverkskablar

---

### Cat. 5e

Vanligast i hemmamiljöer, stödjer en hastighet på upp till 1 Gb/s, vilket räcker gott och väl för de vanligaste användningsområdena i hemmet och små företag. Bandbredden ligger på 100 MHz. E:et i Cat 5e står för enhanced, vilket berättar att det rör sig om en vidareutveckling av den äldre Cat 5-klassen som inte kunde prestera högre än 100 Mb/s. Genom en uppdatering av Ethernetprotokollet IEEE 803.3 kan Cat 5e-kablar stödja upp till 2,5 Gb/s.

---

### Cat. 6

Uppföljaren på Cat. 5e och klarar bandbredden 250 MHz. Det gör det möjligt att leverera ännu högre hastigheter. Cat. 6 är lämplig för hastigheter över 1 Gb/s. Cat. 6 klarar faktiskt hastigheter upp till 10 Gb/s, men då endast på kortare kablar (max. 55 m). Ska nätverkskabel installeras i hela hemmet bör en kabel ur denna kategori, eller uppföljaren, användas för att förbereda för framtiden. Genom en uppdatering av Ethernet-protokollet IEEE 803.3 kan Cat. 6-kablar stödja upp till 5 Gb/s.

---

### Cat. 6a och 7

Cat 6a är en uppdaterad variation av Cat 6 där A:et står för Augmented. Cat 6a klarar bandbredden 500 MHz och stödjer hastigheter upp till 10 Gb/s, även på kablar som är 100 meter långa. Cat. 6a-ledarna är grövre än Cat. 6-kablarna och oftast tvinnade med tätare avstånd för att klara den högre bandbredden. Cat. 6a-kablar är dessutom ofta skärmade. Cat. 7 är en annan uppföljare som också är gjord för och är lämplig för 10 Gb/s (bandbredd 600 MHz). Den måste ha individuellt skärmade par för att klara detta utan att ledarna börjar störa varandra. Cat. 7 använder inte en vanlig RJ45-kontakt och har därför inte blivit populär hos hemanvändare.

---

### Cat. 8 och 8.2

Den senaste standarden för nätverkskablar och delas upp i två olika klasser, Cat 8.1 och Cat. 8.2. Cat 8 är alltid individuellt skärmade, har grövre ledare än tidigare standarder och klarar bandbredden 2000 MHz. Cat 8.1 använder vanlig RJ45-kontakt och stödjer hastigheter upp till 25 Gb/s på maximalt 30 meter. Cat. 8.2 klarar hastigheter upp till 40 Gb/s men använder precis som Cat. 7 inte vanlig RJ45-kontakt.

---

## TP-kabeln är känslig och fel kan uppstå om:

- Kabeln monteras i alltför skarpa böjar. Böj inte kabeln mer än att det går att lägga en snusdosa i böjen.
- Kabeln kläms åt för hårt med buntband eller spikas fast med för små klamrar. 7 mm brukar vara en lagom storlek på så kallad vampire tap.
- Paren tvinnas upp för mycket (max 13 mm för Cat. 5e respektive max 5 mm för Cat. 6 och Cat. 6a).
- Kablarna är för långa (max. 100 meter mellan två enheter).

---

## En beskrivning av olika typer av kablar som kan användas beroende på hastighet och längd

| Standard     | Hastighet       | Beskrivning                                      |
|--------------|-----------------|--------------------------------------------------|
| 10BaseT      | 10 Mb/s         | TP-kabel, två ledningspar är i bruk. Används inte längre. |
| 100Base-TX   | 100 Mb/s        | TP-kabel, två ledningspar är i bruk. Fungerar med Cat. 5e-kablar. |
| 1000Base-T   | 1000 Mb/s (1 Gb/s) | TP-kabel, fyra ledningspar är i bruk. Lämpligt med Cat. 6-kablar (fungerar med Cat. 5e-kablar). |
| 1000Base-F   | 1000 Mb/s (1 Gb/s) | Fiber optic.                                    |
| 2,5GBase-T   | 2500 Mb/s (2,5 Gb/s) | TP-kabel, fyra ledningspar är i bruk. Lämpligt med Cat. 5e-kablar. |
| 5GBase-T     | 5000 Mb/s (5 Gb/s) | TP-kabel, fyra ledningspar är i bruk. Lämpligt med Cat. 6-kablar. |
| 10GBaseT     | 10000 Mb/s (10 Gb/s) | TP-kabel, fyra ledningspar är i bruk. Fungerar med Cat. 6, Cat. 6a-, Cat. 7- och Cat 8-kablar. |
##### 100Base-TX används för att beskriva nätverkshastighet och kabeltyp. I detta fall betyder 100 att hastigheten är 100 megabit per sekund, Base att det är basbandsöverföring (vanlig nätverkstrafik), och TX att det är en TP-kabel där endast två av de fyra paren används.
