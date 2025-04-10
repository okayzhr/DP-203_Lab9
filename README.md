# DP-203_Lab9
# Azure Synapse Analytics Gegevens Laden Lab 🚀

Welkom! 🎉 Dit is het repository voor de **Azure Synapse Analytics Gegevens Laden Lab**. Hier leer je hoe je gegevens in een dedicated SQL-pool binnen Azure Synapse Analytics laadt en bewerkt. Het is een hands-on oefening waarbij je gebruik maakt van verschillende krachtige Azure-tools en -technieken. Klaar om aan de slag te gaan? Let’s do this! 😎

## Wat ga je leren? 🤔

In deze oefening leer je hoe je:
- **Azure Synapse Analytics Workspace** aanmaakt en configureert.
- Gegevens laadt met de **COPY INTO** statement (super snel! 💨).
- Gegevens transformeert met **CREATE TABLE AS SELECT (CTAS)**.
- Werkt met **Slowly Changing Dimensions (SCD)** voor klantdata.
- Je gegevens optimaliseert voor betere prestaties in je data warehouse.

En dat alles binnen de magische wereld van Azure! ✨

## Wat heb je nodig? 🛠️

- Een werkend **Azure abonnement**.
- Toegang tot **Azure Synapse Analytics**.
- Een beetje ervaring met **SQL** (of de wil om te leren!).

## Oefening Stappen 🔄

### 1. Creëer een Azure Synapse Analytics Workspace 🌐
Met behulp van een PowerShell script en een ARM-sjabloon creëer je je eigen Synapse werkruimte. Dit proces is snel en eenvoudig, en je hebt alles binnen handbereik!

### 2. Gegevens Laden met COPY INTO 📥
Laad de gegevens uit .csv-bestanden in een staging-tabel in je SQL-pool. We gebruiken de krachtige **COPY INTO** statement die gegevens razendsnel importeert en eventuele fouten logt.

### 3. Gegevens Transformeren met CREATE TABLE AS (CTAS) 🏗️
Na het laden van de gegevens transformeer je ze door middel van een **CREATE TABLE AS SELECT (CTAS)**-query. Zo krijg je een geoptimaliseerde tabel klaar voor analyses en rapportages.

### 4. Werken met Slowly Changing Dimensions (SCD) 🔄
Het echte werk begint hier! Voeg nieuwe klantgegevens toe, voer updates uit (zowel Type 1 als Type 2), en leer hoe je veranderingen in je gegevens kunt beheren.

### 5. Post-load Optimalisatie 🔧
Zodra de gegevens zijn geladen, wil je de performance verbeteren door indexen opnieuw op te bouwen en statistieken bij te werken. Het draait allemaal om snelheid en efficiëntie!

## Bestanden in dit Repository 📂

- **PowerShell script** voor het provisioneren van de Synapse werkruimte.
- **SQL-scripts** die je helpen om de gegevens te laden, te transformeren en te optimaliseren.
- **Voorbeeld .csv-bestanden** met klant- en productinformatie om mee te werken.

## Klaar voor Actie? 🚀

1. **Clone het Repository!**  
   Dit is je startpunt! Clone het repository naar je lokale machine of werk direct in de cloud.

2. **Volg de stappen in de oefening** en zie hoe je Azure Synapse Analytics gebruikt om je gegevens naar de volgende niveau te brengen!

## Verwijderen van Bronnen 🗑️

Na afloop van de oefening kun je de Azure bronnen die je hebt aangemaakt eenvoudig verwijderen om kosten te besparen. Volg de stappen in de Azure portal en **delete de resource group** — alles wordt netjes opgeruimd!

## Screenshots 📸
![Schermafbeelding 2025-04-10 132259](https://github.com/user-attachments/assets/f9a054ec-dfbc-4b86-b5fe-bccf9c7b50bc)
![Schermafbeelding 2025-04-10 132441](https://github.com/user-attachments/assets/e64ecd0d-46af-40ec-8bc7-7c59d656d7ae)
![Schermafbeelding 2025-04-10 132716](https://github.com/user-attachments/assets/6110539f-f385-4287-a7ff-a4cf9a615dcc)
![Schermafbeelding 2025-04-10 133002](https://github.com/user-attachments/assets/68a4b5e4-fe06-47f8-a0c0-d9802cd6b40f)
![Schermafbeelding 2025-04-10 133242](https://github.com/user-attachments/assets/c627de7a-8fc1-4657-bb54-b5839daf5bdf)
![Schermafbeelding 2025-04-10 133545](https://github.com/user-attachments/assets/ce3ee4bf-fc07-4f14-bbd0-eae935f63259)
![Schermafbeelding 2025-04-10 134742](https://github.com/user-attachments/assets/fedeebeb-919b-4b92-8f36-9a87ffa9f118)



## Waarom zou je dit leren? 🌟

- **Snelle kennis opdoen**: Azure Synapse is een ongelooflijk krachtige tool voor data-analyse en -verwerking.
- **Echt werkervaring**: Deze oefening is ontworpen om je te laten werken met echte scenario’s die je tegenkomt als Data Engineer.
- **Azure is cool**: Het is de toekomst van cloud computing en data-analyse! 🚀

Veel plezier met het leren en succes met de oefening! 🎉 Mocht je ergens vastlopen, aarzel dan niet om een issue aan te maken. Laten we samen groeien! 💪
