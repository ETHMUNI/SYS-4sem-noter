
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
Use cases er centrale i UP til kravhåndtering og design. De beskriver, hvordan brugere (aktører) interagerer med systemet for at opnå deres mål.

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

Behaviour Driven Development (BDD) er en softwareudviklingsmetode, der bygger videre på principperne fra Test Driven Development (TDD). Målet med BDD er at sikre, at udviklingen fokuserer på den adfærd, som brugerne forventer, ved at bruge fælles sprog og samarbejde mellem udviklere, testere og interessenter.

**Metoder i BDD**
BDD bruger følgende metoder og værktøjer til at definere og teste krav:

* User Stories:
 * Hver funktionalitet beskrives som en User Story:
 * "Som [rolle] vil jeg [handling], så jeg kan [mål]."

* Gherkin-sprog:
 * Et formelt men letforståeligt sprog til at skrive accepttests. Det bruger nøgleord som:
 * Feature: Overordnet beskrivelse af, hvad der skal laves.
 * Scenario: Et specifikt tilfælde af, hvordan systemet skal opføre sig.
 * Given: Forudsætninger (hvad der er sandt i starten).
 * When: Handlinger eller begivenheder.
 * Then: Forventede resultater.

* Automatisering af tests:
 * Værktøjer som Cucumber og SpecFlow bruges til at køre disse scenarier automatisk og validere adfærden.

### Processer i BDD

* Fra User Story til Accepttest:
 * Start med at beskrive, hvad brugeren vil opnå.
 * Brug Gherkin-scenarier til at beskrive adfærden.
 * Opret automatiserede tests for at validere adfærden.

* Samarbejde:
 * BDD kræver, at udviklere, testere og interessenter arbejder tæt sammen for at definere krav og prioritere funktionalitet.

* Iterativ tilgang:
 * Byg systemet i små iterationer, hvor adfærden evalueres og forbedres løbende.

* Test First-princip:
 * Tests skrives før selve funktionaliteten implementeres, hvilket sikrer, at kravene forstås korrekt fra starten.

### Vigtige begreber
**Feature:**
* En overordnet beskrivelse af en funktion, fx "Tilføj vare til indkøbskurv."

**Scenario:**
* En konkret måde, hvorpå funktionen skal opføre sig i en given situation.

**Acceptance Criteria:**
* Specifikke krav, der skal opfyldes, for at en User Story kan accepteres.

**Gherkin-sprog:**
* Struktureret sprog til at skrive tests, der er letforståeligt for både tekniske og ikke-tekniske interessenter.

**Automatiserede accepttests:**
* Tests, der validerer systemets adfærd mod definerede kriterier, ofte kørt gennem værktøjer som Cucumber.

## TDD

TDD er en softwareudviklingspraksis, hvor test skrives før selve koden. Det handler om at sikre, at hver del af koden opfylder en defineret funktion, og at funktionaliteten testes automatisk gennem hele udviklingscyklussen.

### De tre faser i TDD:
**Red:**
* Skriv en test, der beskriver den ønskede funktionalitet.
* Testen fejler, fordi den nødvendige funktionalitet endnu ikke er implementeret.
* Dette trin sikrer, at der er et klart mål for den kode, du skal skrive.

**Green:**

* Implementér den mest enkle løsning for at få testen til at bestå.
* Målet her er ikke perfekt design, men funktionalitet, der opfylder kravene i testen.

**Refactor:**
* Forbedr koden uden at ændre dens funktionalitet.
* Fjern redundans, forbedr læsbarheden, og optimer koden for at sikre, at systemet forbliver vedligeholdeligt.

### Vigtige Begreber
* Refactoring: Konstant forbedring af kode for at undgå teknisk gæld.
* Kontinuerlig integration: Sikrer, at ny kode fungerer sammen med eksisterende kodebase.


## SCRUM
Scrum er en agil metode, der fokuserer på iterative og inkrementelle udviklingscyklusser, kaldet sprints. Centrale elementer inkluderer:

**Product Backlog:**
* En prioriteret liste over funktionaliteter og krav, som kunden ønsker.
* Indeholder både detaljerede og grove beskrivelser afhængigt af, hvor tæt de er på at blive implementeret.
* Vedligeholdes af Product Owner og ændres løbende for at reflektere ny viden.

**Sprint Backlog:**
* En liste over opgaver, der skal udføres i en specifik sprint.
* Detaljeres under sprintplanlægning og opdateres dagligt.

**Burndown Chart:**
* Grafen viser hver dag et nyt estimat af, hvor meget arbejde der mangler, indtil teamet er færdigt.

**User Stories:**
* Korte beskrivelser af funktionalitet set fra brugerens perspektiv, ofte skrevet som:
* "Som [rolle] vil jeg [handling], så jeg kan [mål]."

### Roller i Scrum

**Product Owner:**
* Repræsenterer kundens interesser og maksimerer produktets værdi.
* Ansvarlig for:
  * Oprettelse og prioritering af Product Backlog.
  * Sikring af, at teamet forstår kravene.
  
**Scrum Master:**
* Scrum Master er en hjælper, der sørger for, at Scrum kører som det skal.
* Opgaverne er:
  * Hjælpe teamet med at løse problemer.
  * Lære teamet at arbejde på en agil måde.

**Development Team:**
* Selvorganiserende og ansvarlige for at levere de aftalte User Stories.
* Vælger selv opgaver og samarbejder tæt for at opfylde sprintmålet.

### Vigtige Begreber
**Definition of Done (DoD):**
* En aftalt standard, der definerer, hvornår en User Story eller opgave er færdig.

**Team Velocity:**
* Et mål for, hvor mange User Stories teamet kan færdiggøre i en sprint. Bruges til planlægning.

**INVEST-kriterier for User Stories:**
* Independent: Kan udvikles uafhængigt.
* Negotiable: Placeholder for dialog.
* Valuable: Skaber værdi for kunden.
* Estimable: Kan estimeres.
* Small: Kan færdiggøres i en sprint.
* Testable: Skal kunne testes.

**Relative Sizing:**
* Estimering af User Stories baseret på relativ størrelse (S, M, L, XL).

**Planning Poker:**
* En metode til estimering, hvor teammedlemmer vælger estimater anonymt og diskuterer forskelle for at nå konsensus.

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

## Spikes
En Spike er en særlig type user story i agile rammer, der bruges til at reducere usikkerheder og risiko. Spikes hjælper med at:

* Afdække ukendte elementer (tekniske eller funktionelle).
* Gøre user stories lettere at estimere og implementere.
* Forberede teamet på komplekse udfordringer.

**Der findes to typer Spikes:**

**1. Tekniske Spikes:** Undersøger tekniske løsninger (fx "build vs. buy", ydeevne eller teknologivalg).
**2. Funktionelle Spikes:** Undersøger, hvordan brugere interagerer med systemet (fx prototyper, UI-design).

### Sådan bruges Spikes
* I backloggen: De prioriteres som user stories og afsluttes i en iteration.
* Resultater: Spikes fører til beslutninger, prototyper eller analyser, ikke nødvendigvis færdig kode.
* Retningslinjer: Brug Spikes til store usikkerheder og undgå at blande dem med deres relaterede user stories i samme iteration.

### Vigtige begreber
* Teknisk Spike: Bruges til at evaluere tekniske aspekter af en løsning.
* Funktionel Spike: Bruges til at undersøge brugeroplevelser eller funktionelle krav.
* Demonstrerbare resultater: Resultatet af en Spike skal være synligt og brugbart for teamet (fx en prototype eller analyse).
* Undgåelse af overlap: Planlæg Spikes separat fra deres afledte historier for at mindske risiko.
* Risikoreduktion: Spikes bruges til tidligt at håndtere usikkerheder i projektet.

## Dare Share Care

**Dare – Være modig og udfordre sig selv:**
* Tør tage nye opgaver og udfordringer op.
* Være åben overfor at lære nye færdigheder og arbejde uden for sin komfortzone.

**Share – Dele viden og erfaringer:**
* Aktivt dele ideer, viden og erfaringer med kolleger eller i praktikmiljøet.
* Bidrage til fælles forståelse og udvikling.

**Care – Vise omsorg og respekt:**
* Udvise empati og respekt for andres idéer, meninger og behov.
* Fokusere på godt samarbejde og støtte hinandens udvikling.
