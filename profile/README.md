# ePrijzen: Dynamische Energieprijs Inzichten

Welkom bij de ePrijzen GitHub-teamrepository, het centrale punt voor alle componenten van de ePrijzen-service. Dit project, gestart in 2021, groeide uit van een hobbyproject naar een uitgebreide service die duizenden gebruikers van energieprijsinformatie voorziet.

## Overzicht

ePrijzen is ontwikkeld om jou te helpen dynamische energieprijzen te monitoren en te benutten. De service biedt verschillende componenten die samenwerken om real-time energieprijsinformatie te verzamelen, verwerken en delen via meerdere platformen. Hieronder volgt een overzicht van de beschikbare repositories:

## Contact

Alhoewel ik dus gestopt ben met dit project mag je altijd contact met me opnemen. Geef me wel ff de tijd om te reageren, ik heb het druk ;-)

- **Theo van der Sluijs**: 
  - E-mail: [theo@vandersluijs.nl](mailto:theo@vandersluijs.nl)
  - Telegram: [tvdsluijs](https://t.me/tvdsluijs)

### Andere gegevens

Ben je opzoek naar andere gegevens van me?
- Website: [itheo.tech](https://itheo.tech)
- Resume: [theovandersluijs.nl](https://theovandersluijs.nl)
- Linkedin: [Linkedin](https://www.linkedin.com/in/tvandersluijs/)

### Repositories

1. **Energie-API**
   - **Beschrijving**: De Energie-API is de kern van het ePrijzen-project. Hier kun je alle energieprijzen ophalen via een API. Dit is tevens de hoofdconnectie met de SQLite-database.
   - **Functionaliteiten**:
     - Real-time prijsinformatie ophalen.
     - Verbinding maken met de SQLite-database.

2. **Energie-Verwerker**
   - **Beschrijving**: Deze module haalt de energieprijzen op en stuurt ze door naar de API.
   - **Functionaliteiten**:
     - Automatiseren van prijsverzameling.
     - Data-integratie met de Energie-API.

3. **Energie-Telegram**
   - **Beschrijving**: Verzorgt de verbinding met Telegram om je op de hoogte te stellen van energieprijzen.
   - **Functionaliteiten**:
     - Sturen van notificaties bij specifieke prijsdrempels.

4. **Energie-Social**
   - **Beschrijving**: Interface voor het delen van energieprijsinformatie op verschillende sociale platforms zoals X, Facebook, Instagram en Mastodon.
   - **Functionaliteiten**:
     - Automatische updates naar sociale media.

5. **Energie-Graphs**
   - **Beschrijving**: Deze module creëert grafieken en overzichten van energieprijzen.
   - **Functionaliteiten**:
     - Visualisatie van prijsdata.
     - Genereren van rapporten en overzichten.

6. **Energie-Database**
   - **Beschrijving**: Deze repo bevat een zo goed als lege database.
       

## Infrastructuur en Kostenbesparing

De ePrijzen-service draaide oorspronkelijk op een server van **Digital Ocean** via **Docker-instanties**, wat ongeveer **$30 per maand** kostte. Om kosten te besparen, besloot ik de service naar een **Raspberry Pi 5** te migreren, wat een grote verandering met zich meebracht.

- **Nieuwe Opzet**:
  - De migratie vereiste dat ik de infrastructuur herschreef naar een **Pixi Package-based omgeving**.
  - Deze opzet bleek minder stabiel te zijn dan de originele Docker-omgeving, wat resulteerde in meerdere uitdagingen.

- **Uitdagingen**:
  - Het systeem werd minder betrouwbaar, met frequente crashes van bepaalde services.
  - Het oplossen van deze problemen kostte vele uren debugging om te achterhalen waarom de services uitvielen en om een stabiele werking te garanderen.

**Belangrijk:** Buiten de ontvangen donaties heb ik altijd zelf betaald voor de servers van Digital Ocean, en alle uren die ik in dit project heb gestoken waren vrijwillig. Het was een passieproject waarin ik veel tijd en energie heb gestoken om de gemeenschap te ondersteunen.

## Stopzetting van de Service

**Belangrijk:** De huidige ePrijzen-service stopt op **1 september 2024**. Vanaf deze datum zullen de bestaande diensten niet langer actief ondersteund of onderhouden worden. Ik moedig je aan om de repositories te gebruiken om je eigen oplossingen te creëren en voort te bouwen op de bestaande technologie.

## Forken en Hergebruik

Wanneer je mijn repositories wilt forken, hergebruiken, of op welke manier dan ook klonen, is het essentieel dat je altijd verwijst naar de originele repository en de originele ontwikkelaar vermeldt:

- **Repository**: [ePrijzen GitHub](https://github.com/ePrijzen/)
- **Ontwikkelaar**: Theo van der Sluijs
  - Github: [tvdsluijs](https://github.com/tvdsluijs)


## Licentie: MIT

De ePrijzen-codebase is gelicentieerd onder de **MIT-licentie**. Dit betekent dat je de vrijheid hebt om de code te gebruiken, te kopiëren, te wijzigen, samen te voegen, te publiceren, te distribueren, sublicentiëren en/of te verkopen, onder de volgende voorwaarden:

- Je moet de originele copyright notice en de toestemmingstekst in alle kopieën of substantieel delen van de software opnemen.
- De software wordt geleverd "zoals het is", zonder enige vorm van garantie, expliciet of impliciet, inclusief maar niet beperkt tot de garanties van verkoopbaarheid, geschiktheid voor een bepaald doel en niet-inbreuk.

Meer informatie over de MIT-licentie is te vinden in het bestand `LICENSE` in deze repository.

## Waarom Open Source?

Wat begon als een klein persoonlijk project, evolueerde snel tot een uitgebreide service met een groeiende gebruikersbasis. Na jarenlang met veel passie aan ePrijzen te hebben gewerkt, heb ik besloten om het project open source te maken. Hiermee wil ik jou de kans geven om je eigen omgeving op te bouwen en te profiteren van de kennis en tools die ik heb ontwikkeld.

## Mijn Reis

In 2021, toen de energieprijzen begonnen te stijgen, werd ik nieuwsgierig naar manieren om efficiënter met energie om te gaan. Samen met een vriend ontdekte ik de voordelen van dynamische energieprijzen, wat de inspiratie vormde voor ePrijzen. Het project begon als een script dat prijsinformatie verzamelde en via Telegram naar vrienden stuurde. Naarmate de gebruikersaantallen groeiden, breidde ik de service uit naar verschillende platformen en lanceerde ik een betaalde versie van de API.

Gedurende deze reis heb ik veel geleerd en met trots gezien hoe ePrijzen een gemeenschap heeft gevormd. De jaarlijkse donatierondes waren een teken van de steun van de gemeenschap en de waarde die gebruikers in de service zagen.

Ik ben ook betrokken geweest bij duurzaamheid in bredere zin, zoals het opzetten van een duurzaamheidswerkgroep in de gemeente Borsele.

## Dankwoord

Ik wil iedereen bedanken die op welke manier dan ook heeft bijgedragen aan het succes van ePrijzen. Van gebruikersfeedback tot support in de community, jullie hulp is van onschatbare waarde geweest.

## Toekomst van ePrijzen

Hoewel ik nu stop met de actieve ontwikkeling van ePrijzen, blijft het project beschikbaar voor iedereen die het verder wil ontwikkelen. Ik ben ervan overtuigd dat het open-source model nieuwe mogelijkheden zal openen en dat de gemeenschap zal blijven groeien.
