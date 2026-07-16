
bevat de originele docentuitwerkingen vanuit de cursus en wordt gebruikt als referentie en vergelijking.

---

## Gebouwde onderdelen

De huidige CPU bevat onder andere:

- RAM geheugen
- Registers
- ALU (Arithmetic Logic Unit)
- Clock systeem
- Control Section
- Stepper
- Fetch Cycle
- Instruction Decoder
- ALU Instructions
- Load en Store Instructions
- Data Instructions
- Jump Register Instructions
- Jump Address Instructions
- If Instructions
- Clear Flags Instruction

Deze onderdelen werken samen om instructies uit het geheugen op te halen, te interpreteren en uit te voeren.

---

## CPU Architectuur

De CPU werkt volgens een klassieke:

**Fetch - Decode - Execute cyclus**

Het proces bestaat uit:

1. Een instructie wordt opgehaald uit het geheugen (**Fetch Cycle**)
2. De Control Section decodeert de instructie
3. De juiste onderdelen binnen de CPU worden aangestuurd
4. De instructie wordt uitgevoerd door bijvoorbeeld de ALU of het geheugen

---

## Assembly Language

Een volgende stap binnen dit project is het ontwikkelen van programma's in een eigen Assembly Language.

Het doel hiervan is:

- eigen programma's schrijven voor de CPU
- programma's laden in het geheugen
- instructies testen
- fouten analyseren en debuggen

Momenteel wordt gewerkt aan het maken en testen van Assembly programma's voor de eigen CPU.

---

## Toekomstige uitbreidingen

Mogelijke toekomstige uitbreidingen:

- Uitbreiden van een 8-bit naar een 16-bit architectuur
- Uitbreiden van de ALU met extra berekeningen:
  - subtractie
  - vermenigvuldiging
  - deling
- Ontwikkelen van een eigen assembler
- Ontwikkelen van een compiler richting een hogere programmeertaal
- Port Mapped I/O
- Verdere uitbreiding van de CPU instructieset
- Experimenteren met een volledige computerarchitectuur

Het uiteindelijke doel is om vanuit een zelf ontworpen hardwarelaag uiteindelijk programma's op een hoger abstractieniveau te kunnen uitvoeren.

---

## Projectstatus

🚧 **Actief in ontwikkeling**

De huidige focus ligt op:

- Assembly programma's maken
- CPU debuggen
- Nieuwe instructies toevoegen
- Uitbreiden van de architectuur

---

## Inspiratie en leerbron

De basis van dit project is geïnspireerd door de Udemy cursus:

**Design a CPU - van sectie 3 hoofdstuk 20**

van **Ross McGowan**.

Deze cursus vormt de basis voor het bouwen van een computerarchitectuur vanaf digitale logica tot een werkende CPU.

Vanuit deze basis wordt het project zelfstandig uitgebreid met eigen experimenten, uitbreidingen en ideeën richting een completere computerarchitectuur.
