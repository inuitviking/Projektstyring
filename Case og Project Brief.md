# PRINCE2 
## Virksomheden: 
Virksomheden er et aktieselskab med omtrent 8.000 ansatte på globalt plan, med underafdelinger i Argentina, Italien, Tyskland, Japan, USA og Sydafrika. 

Hovedsædet ligger i Bramming og lever af at levere IT infrastrukturer, skræddersyede programmer og kølingssystemer til datacentre. 

Der er planer om at oprette en afdeling enten i Australien eller Indonesien, for at dække den sydøstlige sektor. 

Virksomheden har i mange år haft en Laissez-faire holdning til projekt kultur, men har på det sidste, set sig slået i udbud, af firmaer med stringente projekt-retningslinjer. 

Det bliver besluttet at hovedsædet for projektorganisationen skal sidde i Danmark, med direktøren (Johnny Depp) siddende delvist i Boardet og i Cooperate Management (PRINCE2 Organization). 

Den Sydafrikanske underafdeling er relativt nystartet og har derfor en begrænset mængde kandidater til at forme en fuld organisation. Så her må man på bedst vis, forsøge at kollapse enkelte roller, hvor det det er muligt (Tailoring a project).

Applikationsteamet er primært spredt ud over to lokationer, USA og Japan, hvor den daglige kommunikation mellem de to sites primært foregår på engelsk. 
Der er dog en lille underafdeling i Argentina, der primært står for at udvikle de interne programmeringsopgaver. 
Der er en allerede eksisterende projektkultur for alle ansatte udviklere. De anvender SCRUM og det forventes at de fortsætter denne kultur, selv efter implementeringen af PRINCE2 

Hver site har deres egen infrastruktur gruppe, da der også ydes 24-timers on-site support for de allerede afsluttede projekter. 

Det danske site er mest af alt en administrativ enhed, for de globale operationer, med en begrænset mængde teknisk personale. 
Hvis der brug for teknisk personale kan de hive personale op fra den tyske afdeling, der er allokeret i det nordlige Tyskland, tæt ved Hamborg.
 

## Case 1 
### Oprettelse af Organisations struktur 
I skal beslutte jer for en organisationsstruktur. 

I skal beskrive hvilken slags person der skal besætte flg. Roller: 

- Project Board
    - **Senior User** - En karismatisk person, men kontant om kvaliteten og brugervenligheden af projektet.
    - **Project Executive** - En realistisk person med selv kontrollen og erfaringen til at stoppe når projektet er færdigt.
    - **Senior Supplier** - En som kan finde de rette løsninger til interne problemstillinger når det gælder hardware, værktøj eller mennesker.
- **Project Manager** - En person der kan arbejde med mange bolde i luften, og kan arbejde med mange typer personer.
- **Change Authority** - En der kan håndtere ansvaret for beslutninger og kan hjælpe med styrer flowet af projektet.
- **Project Assurance** - En person der kan have sin egen holdning og forståelse af den information som kommer længere op i strukturen.

**Vigtige hensyn:**

- Hvilke roller ville tage skade af at være geografisk adskilt fra resten af teamet?
  - Team Manager fra Team members
  - Project Manager fra Project Assurance og Project Suport
- Hvilke roller kan lægges sammen i forhold til de små afdelinger, såsom Sydafrika?
  - Project Manager kan også være:
    - Team Manager
    - Project Support
    - Change Authority (Hvis Project Boarded tillader det)
  - CEO
    - Executive (men så dør baby)
- Hvordan sikres leverancer og kvalitet i den globale organisation?
  - Takket været Senior User kan vi sikre kvalitet af det leverede produkt
  - Takket været Senior Supplier kan vi sikre kvalitet af råmaterialer, værktøjer, og medarbejdere.
- Hvilke roller kan varetages centralt og hvilke roller skal være decentrale og hvad gør man når man benytter decentrale roller?
- Centralt:
  - CEO
  - Project Board
  - Change Authority?
- Decentrale:
  - Team Members
  - Team Manager
  - Project Manager
  - Project Support
  - Project Assurance

## Case 2 
### Datacenter 
Facebook har skrevet kontrakt med firmaet, med henblik på at at oprette et datacenter i Odense. 

I denne opgave skal alle afdelinger inddrages, da der både skal laves køling, infrastruktur og datacenteret skal operere på en meget modificeret Linux platform, som firmaets anseelige udviklingshold skal stå for.

Centeret skal stå klart om et år og bygningerne er næsten færdige. 

I businesscasen starter man ud med at vurdere at den samlede indkomst for hele projektet er estimeret til omkring 184 millioner DKK. Det bliver vurderet fra ledelsens side at der kan gives grønt lys for kontrakten. 

Firmaet beslutter at der skal være tre faser (Stages) i projektet: 

- Køling
  - Tager i alt 8 måneder 
- Infrastruktur 
  - Tager i alt 6 måneder 
- Udvikling 
  - Tager i alt 11 måneder 

**Beskriv nu hvordan I vurderer at de forskellige leverancer kan overlappe hinanden. Med andre ord, hvordan presses 25 måneder ned til 12?**

Udviklingen er ikke afhængig af infrastrukturen eller køling, så de kan gå i gang med det samme. Kølingen er dog afhængig af dele af infrastrukturen. Så infrastrukturen skal sættes i gang først, her kan man prioritere de elementer som kølingen er afhængig af og påbegynde kølingen 4 måneder inde i infrastruktur opgaverne.

- **Hvad er tolerancen i projektets tidsplan og kan den sammenhænges med en tolerance indenfor kvalitet?**

Tolerancen er ikke specielt stor, der er kun et år til at færdiggøre projektet bestemt fra kundens side af. Det kan have betydning for kvaliteten af det endelige produkt.

- **Mener i, at man fra ledelsens side, har kalkuleret nok tid til projektet?**

Det lader ikke til at ledelsen har haft noget valg, da facebook specificerede at det skulle stå færdigt om et år. Det kunne muligvis godt have skubbet for at få 2 måneder ekstra.

**Lav en simpel risiko analyse der beskriver de forskellige risici inden for faserne, hvor firmaet kan komme i unødig tidspres og forsøg at finde løsninger for det.**

### **TODO: *Lav en risiko analyse***
Vurderingsscore: 1 til 5, hvor 5 er højeste risiko

Sandsyndlighedsscore: 1 - 5, hvor 5 er meget sandsyndlig

|Risiko|Vurdering|Sandsyndlighed|Løsning|
|------|:-------:|:------------:|-------|
|Forlængelse i udviklingen|2|3|Forlængelse, med fokus på testing|
|Leverance fejl|4|1|Bestil ny levering, evt. lave om i tidsplan|
|Større fejl under udvikling|3|2|Løs bugs, evt. forlængelse|
|Lekage i køling|4|1|Bestil nye dele, evt. lappeløsninger midlertidigt. osv.|
|Forkert netværksopsætning (Rogue DHCP, forkert VLAN, osv.)|3|1|Gennemgang af netværksudstyr|
|Naturkatastrofe|5|1|Indsæt Naturkatastrofeprocedure her|
|Afbrydelse af strøm|3|1|Have generator i tilfælde af strømafbrydelse|


## Case 3 
### Projektets initiering 
Inden projektet starter op, skal der produceres nogle dokumenter. 

- **Beskriv kort, hvilke dokumenter der skal være på plads inden projektet startes op.**
    - Communication Management Aproach
    - Quality Management Approach
    - Risk Management Approach
    - Change control approach
    - Project Brief

- **Hvilke dokumenter anses ifg. PRINCE2 for at være de vigtigste?**
    - Project initiation documentation (PID)
    - Project product description

- **Ud over dokumenter, skal der også fastlægges forskellige andre ressourcer**

    - **Hvilke ressourcer skal der være tilgængelig inden projektet startes?**
      - Servere, kølere, værktøjer, tilbehør, computere, medarbejdere.

    - **Hvem sørger for at skaffe de nødvendige ressourcer til projektet?**
        - Senior Supplier
        - Senior User

- **Når projektet driftes, vil der stadig være behov for at følge op på de enkelte ting.**
  - **Hvilke dokumenter er der behov for at opdatere gennem hele projektet?**
    - Issue report
    - various Logs
    - Project initiation documentation
    - Risk register
    - Quality register

  - **Hvilke processer kan der justeres på gennem projektet, skulle man komme i tidsnød?**
    - Quality
    - Plans
  - **Hvem sidder med ansvaret for ændringer og justeringer?**
    - Change Authority, Project Board ved større ændringer

## Case 4 
### Biroller 
Gennem datacenter projektet, begynder der at melde sig problemer på leverancer. 
Problemet bliver allokeret til, at der ikke er styr på aftaler. 
Det viser sig at de aftaler der bliver indgået i de forskellige afdelinger, kun bliver opbevaret lokalt for hvert site. Ydermere viser det sig at der ikke er sørget for at overensstemme de forskellige aftaler med de forventede output. 

- **Hvad kan der gøres ved problemet?**

Man kan udvikle eller benytte en central platform til opbevaring og validering af aftaler så de fejl ikke kan ske igen. Dette burde være gjort tydeligt i Communication Management approach.

- **Hvordan kan man sikre sig at alle projektets arbejdere køre efter samme retningslinjer?**

Opbevar dem i et centralt sted og sørg for at alle på Project Boardet er blevet sat ind i dem, dette er beskrevet i Project product description (PID)

- **Hvem har ansvaret for at tilføje de nødvendige ressourcer til projektet, og hvorfor?**

Senior Supplier og Senior User på Project Boardet, det er det de er ansat til at lave.

## Project Brief
Project author: Stevie Wonder - Project Name: Facebook Odense Datacenter - Dato: 24-05-2022

### Project Definition
Dette projekt går ud på at udbygge og udruste et datacenter i Odense til Facebook.

**Project Objectives**
- Udbyg et datacenter
- Lave et base image af en Linux distribution

**Project Scopes**
- Udbyg infrastrukturen til køling anlæg samt servere.
- Udbyg et køling anlæg.
- Udbyg infrastrukturen i form a servere.
- Udvikle en specialiceret Linux distribution til serverene.

**Project Tolerances**
- Tid: 12 måneder
- Budget: 184.000.000 DKK
- Kvalitet: Datacenteret i sin helhed skal møde vores kvalitetskrav.

### Business case
**Reasons**
- Muligheden for at bygge forhold med kunden, så man kan få fremtidige kontrakter til andre lokationer.
- En chance for at udvide klientel da det er en højprofils kunde.
- Få skradersyget programmer efter virksomhedens behov.

**Expected Benefits**
- 24-timers on-site support 17.000.000 DKK (årlig)

**Risks**
- Kunden ønsker ikke at arbejde med os efter projektet.
- Kunden ikke ønsker vores løbende serivces.

**Costs**
- Server: 80.000.000 DKK
- Netværksudstyr: 20.000.000 DKK
- Andet hardware: 500.000 DKK
- Software License: 500.000 DKK
- Køling: 5.000.000 DKK
- El arbejde: 5.000.000 DKK



### Project Product Description
**Purpose**
- ***(der er intet information om dette i casen så det er revet ud af røven)*** Datacenteret har til formål at forbedre sikkerheden på Facebooks brugers data, at forbedre oplevelsen som bruger af Facebook i Danmark og at etablere et forhold til brugerne med mere tillid ved at lagre alt dansk data i Danmark.

**Composition**
- Udvælg infrastruktur
- Udvælg køling anlæg
- Udbyg infrastruktur
- Udbyg køling anlæg
- Udvælg kompatible værktøjer og utilities til Linux distribution
- Udvikle Linux distribution
- Byg Linux distribution

**Derivation**
- Cisco (networking)
- Supermicro (servers)
- APC (ups)
- LG (cooling)

**Development skills required**
- Purchasing skills
- Account Management
- System administration
- C/C++ programming
- Compiler configuration

### Approach

Server og netværksopsætning designes dimmensioneres herefter kølingssystemet dimmensioneres, og vil blive indstalleret samtidig. Parallelt udvikles der skradersyget software løsning. Projektet håndteres internt.

### Project Management Team

- Project Board
    - **Executive**: Jacob "Johnny Depp" Enevoldsen Duus
    - **Senior User**: Stevie Wonder
    - **Senior Supplier**: Jason Statham

- **Project Manager**: Billy Ray Cyrus

- **Project Assurance**: Miley Cyrus

- **Project Support**:
    - Justin Timberlake
    - Roberty Downey Jr.
    - Marilyn Monroe

- **Team Manager**:
    - Tommy Seebach
    - Andy Milonakis
    - Daniel Craig
    - Daniel Radcliff
    - Alfred Matthew "Weird Al" Yankovic

- **Special Guests**:
    - Joel Osteen (Pay him in private jets)

### Role Descriptions

**Projektet bruger de roller som er beskrevet i Prince2**

- [Se her](https://prince2.wiki/roles/) for at læse om rollerne
