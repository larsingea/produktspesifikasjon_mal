---
title: "Dyrkbar jord"
updated: "2025-12-03"
organization: "Norsk institutt for bioøkonomi"
logo: "https://register.geonorge.no/data/organizations/988983837_NIBIO_liten.jpg"
---

# Produktspesifikasjon: Dyrkbar jord

## Innledning, historikk og endringslogg


### Innledning


### Historikk


### Endringslogg


### Normative referanser


## Definisjoner og forkortelser


### Definisjoner


### Forkortelser


## Generelt om spesifikasjonen


### Unik identifisering

8252baea-5bad-428b-8f18-fe236fa4ced6

#### Fullstendig navn

Dyrkbar jord

#### Versjon

2025-09-12

### Referansedato

2025-09-12

### Ansvarlig organisasjon

Norsk institutt for bioøkonomi

### Språk

nor

### Hovedtema

Arealtype, Arealressurs, Jordbruk, Dyrkbar, Fulldyrka, Overflatedyrka, Innmarksbeite, Landbruk, Jord, Jordvern, Norge fastland, Arealdekke, geodataloven, Det offentlige kartgrunnlaget, Norge digitalt, modellbaserteVegprosjekter, fellesDatakatalog, Landskap

### Temakategori

Landbruk og havbruk

### Sammendrag

Dyrkbar jord er i år (2025) revidert gjennom bruk av flere datakilder og nye metoder, og det nye datsettet ble gjort tilgjengelig via Geonorge den 16. september. Det er nå lagt inn flere nye tematiske egenskaper i datasettet, og det er gjort en teknisk rydding som innebærer nye objekter og ny geometri. Gå til produktsiden for å lese mer om det reviderte datasettet.

Datasettet Dyrkbar jord er et landsdekkende data-sett som viser arealer som per i dag ikke er fulldyrka jord, men som ut fra agronomiske perspektiv kan dyrkes opp, og som holder kravene til klima og jordkvalitet for plantedyrking. Dyrkbar jord kan være registrert på arealtypene Overflatedyrka jord, Innmarksbeite, Skog, Åpen fastmark og Myr, slik disse er klassifisert i AR5.

Datasettet er et automatisk avledet produkt som produseres årlig.

### Formål

Dyrkbar jord viser areal som har lovmessig vern i Jordlova. Dyrkbar jord er et Geovekst-produkt og en del av det offentlige kart- grunnlaget (DOK). Datasettet bør brukes ved arealplanlegging, behandling av konsesjonssaker. Det kan også i ulike andre analyser. 

Areal som er registrert som dyrkbar jord kan være underlagt restriksjoner mot nydyrking i samsvar med ulike lover og forskrifter. For å finne hvilke areal som er reelt tilgjengelig for oppdyrking, er det fra sommer 2025 mulig å filtrere på de nye egenskapene som er lagt inn i datasettet, og eventuelt holde det opp mot andre relevante kilder og datasett.

## Spesifikasjonsomfang

**Nivå**: dataset

**Utstrekning**:

- **romlig**: - **romlig omfang**: National
- **tidsmessig**: - **intervall**: - 2025-09-12, 2025-09-12

**Juridiske begrensninger**:

- **Bruksbegrensninger**: Tilgang for Geovekst- og Norge digitalt-parter. Nedlasting krever lisens og GeoiD.
- **Tilgangsbegrensninger**: Norge digitalt begrenset
- **Bruksbegrensninger**: Lisens
- **Lisens**: Norge digitalt-lisens
- **Lisenslenke**: <https://www.geonorge.no/Geodataarbeid/geografisk-infrastruktur/Norge-digitalt/Avtaler-og-maler/Norge-digitalt-lisens/>
- **Sikkerhetsbegrensninger**: Ugradert

## Innhold og struktur

**Bruk**: Datasettet Dyrkbar jord skal brukes ved arealplanlegging og behandling av konsesjonssaker. Dyrkbar jord har samme lovmessig vern som dyrka jord i jordlova.  I tillegg til kan datasettet Dyrkbar jord brukes blant annet ved regionale analyser av potensial for nydyrking og arrondering av fulldyrka jord.

### Datamodell

![Dyrkbar-jord xmi feature catalogue](dyrkbar-jord_xmi_feature_catalogue.png)

#### DyrkbarJord_Fellesegenskaper (abstrakt)

abstrakt objekttype som bærer sentrale egenskaper som er anbefalt for bruk i produktspesifikasjoner.<br />Merknad: Disse egenskapene skal derfor ikke modelleres inn i fagområdemodeller.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjon.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>informasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Informasjon om brukte datakilder</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kopidata</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av at objektet er hentet fra et kopidatasett og ikke fra originaldatasettet<br />Merknad: Inneholder informasjon om når kopidatasettet ble kopiert fra originaldatasettet og hvem som er originaldataansvarlig</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kopidata</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kopidata.kopidato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når objektet ble kopiert fra originaldatasettet<br /><br />Merknad:<br />Er en del av egenskapen Kopidata. Brukes i de tilfeller hvor en kopidatabase brukes til distribusjon.<br />Å kopiere et datasett til en kopidatabase skal ikke føre til at Oppdateringsdato blir endret.<br />Eventuell redigering av data i et kopidatasett medfører ny Oppdateringsdato, Datafangstdato og/eller Verifiseringsdato.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kopidata.områdeId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av område som dataene dekker<br /><br />Merknad: Kan angis med kommunenummer eller fylkesnummer. Disse bør spesifiseres nærmere.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kopidata.originalDatavert</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>ansvarlig etat for forvaltning av data</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

#### ArealressursFlate

et sammenhengende areal som er tilordnet de samme egenskapsverdiene i henhold til et arealressursklassifikasjonssystem<br />-- Definition --<br />a continuous area which has been assigned the same attribute values in accordance with an area resource classification system

Geometri:
- type: GM_Surface

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geometry</strong></td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Surface</td>
    </tr>
    <tr>
      <th scope="row">OGC-rolle:</th>
      <td>primary-geometry</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dyrkbarJord</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Dyrkbar jord er areal som per i dag ikke er fulldyrka, men som ved oppdyrking kan settes i en slik stand at de holder kravene til fulldyrka jord, ut fra agronomiske perspektiv kan dyrkes opp til fylldyrka jord, og som holder kravene til klima og jordkvalitet for plantedyrking.  Informasjon om dyrkbar jord på arealressurser av typen overflatedyrka jord, innmarksbeite, skogareal, åpen fastmark og myr.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DyrkbarJord</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Dyrkbar Jord – Areal som egner seg for oppdyrking til fulldyrka jord.</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fulldyrka2008</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Arealer som var fulldyrka jord i DMK-basen i 2008, men ikke er fulldyrka lenger</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Fulldyrka2008</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Fulldyrka 2008 – Arealtilstand er endret etter 2008 som følge av ajourhold av AR5<br />- Ikke fulldyrka – Arealtilstand er ikke endret etter 2008 ved ajourhold av AR5.</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>myrTorv</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Dyrkbar jord er delt i dyrkbar myr, dyrkbar torvmark og dyrkbar mineraljord. Informasjon om grunnforhold er hentet fra AR5</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MyrTorv</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Mineraljord dyrkbar mineraljord – Dyrkbar jord på areal som hverken er registrert med grunnforhold organiske jordlag eller myr i AR5<br />- Myr dyrkbar myr – Dyrkbar jord på areal som er registrert som myr i AR5<br />- Torvmark dyrkbar torvmark – Dyrkbar jord på areal med grunnforhold organiske jordlag i AR5 men som ikke er registrert som myr i AR5</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>planeringsjord</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Areal ansett som planeringsjord og som ligger i kartlagte eller modellerte ravineområder Areal som historisk er kartlagt som dyrkbar jord, forutsatt bakkeplanering</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Planeringsjord</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ikke planeringsjord – Areal som ikke er ansett som planeringsjord<br />- Kartlagt – Dyrkbar jord på areal som historisk er kartlagt som planeringsjord og som ligger i kartlagte ravineområder<br />- Modellert – Dyrkbar jord på areal som historisk er kartlagt som planeringsjord og som ligger i modellerte ravineområder</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>verneform</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Informasjon om arealet ligger i en nasjonalpark eller et naturreservat</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Verneform</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ikke relevant – Det er ikke kartlagt Nasjonalpark eller Naturreservat på lokaliteten.<br />- Verneform nasjonalpark – Dyrkbar jord i nasjonalpark<br />- Verneform naturreservat – Dyrkbar jord i naturreservat</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>årsversjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Årstall for årsversjon av Dyrkbar jord datasettet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
DyrkbarJord_Fellesegenskaper

**Assosiasjoner**
ArealressursGrense – rolle: avgrensesAvArealressursGrense – kardinalitet: 0..*

#### ArealressursGrense

avgrensing for en eller to arealressursflater<br />-- Definition --<br />delimitation for one or two area resource surfaces

Geometri:
- type: GM_Curve

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geometry</strong></td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Curve</td>
    </tr>
    <tr>
      <th scope="row">OGC-rolle:</th>
      <td>primary-geometry</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
ArealressursFlate





## Referansesystem

**Romlige referansesystemer**:

- **kode**: EPSG:25832
  **navn**: EUREF89 UTM sone 32, 2d

- **kode**: EPSG:25833
  **navn**: EUREF89 UTM sone 33, 2d

- **kode**: EPSG:25835
  **navn**: EUREF89 UTM sone 35, 2d

- **kode**: EPSG:4258
  **navn**: EUREF 89 Geografisk (ETRS 89) 2d

- **kode**: EPSG:25832
  **navn**: EUREF89 UTM sone 32, 2d

**Romlig representasjonstype**: Vektor

## Kvalitet

**Nivå**: dataset

- **navn**: SOSI-produktspesifikasjon: Dyrkbar jord
  **Måleparameter**: Dataene er i henhold til produktspesifikasjonen

- **navn**: Sosi applikasjonsskjema
  **Måleparameter**: SOSI-filer er i henhold til applikasjonsskjema

- **navn**: Sosi applikasjonsskjema
  **Måleparameter**: GML-filer er i henhold til applikasjonsskjema

- **navn**: Prosentvis dekning i forhold til datasettets utstrekning
  **Måleparameter**: Datasettets faktiske kartlagte areal i forhold til datasettets spesifiserte utstrekning
  **Resultat**: 6,9

- **navn**: Prosentvis oppfyllelse av FAIR-prinsipper
  **Måleparameter**: Angir fullstendighet i forhold til krav fra FAIR-prinsippene (The FAIR Guiding Principles for scientific data management and stewardship)
  **Resultat**: 100

- **navn**: FAIR
  **Resultat**: Prosentvis oppfyllelse av FAIR-prinsipper: 100%

- **navn**: Coverage
  **Resultat**: Prosentvis dekning i forhold til datasettets utstrekning: 6,9%

**Beskrivelse**:
Dyrkbar jord produseres årlig med utgangspunkt i dyrkbar jord i det historiske datasettet DMK fra 2008.  Datasettet er et avledet produkt som sammenstilles basert på utvalgsregler og geografisk fletting (overlay) av flere datasett. 
Fra FKB-AR5 brukes arealtype og grunnforhold for å legge til eller fjerne areal, samt tilpasse figur-avgrensingene.  SSB-arealbruk brukes for fjerne nedbygd areal. Fra Naturvernområder (Mdir) hentes informasjon om nasjonalparker og naturreservat. I tillegg brukes informasjon fra ravinekart fra Statsforvalteren i Østfold, Buskerud, Oslo og Akershus samt modellert ravinekart fra NIBIO for å definere dyrkbar jord som ligger i raviner som planeringsjord.

## Datafangst



## Datavedlikehold

**Vedlikeholdsfrekvens**: Årlig

**Vedlikeholdsnotat**: Datasettet Dyrkbar jord skal brukes ved arealplanlegging og behandling av konsesjonssaker. Dyrkbar jord har samme lovmessig vern som dyrka jord i jordlova.  I tillegg til kan datasettet Dyrkbar jord brukes blant annet ved regionale analyser av potensial for nydyrking og arrondering av fulldyrka jord.

**Status**: Kontinuerlig oppdatert

## Presentasjon

**Tegnforklaring**:
<https://register.geonorge.no/register/versjoner/tegneregler/norsk-institutt-for-biookonomi/dyrkbar-jord>

## Leveranse

**Distribusjoner**:

- **format**: - **format**: GEONORGE:DOWNLOAD
  **tilgang**:

  - **lenke**: <https://nedlasting.geonorge.no/api/capabilities/>
  - **protokoll**: GEONORGE:DOWNLOAD

- **tittel**: Geonorge nedlastning
  **format**: - **format**: Geonorge nedlastning
  **tilgang**:

  - **lenke**: <https://nedlasting.geonorge.no/api/capabilities/>
  - **protokoll**: GEONORGE:DOWNLOAD

- **tittel**: Dyrkbar jord - WMS
  **format**: - **format**: png, jpg, gif
  **tilgang**:

  - **lenke**: <https://wms.nibio.no/cgi-bin/dyrkbarjord_2?service=wms&request=getcapabilities>
  - **protokoll**: WMS-tjeneste
  - **Lisens**: Tilgangsbegrensede data
  **Notater**: Tjeneste

## Metadata

**Standard**: ISO19115

**Standardversjon**: 2003

**Metadatadato**: 2025-12-03

**språk**: nor

**Kontaktpunkt**:

- **organisasjon**: Norsk institutt for bioøkonomi
- **epost**: gisdrift@nibio.no
- **rolle**: resourceProvider

**Identifikatorer**:

- **Utsteder**: geonorge
  **kode**: 8252baea-5bad-428b-8f18-fe236fa4ced6

**Metadatalenke**:
<https://www.geonorge.no/geonetwork/srv/nor/csw?service=CSW&request=GetRecordById&version=2.0.2&outputSchema=http://www.isotc211.org/2005/gmd&elementSetName=full&id=8252baea-5bad-428b-8f18-fe236fa4ced6>
