---
title: "Jordressurser"
updated: "2026-06-09"
organization: "Norsk institutt for bioøkonomi"
logo: "https://register.geonorge.no/data/organizations/988983837_NIBIO_liten.jpg"
---

# Produktspesifikasjon: Jordressurser

*Kartet Jordressurser inndeler jordkartlagte arealer i fire klasser basert på jordas egenskaper, helling, hyppig forekommende fjell i dagen samt innhold av stein- og blokk. Jordkartlagte arealer er rangert på en skal fra de aller beste egenskapene til de mindre gode egenskapene for jordbruk. Datasettet er et kunnskapsgrunnlag for arealplanlegging på ulike nivåer innen forvaltningen. Klima er ikke hensyntatt i rangeringen. 
Jordkartlagte arealer er inndelt inn i fire klasser: 1 = Svært gode jordressurser, 2 = Gode jordressurser, 3 = Middels gode jordressurser og 4 = Mindre gode jordressurser. Egenskap som skal brukes til å fremstille kartlaget heter jordressursklasser.
Jordressurser er fremstilt i målestokk 1:5000 og er tilpasset bruk i målestokker fra 1:5000 til 1:20 000.*

**Nøkkelord:** Jordsmonn, Jordressurser, Jordsmonkartlegging, arealplanlegging, plan- og bygningsloven (PBL), jord, egenskaper ved jord, jordkartlagte arealer, jordbruksareal

**Emnekategorier:** Landbruk og havbruk

**Geografisk utstrekning**:

- **Vest**: 2.0
- **Øst**: 33.0
- **Sør**: 57.0
- **Nord**: 72.0

**Tidsmessig utstrekning**:

- **Tidsperiode**:
  - **Fra**: 2026-03-17
  - **Til**: 2026-03-17

## Om spesifikasjonen


> **Denne versjonen av produktspesifikasjonen:** <br>
> **Opprettet dato:** 2026-03-17<br>
> **Endret dato:** 2026-03-17<br>
> **Språk:** nor<br>
> **Kontaktinformasjon:** Norsk institutt for bioøkonomi, [siri.svendgard-stokke@nibio.no](mailto:siri.svendgard-stokke@nibio.no)

## Om produktet Jordressurser


> **Romlig representasjonstype:** Vektor<br>
> **Unik identifikator:** 3690c283-a1f2-4e95-8cd4-2d6115eb28f7<br>
> **Kontaktinformasjon:** Norsk institutt for bioøkonomi, [siri.svendgard-stokke@nibio.no](mailto:siri.svendgard-stokke@nibio.no)
>
> **Romlig oppløsning:**
>
> **Ekvivalent målestokk**: 5000
>
> **Begrensninger:**
>
> **Juridiske begrensninger**:
>
> - **Tilgangsbegrensninger**: Åpne data
> - **Bruksbegrensninger**: Lisens
> - **Lisens**: Norsk lisens for offentlige data (NLOD)
> - **Lisenslenke**: <http://data.norge.no/nlod/no/1.0>
>
> **Sikkerhetsbegrensninger**:
>
> - **Klassifisering**: Ugradert

### Formål

I jordkartlegginga blir det lagt vekt på ni spesifikke egenskaper ved jordsmonnet, slik som tekstur, lagdeling og drenering. Dette er relativt stabile egenskaper ved jorda som lar seg bestemme ute i felt, in situ. En jordtype er en spesifikk, unik kombinasjon av disse ni egenskapene. Hver jordtype har et navn.

I noen kartfigurer kan det være avvikende egenskaper enn dem som framkommer fra jordkartleggingen. I tillegg til jordtypene innenfor hver kartfigur, registreres også andre relevante egenskaper, slik som eventuell høy frekvens av fjellblotninger og innhold av stein og blokk i øverste 50 cm. Dominerende hellingsklasse i hver kartfigur tilordnes i etterkant av feltarbeidet.

Klassene for innhold av stein og blokk påvirker klassetildelingen i Jordressurser. 

Helling er tilordnet som heltall, i prosent, og det er kartfigurenes gjennomsnittlige helling som brukes i dette kartet. 
Det er også ander tilleggsegenskaper om kartfiguren som påvirker klassetildelingen i Jordressurser.

### Bruksområde

Datasettet Jordressurser skal bidra til å løse kommunens oppgaver etter plan- og bygningsloven samt annen arealplanlegging som berører jordkartlagte arealer. Kartfigurer fra det nasjonale jordkartleggingsprogrammet utgjør enhetene i kartet.

## Omfang

### Hele datasettet

**Nivå**: dataset

**Nivåbeskrivelse**: Gjelder hele datasettet. Hvis omfang ikke er oppgitt under en overskrift, gjelder teksten for hele datasettet og alle leveranser

### Filleveranser

**Nivå**: dataset

**Nivåbeskrivelse**: Datamodellen dokumenterer filleveranser i form av GML-filer, SOSI-filer, Filgeodatabaser.

## Datainnhold og struktur



### Datamodell - Filleveranser



<a href="filleveranser/filleveranser_feature_catalogue.png" title="Klikk for stor visning"><img src="filleveranser/filleveranser_feature_catalogue.png" alt="Datamodell Filleveranser" style="max-width: 100%; height: auto;" /></a>



➡️ [Se full datamodell for omfang "Filleveranser" (diagram per pakke og objektkatalog)](filleveranser/objektkatalog.html)

## Datakvalitet

**Nivå**: dataset

- **Kvalitetsmål**: Prosentvis dekning i forhold til datasettets utstrekning
  **Målebeskrivelse**: Datasettets faktiske kartlagte areal i forhold til datasettets spesifiserte utstrekning
  **Resultat**: 100

- **Kvalitetsmål**: Coverage
  **Resultat**: Prosentvis dekning i forhold til datasettets utstrekning: 100%

## Datafangst og produksjon

**Datainnsamling og prosessering**:

- **Prosesstrinn**:
  - **Beskrivelse**:
    NIBIO Rapport 37/2025, «Det nasjonale programmet for jordkartlegging» (https://hdl.handle.net/11250/3185641) beskriver hvordan stedfesting og dokumentasjon av jordsmonnets egenskaper utføres (forarbeid, metodikk i felt og etterarbeid). Rapporten inneholder også informasjon om dataforvaltning og formidling av data fra programmet. 
    Kartfigurenes helling hentes fra den nasjonale høydemodellen (hoydedata.no) og to av terrengmodellene derfra benyttes: en med 1 m oppløsning og en med 10 m oppløsning. Begge modellene endres over tid når nye og oppdaterte høydedataprosjekt er tilgjengelig. Det er kartfigurens gjennomsnittlige helling som benyttes i Jordressurser.
    Informasjon om hvordan egenskaper ved jord, helling, hyppig forekommende fjell i dagen samt innhold av stein- og blokk påvirker klassetildeling i Jordressurser er publisert på produktsiden.

## Vedlikehold

**Vedlikeholdsfrekvens**: Ikke planlagt

**Status**: Fullført

## Leveranse

- **Leveranse**:

  - **Leveranseformat**:
    - **Formatnavn**: GeoPackage

    - **Formatnavn**: GML

## Metadata

**Metadatastandard**: ISO19115

**Metadatastandardversjon**: 2003

**Metadatadato**: 2026-05-19

**språk**: nor

**Kontakt**:

- **Organisasjon**: Norsk institutt for bioøkonomi
- **Kontaktperson**: Christina Sogge
- **Logo**: <https://register.geonorge.no/data/organizations/988983837_NIBIO_liten.jpg>
- **Epost**: gisdrift@nibio.no
- **rolle**: pointOfContact

**Metadataidentifikator**:

- **Utsteder**: Geonorge
- **kode**: 3690c283-a1f2-4e95-8cd4-2d6115eb28f7
- **koderom**: <https://kartkatalog.geonorge.no/metadata/>
- **Metadatalenke**: <https://kartkatalog.geonorge.no/metadata/3690c283-a1f2-4e95-8cd4-2d6115eb28f7>

## Tilleggsinformasjon

Produktspesifikasjonen Jordressurser inneholder en beskrivelse av temakartet Jordressurser som er utviklet for arealplanlegging. Temakartet er blant annet tilgjengelige under fagområdet Jordsmonn og fagområde Arealinformasjon i NIBIOs karttjeneste Kilden. Andre temakart som har opphav i jorddata fra jordkartleggingsprogrammet, er beskrevet i produktspesifikasjonene Jordsmonn, Erosjonsrisiko og Dyrkingspotensial.
