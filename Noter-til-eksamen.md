
## SDLC – System Development Life Cycle

* SDLC repræsenterer en struktureret tilgang til softwareudvikling og beskriver de faser, som et system gennemgår fra start til slut. De primære faser er:

* Analyse: Identificere og forstå krav og behov fra interessenter.
* Design: Planlægge og designe systemets arkitektur og komponenter.
* Implementering: Udvikle og kode løsningen.
* Deployment: Udrulning af det færdige produkt til brugerne.

* SDLC kan illustreres lineært eller iterativt afhængigt af den valgte procesmodel.

### 2. Procesmodeller
* Procesmodeller angiver rækkefølgen og værdigrundlaget for aktiviteter i SDLC. De beskriver, hvordan udviklingen organiseres:

#### a. Vandfaldsmodellen
* En lineær tilgang: Hver fase afsluttes, før den næste begynder.
* God til projekter med klare krav.
* Begrænset fleksibilitet.

#### b. Spiralmodellen
* Iterativ tilgang med fokus på risikoanalyse.
* Bruges, når projektet kræver flere iterationer og feedback-loop.

#### c. Agile Modeller (f.eks. Scrum og XP)
* Fokus på fleksibilitet, hurtige iterationer og løbende leverancer.
* Scrum: Organiseret i sprints med faste roller som Scrum Master og Product Owner.
* Extreme Programming (XP): Fokus på god praksis som parprogrammering og testdrevet udvikling.

### 3. Metoder
* Hvor procesmodeller beskriver rækkefølgen af aktiviteter, fokuserer metoder på indholdet i hver fase, herunder:

* Hvilke dokumenter og diagrammer der skabes (fx use cases, ER-diagrammer).
* Praktiske frameworks som Scrum, Lean Software Development, og DevOps.

**Eksempler på metoder:**

* Scrum: En agil tilgang med fokus på korte iterationscyklusser.
* DevOps: Integration af udvikling og drift for kontinuerlig leverance.
* Kanban: Visualisering af opgaver med en flowbaseret tilgang.

### 4. Vigtigste Begreber
* Paradigme: En overordnet tilgang eller tankegang inden for udvikling (fx Agile vs. Vandfald).
* Artefakter: Produkter fra udviklingsfaserne, som kan være diagrammer, kode eller dokumentation.
* Iterativ Udvikling: Gentagelse af udviklingsfaser for at forbedre systemet baseret på feedback.

## UP - Unifed Process

* UP er en iterativ og inkrementel procesmodel for systemudvikling, som fokuserer på at udvikle software i små, håndterbare iterationer.

**Fire hovedfaser:**

* **Inception:** Identifikation af kernekrav og risici.
* **Elaboration:** Yderligere kravspecificering og arkitekturetablering.
* **Construction:** Udvikling og implementering af løsningen.
* **Transition:** Overlevering til slutbrugere og systemdrift.

* **Iterativ tilgang:** UP lægger vægt på gradvis forbedring af systemet gennem gentagelser. Dette reducerer risikoen for store fejl og sikrer løbende feedback.

### Use Cases i UP
U* se cases er centrale i UP til kravhåndtering og design. De beskriver, hvordan brugere (aktører) interagerer med systemet for at opnå deres mål.

**Fordele ved use cases:**

* Fokus på brugerens perspektiv.
* Gør kravene lettere forståelige for ikke-tekniske interessenter.
* Kan skaleres i kompleksitet og formalitet.

**Struktur:**

* Navngivning: Brug altid verber til at starte (fx "Login til system").
* Aktører: Hvem bruger systemet og hvorfor.
* Scenarier: Beskrivelse af trin, der opfylder aktørens mål.

### Vigtige Begreber

**Iterativ og Inkrementel Udvikling**: 
* En tilgang, hvor systemet forbedres i små iterationer, så fejl rettes tidligt, og brugerfeedback inkorporeres løbende.

**Paradigmer og Modeller:**

* Paradigme: Overordnet tankegang (fx Vandfald, Agile, Spiral).
* Modeller: Specifikke repræsentationer af systemets aspekter (fx UML-diagrammer).

**UML (Unified Modeling Language):**

* Et visuelt sprog til at beskrive systemers struktur og interaktion.
* Bruges til at skabe diagrammer, der fungerer som "blueprints" for design.

**Use Cases:**

* Skriftlige beskrivelser af interaktioner mellem system og brugere.
* Enkle og effektive til at kommunikere krav.

**Alternative flows** er en vigtig del af Unified Process (UP) og use cases. De beskriver, hvad der sker, når noget går galt (fejlscenarier), eller hvis brugeren vælger en anden sti (valgfrie handlinger). UP lægger vægt på disse flows, fordi de:

* Reducerer risiko ved at forberede systemet på uventede hændelser.
* Forbereder systemet på kompleks brugeradfærd.
* Sikrer kvalitet ved at teste scenarier ud over det ideelle flow.

**Agile vs. Vandfald:**

* Agile: Fleksibel og iterativ.
* Vandfald: Struktureret og lineær.

## XP - Extreme Programming
Extreme Programming (XP) er en agil softwareudviklingsmetode designet til at håndtere risici i softwareprojekter gennem iterative processer og stærkt samarbejde. Det er en disciplin, der fokuserer på:

* Risikohåndtering: XP adresserer projektets almindelige udfordringer som forsinkelser, høje fejlrate, og ændringer i krav.
* Iterative kortcyklusser: XP bryder projektet ned i korte iterationer (1-4 uger), hvor de vigtigste funktioner implementeres først.
* Kvalitet: Programmering med automatiserede tests og løbende forbedringer sikrer software af høj kvalitet.

**XP fremhæver fire kerneværdier:**

* Kommunikation: Etablering af stærk kommunikation i teamet.
* Enkelthed: Fokus på simple løsninger, der løser problemet.
* Feedback: Konstant feedback fra tests og kunder.
* Mod: Mod til at ændre kurs eller udfordre antagelser.

### Processer i XP
XP’s processer fokuserer på løbende iterationer og fleksibilitet. Nogle nøgleelementer inkluderer:

**The Planning Game:**

* Hurtig planlægning af scope for næste iteration.
* Samarbejde mellem forretning og udvikling for at prioritere funktioner baseret på værdi og teknisk vurdering.

**Små releases:**

* Udgiv tidlige versioner af systemet og iterer hurtigt.

**Kontinuerlig integration:**

* Koden integreres og testes flere gange dagligt for at undgå konflikter.

**40-timers uge:**

* Maksimer produktiviteten gennem realistiske arbejdstider og undgå overarbejde.

### Metoder
XP indeholder specifikke praksisser, som fungerer sammen og forstærker hinanden:

**Pair Programming:**
* To udviklere arbejder sammen på én maskine, hvilket øger kvalitet og deling af viden.

**Testing:**
* En kernepraksis, hvor automatiserede tests sikrer systemets robusthed.

**Refactoring:**
* Konstant forbedring af koden uden at ændre dens funktionalitet.

**Metafor:**
* Et fælles, simpelt billede af systemets struktur for at lette forståelsen.

**Kollektiv ejerskab:**
* Enhver i teamet kan ændre kode, hvilket fremmer hurtigere og bedre løsninger.

### Vigtige Begreber
**Fire kontrolvariabler:**
* Scope, tid, kvalitet, og omkostninger skal balanceres. Typisk vælges tre af disse variabler, mens den fjerde justeres.

**Enkel design:**
* Fokuser kun på, hvad der er nødvendigt nu, og fjern unødvendig kompleksitet.

**Kontinuerlig feedback:**
* Løbende kommunikation mellem udviklere og kunder sikrer, at systemet opfylder forretningsmålene.

**On-site kunde:**
* En reel kunde er til stede i teamet og hjælper med at definere krav og prioritere funktionalitet.

**Automatiserede tests:**
* En regel i XP er, at en funktion uden test ikke eksisterer.

## BDD

## TDD

## SCRUM

## AGILE

### De 12 Principper bag Agile Manifesto

**Agile Manifesto definerer de centrale værdier i agil softwareudvikling og prioriterer dem på følgende måde:**

**1. Individer og interaktioner frem for processer og værktøjer:**
* Fokus på samarbejde og kommunikation mellem teammedlemmer, fremfor at lade processer eller værktøjer diktere arbejdet.

**2. Arbejdende software frem for omfattende dokumentation:**
* Levering af funktionel software har højere prioritet end at producere omfattende dokumentation, der ofte bliver forældet.

**3. Kundesamarbejde frem for kontraktforhandling:**
* Samarbejde med kunden for at forstå deres behov, i stedet for blot at følge kontraktuelle forpligtelser.

**4. Reageren på ændringer frem for at følge en plan:**
* Agil udvikling omfavner ændringer, selv sent i udviklingsprocessen, for at sikre, at software opfylder aktuelle behov.

**NOTE:** Disse værdier betyder ikke, at elementerne til højre (processer, dokumentation, kontrakter og planer) er uvigtige, men de vægtes mindre end dem til venstre.
##
**1. Tidlig og kontinuerlig levering:**
* Kunden skal tilfredsstilles gennem tidlig og løbende levering af værdifuld software.

**2. Velkommen ændringer:**
* Selv sent i udviklingsprocessen skal ændringer i krav omfavnes for at give kunden en konkurrencefordel.

**3. Hyppige leverancer:**
* Software skal leveres ofte, ideelt set med iterationer på et par uger til et par måneder.

**4. Samarbejde mellem forretning og udvikling:**
* Forretningsfolk og udviklere skal arbejde tæt sammen dagligt.

**5. Motiverede individer:**
* Projekter skal bygges omkring personer, der har de nødvendige ressourcer og støtte, samt tillid til at løse opgaven.

**6. Ansigt-til-ansigt-kommunikation:**
* Direkte samtale er den mest effektive måde at kommunikere på i et udviklingsteam.

**7. Arbejdende software som målestok:**
* Fremgang måles primært ud fra, om softwaren fungerer som forventet.

**8. Bæredygtig udvikling:**
* Udviklingshastigheden skal kunne opretholdes konstant over tid.

**9. Teknisk ekspertise og god design:**
* Vedvarende fokus på teknisk kvalitet og design fremmer agilitet.

**10. Enkelhed:**
* Fokuser på at minimere mængden af arbejde, der ikke er nødvendigt.

**11. Selvorganiserende teams:**
* De bedste løsninger og designs opstår fra selvorganiserende teams.

**12. Løbende refleksion og tilpasning:**
* Teamet skal regelmæssigt reflektere over deres processer og justere dem for at blive mere effektive.


## Estimering - Outsourcing - Plan

## Robusthedsdiagram

## Dare Share Care


mål, kontekst, kilder og forventninger
