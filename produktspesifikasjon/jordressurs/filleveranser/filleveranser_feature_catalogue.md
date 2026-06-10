#### JordressursGrense

avgrensing for en eller to arealressursflater<br />-- Definition --<br />delimitation for one or two area resource surfaces

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>grense</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger overgang mellom ulike fenomener<br />-- Definition --<br />course following the transition between different real world phenomena</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Curve</td>
    </tr>
  </tbody>
</table>

#### Jordressurser_Fellesgenskaper

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
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
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
      <td>lokal identifikator av et objekt<br /><br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
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
      <td>navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br /><br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
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
      <td><strong>identifikasjon.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td>angivelse av at objektet er hentet fra en kopi av originaldata<br />Merknad:<br />Kan benyttes dersom man gjør et uttak av en database som ikke inneholder originaldataene.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>kvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Posisjonskvalitet</td>
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
      <td><strong>kvalitet.målemetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Målemetode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/SOSI/generelleKonsepter/generelleTyper/5.1/Målemetode">http://skjema.geonorge.no/SOSI/generelleKonsepter/generelleTyper/5.1/Målemetode</a></td>
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
      <td><strong>verifiseringsdato</strong></td>
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

#### Jordressurser

Definisjon: geografisk område med tilnærmet enhetlige egenskaper i de kriteriene som benyttes i rangering av jordkartlagte arealer for datasettet<br />— Definition —<br />Geographic area with approximately uniform characteristics in the dataset

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning<br />— Definition —<br />Area over which an object extends</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Surface</td>
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
      <td><strong>jordressursklasse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Viser arealets klassetilhørighet i Jordressurser<br />— Definition —<br />Shows the Soil Resource Class for an area</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Jordressursklasser</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Svært gode jordressuser – Jord og areal som er lettdrevet. I tilfelle to jordtyper er registrert, kan den mindre dominerende jordtypen ha andre egenskaper.<br />- Gode jordressurser – Jord og areal som er nokså lettdrevet men krever noe større innsats enn jord og areal i klasse 1. Hvis to jordtyper er registrert kan den mindre dominerende jordtypen ha andre egenskaper. Avhengig av jordegenskaper klassifiseres stein og blokkholdige arealer arealer med helling 25 prosent til under 33 prosent og arealer med tegn til forstyrrelser utover vanlig jordbearbeiding eller grøfting i denne klassen.<br />- Middels gode jordressurser – jord og areal som setter større krav til innsats enn jord og areal i klasse 2 og 3. I tilfelle to jordtyper er registrert kan den mindre dominerende jordtypen ha andre egenskaper. Avhengig av jordegenskaper klassifiseres stein og blokkholdige arealer samt hyppig forekommende fjell i dagen og arealer med helling 25 prosent til under 33 prosent i denne klassen.<br />- Mindre gode jordressurser – Jord og areal som har ugunstige egenskaper som det er vanskelig å få gjort noe med.
I tilfelle jordtypene er registrert kan den mindre dominerende jordtypen ha andre egenskaper.
Avhengig av jordeegenskaper klassifiseres stein og blokkholdige eller stein og blokkholdige arealer hyppig forekommende fjell i dagen og arealer med helling 33 prosent i denne klassen.</td>
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
      <td><strong>hellingGjsnitt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Viser gjennomsnittlige helling på arealet.<br />-- Definition - -<br />Average inclination class of the soil figure</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>HellingGjsnitt</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- 0 - 25 % – Mindre enn 25 % gjennomsnittlig helling. Har ikke betydning for maskinvalg eller jordarbeiding
-- Definition --
Less than25 % inclination. Not significant for choice of machinery or tillage.<br />- ≥ 25 - 33 % – Mellom 25 og opp til 33 % gjennomsnittlig helling, Maskinvalg og jordarbeiding begrenses noe
-- Definition --
Between 25% and less than 33 %  average inclination. Choice of machinery and tillage is limited.<br />- ≥ 33 % – 33 % eller mer gjennomsnittlig helling. Maskinvalg og jordarbeiding begrenses sterkt.
-- Definition --
33 % or more  average inclination. Choice of machinery and tillage is strongly limited.</td>
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
      <td><strong>steinblokk</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Viser stein- og blokkinnhold (0–50 cm) på arealet på kartleggingstidspunktet — — Definition —<br />Shows the amount of stones and boulders for the soil figure in the upper 50 cm</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>SteinBlokk</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ikke registrert – Ikke registrert stein og blokk.<br />- Ingen eller noe stein og blokk – Lite eller ingen stein og blokk.<br />- Stein og blokkholdig – Inneholder stein og blokk.<br />- Stein og blokkrik – Inneholder mye stein og blokk.</td>
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
      <td><strong>årsakTilNedklassifisering</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Viser årsak til at kartfiguren er nedklassifisert<br />— Definition —<br />Reason for down-classification of Soil Resource Class</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>ÅrsakTilNedklassifisering</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Jordegenskaper – Jorda har egenskaper som gjør at arealet krever større innsats i drift<br />- Helling – Arealet har en gjennomsnittlig helling på enten 25 til under 33 prosent eller 33 prosent og over. Dette gir driftsutfordringer<br />- Jordegenskaper og helling – Jorda har egenskaper som gjør at arealet krever større innsats i drift og arealet har en gjennomsnittlig helling på 25 prosent og over til under 33 prosent<br />- Hyppig forekommende fjell i dagen – Arealet har mer enn 4 fjellblotninger / fjell i dagen per 10 daa og dette gir driftsutfordringer<br />- Innhold av stein og blokk – Arealet er enten stein- og blokkholdig eller stein- og blokkrikt og dette gir driftsutfordringer<br />- Deler av arealet har organisk jord, har liten evne til å bli kvitt overflødig vann, er bakkeplanert eller forstyrret av graving eller påfylling – Deler av arealet har egenskaper utover dem som er registrert som egenskaper ved jordtypene og disse gir driftsutfordringer<br />- Ingen nedklassifisering – Arealet har ingen årsak til nedklassifisering</td>
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
      <td><strong>tilleggsinformasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Viser tilleggsinformasjon om andre egenskaper ved arealet<br />— Definition —<br />Supplementary information</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Tilleggsinformasjon</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Deler av arealet er bakkeplanert<br />- Deler av arealet er forstyrret av graving eller fyllmateriale – Deler av arealet er forstyrret av graving eller fyllmateriale.<br />- Ingen – Ingen forstyrrelser.<br />- Deler av arealet er organisk jord<br />- Deler av arealet er preget av vannmetning – Deler av arealet er preget av vannmetning.<br />- Deler av arealet er mineraljord<br />- Hyppig forekommende fjell i dagen</td>
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
      <td><strong>kartleggingsår</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Viser hvilket år kartfiguren ble jordkartlagt<br />— Definition —<br />Mapping year</td>
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
      <td><strong>kartleggingsmetodikk</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Viser hvilken kartleggingsmetodikk som ble brukt da kartfiguren ble jordkartlagt<br />— Definition —<br />Original mapping method</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kartleggingsmetodikk</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Detaljert kartlegging – Feltbasert kartlegging med avgrensning av jordtyper direkte inn på digitale flybilder i felt, basert på en kombinasjon av borstikk ned til en meters dybde, flybildetolking og GPS. I tillegg deles arealene inn på bakgrunn av terrengegenskaper som helling og stein- og blokkinnhold.<br />- Forenklet kartlegging – Feltbasert kartlegging med en grovere inndeling av jorda enn detaljert kartlegging, der en i tillegg slår sammen enkelte hellingsklasser og ser bort i fra andre egenskaper ved terrenget<br />- Harmonisert kartlegging – Feltbasert kartlegging som kombinerer det beste fra de tidligere metodikkene (detaljert og forenklet).</td>
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
      <td><strong>opprinneligLokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Opprinnelig id i databasen<br />— Definition —<br />Original ID in the soil database</td>
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
Jordressurser_Fellesgenskaper

**Assosiasjoner**
JordressursGrense – rolle: avgrensesAvJordressursgrense – kardinalitet: 0..*

### Kodelister

#### «CodeList» Målemetode

**Definisjon:** metode som ligger til grunn for registrering av posisjon
-- Definition - -
method on which registration of position is based

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/SOSI/generelleKonsepter/generelleTyper/5.1/Målemetode">http://skjema.geonorge.no/SOSI/generelleKonsepter/generelleTyper/5.1/Målemetode</a></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Jordressursklasser

**Definisjon:** Viser arealets klassetilhørighet i Jordressurser
— Definition —
Shows the Soil Resource Class for an area

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Svært gode jordressuser</td>
      <td>Jord og areal som er lettdrevet. I tilfelle to jordtyper er registrert, kan den mindre dominerende jordtypen ha andre egenskaper.</td>
      <td></td>
    </tr>
    <tr>
      <td>Gode jordressurser</td>
      <td>Jord og areal som er nokså lettdrevet men krever noe større innsats enn jord og areal i klasse 1. Hvis to jordtyper er registrert kan den mindre dominerende jordtypen ha andre egenskaper. Avhengig av jordegenskaper klassifiseres stein og blokkholdige arealer arealer med helling 25 prosent til under 33 prosent og arealer med tegn til forstyrrelser utover vanlig jordbearbeiding eller grøfting i denne klassen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Middels gode jordressurser</td>
      <td>jord og areal som setter større krav til innsats enn jord og areal i klasse 2 og 3. I tilfelle to jordtyper er registrert kan den mindre dominerende jordtypen ha andre egenskaper. Avhengig av jordegenskaper klassifiseres stein og blokkholdige arealer samt hyppig forekommende fjell i dagen og arealer med helling 25 prosent til under 33 prosent i denne klassen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Mindre gode jordressurser</td>
      <td>Jord og areal som har ugunstige egenskaper som det er vanskelig å få gjort noe med.
I tilfelle jordtypene er registrert kan den mindre dominerende jordtypen ha andre egenskaper.
Avhengig av jordeegenskaper klassifiseres stein og blokkholdige eller stein og blokkholdige arealer hyppig forekommende fjell i dagen og arealer med helling 33 prosent i denne klassen.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» HellingGjsnitt

**Definisjon:** Viser gjennomsnittlige helling på arealet.
-- Definition - -
Average inclination class of the soil figure

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0 - 25 %</td>
      <td>Mindre enn 25 % gjennomsnittlig helling. Har ikke betydning for maskinvalg eller jordarbeiding
-- Definition --
Less than25 % inclination. Not significant for choice of machinery or tillage.</td>
      <td></td>
    </tr>
    <tr>
      <td>≥ 25 - 33 %</td>
      <td>Mellom 25 og opp til 33 % gjennomsnittlig helling, Maskinvalg og jordarbeiding begrenses noe
-- Definition --
Between 25% and less than 33 %  average inclination. Choice of machinery and tillage is limited.</td>
      <td></td>
    </tr>
    <tr>
      <td>≥ 33 %</td>
      <td>33 % eller mer gjennomsnittlig helling. Maskinvalg og jordarbeiding begrenses sterkt.
-- Definition --
33 % or more  average inclination. Choice of machinery and tillage is strongly limited.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» SteinBlokk

**Definisjon:** Viser stein- og blokkinnhold (0–50 cm) på arealet på kartleggingstidspunktet
— Definition —
Shows the amount of stones and boulders for the soil figure in the upper 50 cm

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ikke registrert</td>
      <td>Ikke registrert stein og blokk.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ingen eller noe stein og blokk</td>
      <td>Lite eller ingen stein og blokk.</td>
      <td></td>
    </tr>
    <tr>
      <td>Stein og blokkholdig</td>
      <td>Inneholder stein og blokk.</td>
      <td></td>
    </tr>
    <tr>
      <td>Stein og blokkrik</td>
      <td>Inneholder mye stein og blokk.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» ÅrsakTilNedklassifisering

**Definisjon:** Viser årsak til at kartfiguren er nedklassifisert
— Definition —
Shows the reason for the map figure being downgraded

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Jordegenskaper</td>
      <td>Jorda har egenskaper som gjør at arealet krever større innsats i drift</td>
      <td></td>
    </tr>
    <tr>
      <td>Helling</td>
      <td>Arealet har en gjennomsnittlig helling på enten 25 til under 33 prosent eller 33 prosent og over. Dette gir driftsutfordringer</td>
      <td></td>
    </tr>
    <tr>
      <td>Jordegenskaper og helling</td>
      <td>Jorda har egenskaper som gjør at arealet krever større innsats i drift og arealet har en gjennomsnittlig helling på 25 prosent og over til under 33 prosent</td>
      <td></td>
    </tr>
    <tr>
      <td>Hyppig forekommende fjell i dagen</td>
      <td>Arealet har mer enn 4 fjellblotninger / fjell i dagen per 10 daa og dette gir driftsutfordringer</td>
      <td></td>
    </tr>
    <tr>
      <td>Innhold av stein og blokk</td>
      <td>Arealet er enten stein- og blokkholdig eller stein- og blokkrikt og dette gir driftsutfordringer</td>
      <td></td>
    </tr>
    <tr>
      <td>Deler av arealet har organisk jord, har liten evne til å bli kvitt overflødig vann, er bakkeplanert eller forstyrret av graving eller påfylling</td>
      <td>Deler av arealet har egenskaper utover dem som er registrert som egenskaper ved jordtypene og disse gir driftsutfordringer</td>
      <td></td>
    </tr>
    <tr>
      <td>Ingen nedklassifisering</td>
      <td>Arealet har ingen årsak til nedklassifisering</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Tilleggsinformasjon

**Definisjon:** Viser tilleggsinformasjon om andre egenskaper ved arealet.
— Definition —
Supplementary information

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Deler av arealet er bakkeplanert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Deler av arealet er forstyrret av graving eller fyllmateriale</td>
      <td>Deler av arealet er forstyrret av graving eller fyllmateriale.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ingen</td>
      <td>Ingen forstyrrelser.</td>
      <td></td>
    </tr>
    <tr>
      <td>Deler av arealet er organisk jord</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Deler av arealet er preget av vannmetning</td>
      <td>Deler av arealet er preget av vannmetning.</td>
      <td></td>
    </tr>
    <tr>
      <td>Deler av arealet er mineraljord</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hyppig forekommende fjell i dagen</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Kartleggingsmetodikk

**Definisjon:** Viser hvilken opprinnelig kartleggingsmetodikk som er brukt under jordsmonnkartlegging.
--Definition--
Displays the methodolgy used during field mapping.

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Detaljert kartlegging</td>
      <td>Feltbasert kartlegging med avgrensning av jordtyper direkte inn på digitale flybilder i felt, basert på en kombinasjon av borstikk ned til en meters dybde, flybildetolking og GPS. I tillegg deles arealene inn på bakgrunn av terrengegenskaper som helling og stein- og blokkinnhold.</td>
      <td></td>
    </tr>
    <tr>
      <td>Forenklet kartlegging</td>
      <td>Feltbasert kartlegging med en grovere inndeling av jorda enn detaljert kartlegging, der en i tillegg slår sammen enkelte hellingsklasser og ser bort i fra andre egenskaper ved terrenget</td>
      <td></td>
    </tr>
    <tr>
      <td>Harmonisert kartlegging</td>
      <td>Feltbasert kartlegging som kombinerer det beste fra de tidligere metodikkene (detaljert og forenklet).</td>
      <td></td>
    </tr>
  </tbody>
</table>
