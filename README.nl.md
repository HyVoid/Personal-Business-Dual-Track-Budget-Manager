[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Geïntegreerd budgetraamwerk voor privé en zakelijk
### Scheid privé geld en zakelijk geld zonder het vermogen te verliezen om geïntegreerde financiële beslissingen te nemen.

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)
![Tool](https://img.shields.io/badge/Type-Decision%20Support-orange.svg)

**Een gratis browser- en Excel-toolkit die verspreide transacties omzet in een gestructureerd financieel besturingssysteem—zonder installatie, abonnementen of boekhoudsoftware.**

**Geen registratie. Geen installatie. Gratis in uw browser.**

Probeer de browserversie gratis. Als u de Excel-versie nodig heeft, kunt u die kopen met een geld-terug-garantie van 30 dagen zonder vragen.
>
> 🌐 Openen in browser → [HTML-livedemo](https://hyvoid.github.io/Personal-Business-Dual-Track-Budget-Manager/)  
> 📥 Download Excel → https://github.com/HyVoid/Personal-Business-Dual-Track-Budget-Manager/blob/main/Personal%20%26%20Business%20Unified%20Budget%20Framework.xlsx

---

## Wat het u helpt bijhouden

- Persoonlijke uitgaven versus zakelijke bedrijfskosten, zonder beide te vermengen.
- Werkelijke winstgevendheid van het bedrijf na onttrekkingen door de eigenaar.
- Minimale persoonlijke levensonderhoudskosten versus discretionaire levensstijluitgaven.
- Wekelijkse budgetafwijking, voordat overbesteding een maandelijkse verrassing wordt.
- Bedrijfsrunway en het vermogen om aankomende verplichtingen te dekken.
- Spaarvoortgang en vermogensopbouw naast operationele prestaties.

---

## Waarom ik dit heb gebouwd

De meeste kleine bedrijven en solo-ondernemers falen niet omdat het hen aan transactieregistraties ontbreekt.

Zij falen omdat ze die registraties niet correct kunnen interpreteren.

Persoonlijke uitgaven lekken naar zakelijke rekeningen. Bedrijfswinsten lijken groter dan de werkelijkheid omdat onttrekkingen door de eigenaar worden genegeerd. Levensstijlinflatie verstopt zich in tientallen kleine transacties. [...]

De meest voorkomende reactie is óf niets doen, óf boekhoudsystemen adopteren die te zwaar aanvoelen voor dagelijks gebruik.

Ik bouwde dit raamwerk nadat ik herhaaldelijk hetzelfde analytische falen had gezien:

> Geld werd bijgehouden.
>
> Beslissingen werden dat niet.

Bijvoorbeeld:

**Voor**

Een bedrijfseigenaar ziet \$12,000 op de bank en concludeert:

> "Het bedrijf is gezond."

Er bestaat geen onderscheid tussen:

- toekomstige operationele verplichtingen,
- persoonlijke levensbehoeften,
- bedrijfswinstgevendheid,
- spaarverplichtingen.

Onttrekkingen door de eigenaar gebeuren willekeurig.

Persoonlijke uitgaven verlopen soms via zakelijke rekeningen.

Het beschikbare-contanten-cijfer wordt misleidend.

**Na**

Dezelfde \$12,000 worden gescheiden in:

- \$4,500 toegezegde zakelijke verplichtingen,
- \$2,500 toewijzing voor onttrekking door de eigenaar,
- \$2,000 persoonlijke levensonderhoudskosten,
- \$1,500 discretionair budget,
- \$1,500 spaardoel.

De vraag verandert van:

> "Hoeveel geld is beschikbaar?"

naar:

> "Welke beslissingen kunnen veilig worden genomen?"

Dit workbook productiseert dat redeneren.

Het is geen vervanging voor boekhouding.

Het is een herbruikbaar besluitraamwerk dat financiële afwegingen zichtbaar maakt voordat fouten zich opstapelen.

---

## Veelvoorkomende financiële problemen die dit oplost

| Probleem | Zonder dit hulpmiddel | Met dit hulpmiddel |
|---|---|---|
| Privé en zakelijk geld vermengen | Werkelijke winstgevendheid wordt onschatbaar | Entiteitscheiding behoudt zowel helderheid als flexibiliteit |
| Grote banksaldi creëren vals vertrouwen | Toekomstige verplichtingen blijven onzichtbaar | Contanten worden geïnterpreteerd via verplichtingen en runway |
| Onttrekkingen door de eigenaar gebeuren inconsistent | Levensstijluitgaven destabiliseren operaties | Onttrekkingen worden intentioneel en meetbaar |
| Wekelijkse overbesteding blijft onopgemerkt | Budgetfalen verschijnt na het einde van de maand | Drempelwaarschuwingen identificeren afwijking vroeg |
| Spaardoelen concurreren met dagelijkse uitgaven | Sparen gebeurt alleen wanneer het gelegen komt | Sparen wordt expliciete toewijzingen |
| Ambigue transacties hopen zich op | Verzoening wordt pijnlijk en vertraagd | Openstaande items worden opgelost tijdens korte wekelijkse reviews |

---

## Voor wie dit is

Ontworpen voor:

- Freelancers die zowel zakelijke inkomsten als persoonlijke uitgaven beheren.
- Eigenaren van kleine bedrijven zonder eigen financiële staf.
- Consultants die via eenvoudige bankopstellingen werken.
- Ondernemers die overweldigd worden door gefragmenteerde transactieregistraties.
- Mensen die operationele helderheid zoeken in plaats van volledige boekhoudsystemen.

Niet ontworpen voor:

- Consolidaties van meerdere bedrijfsentiteiten.
- Enterprise-ERP-omgevingen.
- Wettelijke boekhouding en belastingaangifte-workflows.
- Teams die geavanceerde goedkeuringshiërarchieën vereisen.

Geen spreadsheet-expertise nodig.

Open de browserversie en begin direct met bijhouden, of download de Excel-versie voor volledige controle.

---

## Over

Ik bouw lichtgewicht trackers en besluitondersteunende hulpmiddelen voor situaties met te veel bewegende delen om betrouwbaar in het geheugen te houden.

De vraag achter elk hulpmiddel is simpel:

> Welke informatie moet op één plek bestaan om het volgende besluit met vertrouwen te ondersteunen?

Dit raamwerk past die filosofie toe op privé- en zakelijke financiën. In plaats van boekhoudsystemen te vervangen, helpt het de informatie bloot te leggen die nodig is om verantwoord te opereren tussen grote [...]

---

## Technische details

<details>
<summary>Voor technische reviewers, Excel-beoefenaars en medewerkers</summary>

---

### Workbook-architectuur

| Laag | Functie | Doel |
|---|---|---|
| Transactiecaptuur | Ruwe invoeren en imports | Slaat alle activiteit op |
| Classificatie | Entiteits- en categorie-toewijzing | Behoudt analytische integriteit |
| Validatie | Openstaande review en controles | Vermindert classificatiefouten |
| Berekeningen | Budgets en financiële kengetallen | Genereert besluitindicatoren |
| Outputs | Pulse-dashboards en samenvattingen | Ondersteunt wekelijkse beslissingen |

Gegevensstroom:

```text
Transactions
    ↓
Entity Classification
    ↓
Category Assignment
    ↓
Validation Checks
    ↓
Budget Calculations
    ↓
Pulse Indicators
    ↓
Decision Outputs
````

Validatie-afhankelijkheden:

```text
Pending Transactions
        ↓
Weekly Review
        ↓
Approved Classification
        ↓
Financial Reporting
```

---

### Drie valkuilen die zelfs ervaren operators vangen

#### Valkuil 1: banksaldo gelijk aan beschikbare contanten

Er werd een beslissing genomen.

Uitbreidingsuitgaven werden goedgekeurd.

Het besluit vertrouwde alleen op het banksaldo.

| Verkeerde aanpak             | Juiste aanpak             |
| -------------------------- | ---------------------------- |
| Totaalsaldo gebruiken          | Verplichtingen eerst aftrekken     |
| Toekomstige verplichtingen negeren  | Operationele runway berekenen |
| Contanten als onbeperkt behandelen | Toewijzen op doel          |

De gebreke:

Contanten en beschikbare contanten zijn niet identiek.

Gecorrigeerd resultaat:

Uitbreidingsbeslissingen plaatsen alleen nadat toegezegde uitgaven zijn gedekt.

<details>
<summary>Formulelogica</summary>

```excel
Available Cash
=
Bank Balance
- Committed Expenses
- Planned Draws
```

</details>

---

#### Valkuil 2: persoonlijke uitgaven verborgen in zakelijke kosten

Er werd een beslissing genomen.

Winstgevendheid werd geëvalueerd.

Persoonlijke uitgaven ingebed in zakelijke rekeningen vervormden de marges.

| Verkeerde aanpak               | Juiste aanpak    |
| ---------------------------- | ------------------- |
| Vermengde transacties           | Entiteitscheiding   |
| Geschatte onttrekkingen        | Expliciete onttrekking door eigenaar |
| Opgeblazen uitgaven of winsten | Traceerbare transfers |

De gebreke:

Vermengde entiteiten vernietigen de interpreteerbaarheid.

Gecorrigeerd resultaat:

Bedrijfsprestaties en persoonlijke consumptie worden onafhankelijk meetbaar.

<details>
<summary>Formulelogica</summary>

```excel
Entity
=
Business
OR
Personal
OR
Owner Draw
```

</details>

---

#### Valkuil 3: maandelijkse reviews detecteren problemen te laat

Er werd een beslissing genomen.

Levensstijluitgaven gaven onveranderd door.

Budgetoverschrijdingen werden achteraf ontdekt.

| Verkeerde aanpak             | Juiste aanpak             |
| -------------------------- | ---------------------------- |
| Maandelijkse ontdekking          | Wekelijkse pulse-reviews         |
| Geen waarschuwingsdrempels      | Vroege indicatoren             |
| Grote correcties vereist | Kleine aanpassingen volstaan |

De gebreke:

Feedbacklusjes kwamen te langzaam aan.

Gecorrigeerd resultaat:

Overbesteding wordt beheersbaar voordat het zich opstapelt.

<details>
<summary>Formulelogica</summary>

```excel
Discretionary Usage %
=
Actual Spend
/
Budget

Alert Trigger
=
Usage % > 85%
```

</details>

---

### Voorbeeldscenario

Een consultant besluit de week met:

| Invoer                    |  Bedrag |
| ------------------------ | ------: |
| Saldo zakelijke rekening | $12,000 |
| Aankomende SaaS-kosten      |    $800 |
| Betalingen aan aannemers      |  $2,200 |
| Geplande onttrekking door eigenaar       |  $2,500 |
| Persoonlijke levensonderhoudskosten  |  $2,000 |
| Spaardoel           |  $1,500 |

Tussenliggende interpretatie:

```text
Business Obligations
=
800 + 2,200
=
3,000

Remaining After Operations
=
12,000 − 3,000
=
9,000

Remaining After Draw
=
9,000 − 2,500
=
6,500

Remaining After Personal Allocation
=
6,500 − 2,000 − 1,500
=
3,000
```

Aanbeveling:

Het bedrijf kan geplande verplichtingen en eigenaarsvergoeding dragen terwijl de spaardoelen worden behouden.

Besluitimplicatie:

Aanvullende discretionaire uitgaven moeten onder de resterende buffer blijven tot nieuwe omzet arriveert.

Het saldo zelf beantwoordde deze vraag niet.

De gestructureerde toewijzing deed dat.

---

### Formulereferentie

<details>
<summary>Entiteitsclassificatie</summary>

Doel:

Analytische contexten scheiden.

```excel
Business
Personal
Owner Draw
```

</details>

<details>
<summary>Budgetmonitoring</summary>

Doel:

Overbesteding vroeg detecteren.

```excel
Actual / Budget
```

Drempel:

```excel
>85%
```

</details>

<details>
<summary>Contantentoewijzing</summary>

Doel:

Besluitveilige liquiditeit schatten.

```excel
Balance
− Obligations
− Planned Transfers
```

</details>

---

### Validatieregels

| Veld                   | Regel                     | Foutgedrag        |
| ----------------------- | ------------------------ | --------------------- |
| Entiteit                  | Moet worden geselecteerd         | Markeren als openstaand       |
| Categorie                | Moet bij entiteit passen        | Classificatie afwijzen |
| Bedrag                  | Numeriek en niet-nul     | Invoerwaarschuwing         |
| Transactiedatum        | Verplicht                 | Uitgesloten van rapporten |
| Onttrekking door eigenaar              | Moet entiteiten overbruggen     | Validatiewaarschuwing      |
| Budgetdrempel        | Waarschuwing boven 85%        | Overbesteding markeren   |
| Verzoeningsafwijking | Kleine afwijking getolereerd | Review vereist       |

</details>

---

## Andere hulpmiddelen in deze serie

* **Voorraadvoorspelling & nabestellingsplanning** — Bepaal het aanvultijdstip voordat voorraad uitputting optreedt.
* **CRM-besluitondersteuningstracker** — Zet lead-activiteit om in gestructureerde pipeline-beslissingen.
* **Leveranciersuitgaven-planningstoolkit** — Monitor verplichtingen tegen goedgekeurde budgetten.
* **Project-financiële-pulstracker** — Maak leveringsrisico zichtbaar via lichte operationele reviews.

GitHub-profiel: *profiellink*
Website: [Bezoek onze website](https://www.theseusworkshop.com/)

---

## Licentie

Dit project is gelicentieerd onder de **Apache License 2.0**.

U mag dit werk vrij gebruiken, wijzigen en distribueren in overeenstemming met de voorwaarden van de Apache License 2.0. Zie het bestand `LICENSE` voor details.
