#### FiktivDelelinje

linje for å dele opp store flateobjekter<br /><br />Merknad:<br />En del produktspesifikasjoner benytter spesifikke fiktive delelinjer.

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Hjelpelinjer

#### Dataavgrensning

generell avgrensningslinje, f.eks. mellom datasett med ulik kvalitet, innhold eller detaljering

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Hjelpelinjer

#### SOSI_Objekt_Hjelpelinjer (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er til felles for KantUtsnitt, Dataavgrensning og FiktivDelelinje i dette applikasjonsskjemaet

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
    </tr>
  </tbody>
</table>

#### SOSI_Objekt_Linjer_Samferdsel (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er til felles for flere objekttyper i underpakke Samferdsel i dette applikasjonsskjemaet

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>medium</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets beliggenhet i forhold til jordoverflaten<br /><br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MediumSamferdsel</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/mediumsamferdsel">https://register.geonorge.no/sosi-kodelister/kartdata/mediumsamferdsel</a></td>
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
      <td><strong>datafangstdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når objektet siste gang ble registrert/observert/målt i terrenget</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td>beskrivelse av kvaliteten på stedfestingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/m%C3%A5lemetode">https://register.geonorge.no/sosi-kodelister/kartdata/m%C3%A5lemetode</a></td>
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
      <td><strong>kvalitet.nøyaktighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br /><br />Merknad:<br />Oppgitt i cm</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Nøyaktighet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/n%c3%b8yaktighet">https://register.geonorge.no/sosi-kodelister/kartdata/n%c3%b8yaktighet</a></td>
    </tr>
  </tbody>
</table>

#### SOSI_Objekt_Flater (abstrakt)

abstrakt supertype som samler fellesegenskaper og assosiasjoner som gjelder objekttyper som bare har flategeometri

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
KantUtsnitt – rolle: avgrensesAvKantutsnitt – kardinalitet: 0..*

#### SOSI_Objekt_Sperrelinjer (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er felles for alle sperrelinjer i dette applikasjonsskjemaet

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektdataene</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
    </tr>
  </tbody>
</table>

#### SOSI_Objekt_Kombinasjon_Ulike_Geometrityper (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er til felles for alle objekttyper med en kombinasjon av punkt- og flategeometri eller linje- og flategeometri i dette applikasjonsskjemaet

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>datafangstdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når objektet siste gang ble registrert/observert/målt i terrenget</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td>beskrivelse av kvaliteten på stedfestingen</td>
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
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/m%C3%A5lemetode">https://register.geonorge.no/sosi-kodelister/kartdata/m%C3%A5lemetode</a></td>
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
      <td><strong>kvalitet.nøyaktighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br /><br />Merknad:<br />Oppgitt i cm</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Nøyaktighet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/n%c3%b8yaktighet">https://register.geonorge.no/sosi-kodelister/kartdata/n%c3%b8yaktighet</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
KantUtsnitt – rolle: avgrensesAvKantUtsnitt – kardinalitet: 0..*

#### SOSI_Objekt_PunkterOgLinjer_Høyde (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er til felles for flere objekttyper i underpakke Høyde i dette applikasjonsskjemaet

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>medium</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets beliggenhet i forhold til jordoverflaten<br /><br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MediumHøyde</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/mediumh%C3%B8yde">https://register.geonorge.no/sosi-kodelister/kartdata/mediumh%C3%B8yde</a></td>
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
      <td><strong>datafangstdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når objektet siste gang ble registrert/observert/målt i terrenget</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td>beskrivelse av kvaliteten på stedfestingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/m%C3%A5lemetode">https://register.geonorge.no/sosi-kodelister/kartdata/m%C3%A5lemetode</a></td>
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
      <td><strong>kvalitet.nøyaktighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br /><br />Merknad:<br />Oppgitt i cm</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Nøyaktighet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/n%c3%b8yaktighet">https://register.geonorge.no/sosi-kodelister/kartdata/n%c3%b8yaktighet</a></td>
    </tr>
  </tbody>
</table>

#### KantUtsnitt

avgrensning av et utsnitt

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Hjelpelinjer

#### SOSI_Objekt_PunkterOgLinjer (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er til felles for flere objekttyper med punkt- eller linjegeometri i underpakkene Administrative områder, Arealdekke, Bygninger og anlegg, Restriksjonsområder og Samferdsel i dette applikasjonsskjemaet

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>datafangstdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når objektet siste gang ble registrert/observert/målt i terrenget</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td>beskrivelse av kvaliteten på stedfestingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/m%C3%A5lemetode">https://register.geonorge.no/sosi-kodelister/kartdata/m%C3%A5lemetode</a></td>
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
      <td><strong>kvalitet.nøyaktighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br /><br />Merknad:<br />Oppgitt i cm</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Nøyaktighet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/n%c3%b8yaktighet">https://register.geonorge.no/sosi-kodelister/kartdata/n%c3%b8yaktighet</a></td>
    </tr>
  </tbody>
</table>

#### AvtaltAvgrensningslinje

avtalt avgrensningslinje til havs basert på folkerettslig bindende avtaler<br /><br />Merknad:<br />Avtalt avgrensningslinje vil normalt gjelde alle aktuelle former for kyststatsjurisdiksjon. Detaljene vil framgå av den aktuelle avgrensningsavtale.

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Teiggrensepunkt

koordinatbestemt punkt som er påvist, beskrevet og/eller markert spesielt i den geografiske avgrensinga av teigen<br /><br /><br />-- Definition --<br />point established by coordinates, which is proven, described and/or marked specifically in the geographical demarcation of the parcel Note: Can also be am auxiliary point for technical registration purposes Note: A boundary point is placed either at the beginning or end of a parcel boundary.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>grensepunkttype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av hva slags grensemerke som er brukt i terrenget. Sier også om grensepunktet er merket i terrenget, eller om det bare er et registreringsteknisk punkt.<br /><br />-- Definition --<br />statement of what kind of grensemerke which is used in the terrain. Indicates also whether the boundary point is marked in the terrain, or whether it is merely a point for technical registration purposes.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Grensepunkttype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/grensepunkttype">https://register.geonorge.no/sosi-kodelister/kartdata/grensepunkttype</a></td>
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
      <td><strong>grensepunktnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kommunens nummerering av grensepunkt</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Fylkesgrense

avgrensning av fylke

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Kommune

inndeling i administrative og politiske enheter innenfor fylket<br /><br />Merknad: Tilsvarer NUTS 5 og LAU 2 på internasjonalt statistisk nivå

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
      <td>objektets utstrekning</td>
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
      <td><strong>kommunenavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>offisielt navn på kommunen</td>
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
      <td><strong>kommunenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummerering av kommuner i henhold til Statistisk sentralbyrå sin offisielle liste<br /><br />Merknad: Det presiseres at kommune alltid skal ha 4 siffer, dvs. eventuelt med ledende null. Kommune benyttes for kopling mot en rekke andre registre som også benytter 4 siffer.<br /><br />-- Definition - -<br />numbering of municipalities in accordance with Statistics Norway’s official list<br />Note: It must be following that municipality number always consists of 4 digits, i.e. sometimes with leading zero. Municipality is used for establishing relations to a number of other registers which also use 4 digits.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kommunenummer</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer">https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer</a></td>
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
      <td><strong>fylkesnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummerering av kommuner i henhold til Statistisk sentralbyrå sin offisielle liste</td>
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
      <td><strong>fylkesnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>offisielt navn på fylket</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
AvtaltAvgrensningslinje – rolle: avgrensesAvAvtaltAvgrensningslinje – kardinalitet: 0..*
Fylkesgrense – rolle: avgrensesAvFylkesgrense – kardinalitet: 0..*
Riksgrense – rolle: avgrensesAvRiksgrense – kardinalitet: 0..*
Territorialgrense – rolle: avgrensesAvTerritorialgrense – kardinalitet: 0..*
Kommunegrense – rolle: avgrensesAvKommunegrense – kardinalitet: 0..*

#### Riksgrense

avgrensningen av nasjonen Norge mot andre nasjoner<br /><br />Merknad:<br />Delvis avledet fra norsk svensk riksgrensemodell<br /><br />--Definition--<br />delimitation of the country of Norway over against other countries Note:Partially derived from the Norwegian-Swedish national boundary model

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Grunnlinje

rette linjer trukket opp mellom punkter på de ytterste nes og skjær som stikker opp av havet ved lavvann (fjære sjø)<br /><br />Merknad:<br />Med rett linje forstås den korteste linje mellom to punkt (såkalt geodetisk linje).

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Kommunegrense

avgrensing av kommune

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Grunnlinjepunkt

knekkpunkt på grunnlinjen

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>grunnlinjepunktnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av navn på grunnlinjen</td>
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
      <td><strong>grunnlinjepunktnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av nummeret på grunnlinjen</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Territorialgrense

avgrensning i havet av statens suverenitetsområde, beregnet 12 nm (22 224 m) utenfor og parallelt med grunnlinjen

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### ElvMidtlinje

kunstig objekt hvor senterlinjen er en fiktiv linje som skjøter sammen en-strekselver gjennom en elveflate

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Park

grøntområde i by- eller tettbygd område, opparbeidet og vedlikeholdt med plenareal, beplantninger, vannpartier og lignende<br /><br /><br />-- Definition --<br />green area in a city or densely populated area, worked up and maintained, with lawns, planting, water features, etc.

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### Flomløpkant

begrensningslinje for store markerte elveløp hvor det pga regulering eller andre årsaker bare det en sjelden gang er vannføring<br /><br /><br />-- Definition --<br />Demarkation line for large river courses where water flow is occational due to regulation or other causes.

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### ElvelinjeFiktiv

Kunstig objekt hvor senterlinjen representerer en fiktiv linje som skjøter sammen lenker der det er hull i beskrivelsen av vannforløp<br /><br />-- Definition –<br />Artificial objekt where the center linje represents a fictious line joining links where there are gaps in the description of water courses

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Skog

alle typer skogsmark som barskog, lauvskog og blandingsskog<br /><br />Merknad: Også hogstflater - selv om nyplanting ikke er synlig.  Omfatter alle slags skogboniteter, også storvokste vierkrattbelter i Nord-Norge<br /><br /><br />-- Definition --<br />all types of forest land, such as coniferous forest, deciduous forest and mixed forest

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*

#### ElveKant

konturlinje mellom land og elveflate<br /><br /><br />-- Definition --<br />Demarkation line between land and river surface.

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### InnsjøInnsjøSperre

hjelpelinje for avgrensning av en innsjø mot en annen innsjø der det ikke er elv mellom<br /><br /><br />-- Definition --<br />Construction line for delimitation of lake surface from another lake where there is no river between them.

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Sperrelinjer

#### Myr

åpent ikke skogvokst område med myrvegetasjon<br /><br />Merknad:  Myra kan være bevokst, men da av få eller små trær.  Grøftet myr som er blitt skogmark tas IKKE med<br /><br /><br />-- Definition --<br />open, non-forested area with marsh vegetation

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*

#### ÅpentOmråde

område som ikke er klassifisert som annet tema i henhold til gjeldende produktspesifikasjon

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*

#### Gravplass

areal hvor gravlegging kan finne sted i en grav  innenfor gravfelt

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantregulert – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*

#### Kystkontur

grense mellom land og sjø, definert som midlere høyvannslinje<br /><br />Merknad:<br />Tilsvarer COALNE i S-57<br /><br /><br />-- Definition --<br />boundary between land and sea, defined as the mean high water line Note: Corresponds to COALNE in S-57

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Arealbrukgrense

avgrensning av de ulike arealbruksflatene<br /><br />Merknad:<br />Kode for bruken av arealet legges på flaten, dvs på representasjonspunktet der dette representerer flata.<br /><br /><br />-- Definition --<br />delimitation of the various land use areas Note: Land use code is assigned to the surface, i.e. on the representation point which represents this surface.

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Lufthavn

land- eller sjøområde (med bygninger, installasjoner og utstyr) som helt eller delvis brukes for luftfartøyers avgang, landing og annen manøvrering på bakken

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
      <td>objektets utstrekning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>lufthavntype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av type lufthavn</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Lufthavntype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/lufthavntype">https://register.geonorge.no/sosi-kodelister/kartdata/lufthavntype</a></td>
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
      <td><strong>trafikktype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av rutetrafikk</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Trafikktype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/trafikktype">https://register.geonorge.no/sosi-kodelister/kartdata/trafikktype</a></td>
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
      <td><strong>iataKode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik kode for lufthavner.<br /><br />Merknad1: Ikke alle lufthavner har IATA kode.<br />Merknad 2: Bare norske lufthavner er tatt med her.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>IATAKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/iatakode">https://register.geonorge.no/sosi-kodelister/kartdata/iatakode</a></td>
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
      <td><strong>icaoKode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av lufthavn ved kode på fire alfanumeriske tegn.<br /><br />Merknad: Den første bokstaven tilordnes etter kontinent og angir et land eller en gruppe land på det samme kontinentet. Den andre bokstaven angir landet og de to siste angir lufthavn.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>ICAOKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/icaokode">https://register.geonorge.no/sosi-kodelister/kartdata/icaokode</a></td>
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
      <td><strong>lufthavneier</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>eier av lufthavn</td>
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
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på flyplass<br /><br />Merknad: Benyttes spesielt for de flyplasser som ikke har IATA eller ICAO kode</td>
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
      <td><strong>retning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>linjestykke i planet med retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retning</td>
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
      <td><strong>retning.retningsverdi</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>generelt element med angivelse av retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
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
      <td><strong>retning.retningsenhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>enhet for retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retningsenhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet">https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet</a></td>
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
      <td><strong>retning.retningsreferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referansesystem for retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retningsreferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse">https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_Kombinasjon_Ulike_Geometrityper

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*

#### FerskvannTørrfall

sandbanker og avleiringer i elv/bekk som oversvømmes ved normal høyvannsføring<br /><br />Merknad:<br />Flatene avgrenses av FerskvannTørrfallKant og elve- eller kanalkant som grenser inn til tørrfallet.<br /><br /><br />-- Definition --<br />Banks of sand or sediments in rivers and brooks which is flooded during high water levels.

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
FerskvannTørrfallkant – rolle: avgrensesAvFerskvanntørrfallkant – kardinalitet: 0..*

#### SportIdrettPlass

område hvor det utøves sport og idrett<br /><br /><br />-- Definition --<br />area where sports and athletics are engaged in??

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*

#### KanalGrøft

rennende vann der forløpet er menneskeskapt<br /><br /><br />-- Definition --<br />Running water where the water course is made by humans.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>vannBredde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>gir informasjon om hvordan elv/bekk og kanal/grøft grovt er klassifisert etter bredde<br /><br />-- Definition --<br />gives information about how a river/brook and a channel/trench are classified according to width</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>VannBredde</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/vannbredde">https://register.geonorge.no/sosi-kodelister/kartdata/vannbredde</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### ElvBekk

mindre vannvei for rennende vann representert ved senterlinje

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>vannbredde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>grov klassifikasjon av vassdrag etter gjennomsnittelig bredde over lengre strekninger<br /><br /><br />-- Definition - -<br />Rough classification of river system according to average width over longer sections.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>VannBredde</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/vannbredde">https://register.geonorge.no/sosi-kodelister/kartdata/vannbredde</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### FerskvannTørrfallkant

avgrensningslinje for FerskvannTørrfall<br /><br /><br />-- Definition --<br />Demarkation line for FreshwaterForeshoreEdge

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Innsjøkant

konturlinje mellom land og innsjø<br /><br /><br />-- Definition --<br />Demarkation line between land and lake surface.

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### BymessigBebyggelse

kvartalsbebyggelse (bykjerne) med stort innslag av forretnings- og servicebygg<br /><br />Merknad:<br />Husene har overveiende to eller flere etasjer.<br /><br /><br />-- Definition --<br />city block (town centre) with a large element of shops and service buildings. Note: The buildings have predominantly two or more storeys.

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### Tettbebyggelse

sammenhengende bebygd område (overveiende boligbegyggelse) hvor husene i hovedsak ligger tettere enn 50 meter<br /><br /><br />-- Definition --<br />continuous, developed area (predominantly residential) where the buildings, for the most part, are closer than 50 metres apart

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### DyrketMark

fulldyrket (plogmark), beitemark som er overflatebehandlet og bærhager. Jordbruksareal som ligger brakk i kortere perioder eller brukes til kulturbeite, regnes også som dyrket mark<br /><br /><br />-- Definition --<br />fullly cultured (plowed land), pasture with surface treatment, and berry gardens. Farmlands which lie fallow for shorter periods or are used as cultivated pasture, are also regarded as crop land.

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### Steintipp

permanent massedeponering som ikke er skogbevokst og er dominerende i<br />landskapet (f.eks. laget i forbindelse med gruvedrift eller vassdragsutbygging)

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### Steinbrudd

område for steinbrudd<br /><br /><br />-- Definition --<br />area for stone quarry. Land use boundary is used as delimitation.

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### Rullebane

avgrenset, rektangulært område på en flyplass på land innrettet for landing og avgang med luftfartøyer

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### HavInnsjøSperre

en fiktiv linje som definerer grensen mellom hav og innsjø, i samme nivå som kystkontur (middel høyvann)<br /><br /><br />-- Definition --<br />Construction line for delimitation of lake surface where it turns into sea surface. At the same altitude as the shoreline (by middle high tide).

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Sperrelinjer

#### HavElvSperre

en fiktiv linje som definerer grensa mellom sjø og elv, i samme nivå som kystKontur (middel høyvann)<br /><br />Merknad:<br />Denne er identisk med samme linje nevnt under kapitlet Innsjøer og vassdrag).<br /><br /><br />-- Definition --<br />a fictitious line which defines the border between sea and river at the same level as coastline (mean high water) Note: This is identical to the same line referred to in the chapter on Lakes and watercourses).

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Sperrelinjer

#### Golfbane

område for golfspilling<br /><br /><br />-- Definition --<br />area for golfing

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### SnøIsbre

grense mellom snø eller isbre og barmark der det er usikkert om det er isbre eller snø<br /><br /><br />Merknad:<br />Isbre kan også være en del av evig snø, særlig når breens kantlinje ikke kan defineres (og registreres) som Isbre.  Den gamle koden for isbre er overført til dette objektet !<br /><br /><br />-- Definition --<br />Snow or glacier and bare ground where it is uncertain if it is snow or glacier. Note: A snowfield can also be a part of perpetual snow, especially when the glacier's edge cannot be defined and registered as a glacier.

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### Innsjø

en ferskvannsflate som ikke er renndende vann<br /><br /><br />-- Definition --<br />Freshwater surface which is not running water.

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
      <td>objektets utstrekning</td>
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
      <td><strong>vatnLøpenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon på innsjøer som fortløpende løpenummer i henhold til NVEs Innsjøregister<br /><br />-- Definition --<br />unique identification of lakes as consecutive serial number in accordance with the lake register of the NVE (The Norwegian Water Resources and Energy Administration)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>registrert høyde for vannspeilet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
InnsjøInnsjøSperre – rolle: avgrensesAvInnsjøinnsjøsperre – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
HavInnsjøSperre – rolle: avgrensesAvHavInnsjøSperre – kardinalitet: 0..*
InnsjøElvSperre – rolle: avgrensesAvInnsjøElvSperre – kardinalitet: 0..*

#### InnsjøMidtlinje

kunstig objekt hvor senterlinjen er en fiktiv linje som skjøter sammen en-strekselver gjennom en innsjøflate

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Fiktiv senterlinje i innsjø</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Havflate

havområde som avgrenses av Kystkontur, Kystsperre, HavElvSperre og KystkonturTekniskAnlegg<br /><br /><br />-- Definition --<br />sea area which is delimited by Coastline, CoastDelineation, SeaRiverDelineation and ShorelineConstruction

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
HavInnsjøSperre – rolle: avgrensesAvHavInnsjøSperre – kardinalitet: 0..*
HavElvSperre – rolle: avgrensesAvHavElvSperre – kardinalitet: 0..*

#### InnsjøRegulert

en ferskvannsflate som ikke er rennende vann og som er regulert<br /><br /><br />-- Definition --<br />Freshwater surface which is not running water, but regulated

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
      <td>objektets utstrekning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>vatnLøpenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon på innsjøer som fortløpende løpenummer i henhold til NVEs Innsjøregister<br /><br />-- Definition --<br />unique identification of lakes as consecutive serial number in accordance with the lake register of the NVE (The Norwegian Water Resources and Energy Administration)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>lavesteRegulerteVannstand</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>laveste regulerte vannstand - LRV<br /><br />-- Definition --<br />lowest regulated water level</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>for regulerte innsjøer er HØYDE tilsvarende høyeste regulert vannstand (HRV)<br /><br />-- Definition --<br />highest regulated water level</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
InnsjøInnsjøSperre – rolle: avgrensesAvInnsjøinnsjøsperre – kardinalitet: 0..*
InnsjøElvSperre – rolle: avgrensesAvInnsjøElvSperre – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantregulert – kardinalitet: 0..*

#### Elv

større vannvei for rennende vann representert ved flate

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
FerskvannTørrfallkant – rolle: avgrensesAvFerskvanntørrfallkant – kardinalitet: 0..*
HavElvSperre – rolle: avgrensesAvHavElvSperre – kardinalitet: 0..*
InnsjøElvSperre – rolle: avgrensesAvInnsjøElvSperre – kardinalitet: 0..*

#### Industriområde

område, bebygd eller ubebygd, benyttet til industriformål<br /><br />Merknad:<br />Omfatter også anlegg for vannforsyning, avfallshåndtering og rensing, samt kraftstasjon, transformatorstasjon o.l.<br /><br /><br />-- Definition --<br />developed or undeveloped, used for industrial purposes. Also includes installations for water supply, waste handling and cleaning, as well as power plants, transformer substation, etc.

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### Foss

vann i tilnærmet fritt fall<br /><br />Merknad:<br />Representeres med punkt eller linje mellom topp og bunn av foss.<br /><br /><br />-- Definition --<br />Quoted height of fall for waterfall and cascades.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>retning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>linjestykke i planet med retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retning</td>
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
      <td><strong>retning.retningsverdi</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>generelt element med angivelse av retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
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
      <td><strong>retning.retningsenhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>enhet for retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retningsenhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet">https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet</a></td>
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
      <td><strong>retning.retningsreferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referansesystem for retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retningsreferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse">https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Skjær

generalisert punktobjekt for små øyer eller landareal<br /><br /><br />-- Definition --<br />generalised point object for small islands or land area

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### InnsjøkantRegulert

avgrensningslinje for innsjø som er oppdemt/regulert<br /><br /><br />-- Definition --<br />Demarkation line for dammed or regulated lake.

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Tregruppe

enkeltstående tre eller trær i små grupper<br /><br />Merknad: Avstanden mellom trærne/gruppene skal være så stor at det ikke kan defineres som et sammenhengende skogsområde<br /><br /><br />-- Definition --<br />single tree or trees in small groups

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### InnsjøElvSperre

hjelpelinje for avgrensning av innsjø mot elv eller kanal/grøft<br /><br /><br />-- Definition --<br />Construction line for delimitation of lake surface from river, canal or ditch.

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Sperrelinjer

#### Alpinbakke

nedfart for ski med permanent karakter<br /><br /><br />-- Definition --<br />permanent downhill ski slope

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
      <td>objektets utstrekning</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
FiktivDelelinje – rolle: avgrensesAvFiktivdelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: avgrensesAvDataavgrensning – kardinalitet: 0..*
ElveKant – rolle: avgrensesAvElveKant – kardinalitet: 0..*
Kystkontur – rolle: avgrensesAvKystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: avgrensesAvArealbrukgrense – kardinalitet: 0..*
Innsjøkant – rolle: avgrensesAvInnsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: avgrensesAvInnsjøkantRegulert – kardinalitet: 0..*

#### Tårn

høy bygningsmessig konstruksjon hvor høyden er stor i forhold til bygningens areal i grunnplanet<br />Merknad: Omfatter alle tårn med unntak av de tårn som har en mer spesifisert beskrivelse- som f.eks Silo og tank.<br />Eksempel: Måletårn og stupetårn<br /><br /><br />-- Definition --<br />Tall building structure in which the height is great in relation to the footprint of the building

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Reingjerde

gjerde for reindrift<br /><br /><br />-- Definition --<br />fence for reindeer husbandry

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Gruve

ikke dagbrudd og skjerp, hvor gruveinngangen er tydelig<br /><br /><br />-- Definition --<br />not quarry and prospect, where the pit entrance is prominent

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### MastTele

mast med radio- og telekommunikasjonsutstyr for sending/mottak av telesignaler<br /><br />Merknad:<br />Kan benyttes dersom ..KOPLING * 2 * MA<br /><br /><br />-- Definition --<br />mast with radio and telecommunication equipment for sending /receiving telecommunications signals. Note: may be used if ..KOPLING * 2 * MA  (KOPLING := coupling)

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Campingplass

faste anlegg med vaskerom, campinghytter o.l.<br /><br /><br />-- Definition --<br />permanent  construction with wash rooms, cabins, etc.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Lysløype

løypetrasé som har belysning<br /><br /><br />-- Definition --<br />trail route with lighting

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Parkeringsområde

område for parkering av kjøretøy

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Navigasjonsinstallasjon

objekt som hjelper sjøfarende å navigere på sjøen<br /><br /><br />-- Definition --<br />object which helps mariners to navigate at sea

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Taubane

innretning hvor tau eller vaiere bærer og eller trekker last over en strekning<br /><br /><br />-- Definition --<br />facility where ropes or cables carry and/or pull cargo over some distance

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Vindkraftverk

kraftverk som nytter vindens energi til å produsere elkraft<br /><br />Merknad:<br />Kan benyttes dersom ..KOPLING * 3 * VKST<br /><br /><br />-- Definition --<br />power plant which utilises the wind's energy to produce electric power. Note: may be used if ..KOPLING * 3 * VKST   (KOPLING := coupling)

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Pir

markert utstikkende brygge, normalt med vann under, i sjø<br /><br /><br />-- Definition --<br />marked protruding pier, normally with water underneath, in the sea

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Rørgate

rør som leder vann frem til foredlingsanlegg<br /><br /><br />-- Definition --<br />pipes which lead water into processing facility

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Bygning

bygning som er registrert i Matrikkelen<br /><br />Representasjonspunkt for bygningen. Punktet angis med geometritypen Punkt definert i SOSI<br /><br />Skal plasseres innenfor bygningens omriss.<br /><br />Punkt registreres også uten at en har omrisset, men da settes ikke kvalitetsmerket for at den er verifisert mot bygningens omriss.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>bygningstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>bygningstype sier hva bygningen er brukt til</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>BygningstypeKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/bygningstypekode">https://register.geonorge.no/sosi-kodelister/kartdata/bygningstypekode</a></td>
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
      <td><strong>hytteinformasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>informasjon om hytter i form av betjeningsgrad, eier og tilgjengelighet<br /><br />-- Definition --<br />Information on cabins in the form of identification, services offered and owner</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Hytteinformasjon</td>
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
      <td><strong>hytteinformasjon.betjeningsgrad</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av hvilke servicefunksjoner som er tilgengelige<br /><br />-- Definition --<br />description of which service functions are available</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Betjeningsgrad</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/betjeningsgrad">https://register.geonorge.no/sosi-kodelister/kartdata/betjeningsgrad</a></td>
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
      <td><strong>hytteinformasjon.hytteeier</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>eieren av en hytte<br /><br />-- Definition --<br />the owner of a cabin</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Hytteeier</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/hytteeier">https://register.geonorge.no/sosi-kodelister/kartdata/hytteeier</a></td>
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
      <td><strong>hytteinformasjon.tilgjengelighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver om hytta er låst eller ulåst</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Tilgjengelighet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/tilgjengelighet">https://register.geonorge.no/sosi-kodelister/kartdata/tilgjengelighet</a></td>
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
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på turisthytta</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Kombinasjon_Ulike_Geometrityper

**Assosiasjoner**
Takkant – rolle: avgrensesAvTakkant – kardinalitet: 0..*

#### Tankkant

avgrensning av tank<br /><br /><br />-- Definition --<br />delimitation of tank/vessel

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Molo

kunstig eller naturlig oppbygning som demper eller tilintetgjør bølgebevegelser i sjøen<br /><br /><br />-- Definition --<br />artificial or natural structure which reduces or eliminates waves in the sea

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Skytebaneinnretning

omriss av tekniske anlegg på skytebane - standplass og skiver som ikke blir registrert som f.eks bygninger og murer<br /><br /><br />-- Definition --<br />outline of technical facilities at shooting range - stands and targets that are not registered as building or walls

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Ledning

begrepet ledning er i modellen generalisert til å bety alle typer langsgående fysiske objekter i ledningstraseen<br /><br />Merknad:<br />Dette inkluderer også tunnel, kanal, rør og andre objekter som brukes som omsluttende konstruksjon for andre ledninger.<br /><br /><br />-- Definition --<br />in the model, the term line has been generalised to mean all types of longitudinal physical objects in the route. Note: this also includes tunnels, ducts, pipes and other objects used as encasing?? structures for other lines

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Takkant

bygningens ytre takflateavgrensing<br /><br />Merknad: Høydereferansen er de målte punktene på taket.<br /><br />Merknad: Dersom deler av takkanten ikke er synlig kodes den synlige delen som takkant- og den ikke synlige som fiktiv bygningsavgrensning.<br /><br /><br />-- Definition --<br />the external delimitation of the roof surface of the building

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### KaiBrygge

angivelse av  innretninger som er satt opp for å betjene båter ved lasting- lossing og landligge<br />Merknad: Kai er utvidet til også å kunne være bare et fortøyningsanlegg- f.eks. enkeltstående metallring for fastgjøring av skip.<br /><br /><br />-- Definition --<br />indication of facilities set up to serve boats during loading, unloading and docking

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Skitrekk

taubane til å dra skiløper opp bratte bakker<br />Merknad: Særlig brukt i alpinbakker<br /><br /><br />-- Definition --<br />cableway for pulling skiers up steep slopes

Egenskaper

(ingen)

Relasjoner

**Arv**
Taubane

#### Flytebrygge

brygge som er forankret til bunn og hvor plasseringen kan avhenge av vind og strømretning<br /><br /><br />-- Definition --<br />wharf chained to the bottom and whose location may depend on the direction of the wind and current

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### LuftledningLH

linje som fører elektrisk kraft over store avstander og der det er usikkert om det er lav- eller høyspentlinje<br /><br />Merknad:<br />Kan benyttes dersom ..MEDIUM L og ..LEDNING * 3 8<br /><br /><br />-- Definition --<br />line conducting electrical power over large distances and where it is uncertain whether there is a low-voltage or high-voltage line. Note: may be used if ..MEDIUM L and ..LINE * 3 8

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>flerLinjer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av antall kraftlinjer</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>FlerLinjer</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/flerlinjer">https://register.geonorge.no/sosi-kodelister/kartdata/flerlinjer</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Hoppbakke

anlegg for skihopping med kunstig eller naturlig tilløp<br /><br /><br />-- Definition --<br />facility for ski jumping with artificial or natural approach

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>lengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>bakkens lengde i meter</td>
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
      <td><strong>retning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>linjestykke i planet med retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retning</td>
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
      <td><strong>retning.retningsverdi</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>generelt element med angivelse av retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
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
      <td><strong>retning.retningsenhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>enhet for retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retningsenhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet">https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet</a></td>
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
      <td><strong>retning.retningsreferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referansesystem for retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retningsreferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse">https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Dam

konstruksjon for å heve vannspeilet og danne et kunstig vannmagasin, samt regulere vannføringen<br /><br /><br />-- Definition --<br />construction for elevating the water surface and creating an artifical water reservoir as well as regulating the flow of water

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### SpesiellDetalj

objekttyper som det er nødvendig å angi av kartografiske hensyn og som ikke fanges opp av definerte objekttyper

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Curve</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Tank

lukkede kar for oppbevaring av gass eller væsker som ikke er registrert som bygning<br /><br /><br />-- Definition --<br />closed tank/vessel for storage of gas or fluids which is not registered as building

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Surface</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_Kombinasjon_Ulike_Geometrityper

**Assosiasjoner**
Tankkant – rolle: avgrensesAvTankkant – kardinalitet: 0..*

#### Høydekurve

linje i terrenget med fast høydeverdi (z-verdi) over referansehøyden<br /><br />Merknad: Høydekurver skal ikke krysse hverandre, bortsett fra der dette er tilfelle (overheng).<br /><br /><br />-- Definition --<br />line in the terrain with a fixed height value (z value) above the reference height

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av høydekurvens høyde over høydereferansen i meter<br /><br />-- Definition --<br />indication of the depression curve's height above the height reference in metres - to be given with decimals if necessary</td>
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
SOSI_Objekt_PunkterOgLinjer_Høyde

#### Terrengpunkt

punkt i terrenget med målt høydeverdi som brukes for å angi høyde på markerte flater i terrenget som for eksempel sadler og store flater, i veg- og gatekryss og andre kryss mellom samferdselslinjer, på gårdsplasser utenfor hovedinnganger og på parkeringsplasser<br /><br /><br />-- Definition --<br />point in the terrain with a measured height value used to indicate the height on pronounced surfaces in the terrain, such as saddles and large surfaces, in road and street intersections and other intersections between transportation lines, in courtyards outside main entrances and in car parks

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av punktets høyde, og oppgis i meter<br /><br />-- Definition --<br />indication of the height of the point, to be given with decimals if necessary</td>
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
SOSI_Objekt_PunkterOgLinjer_Høyde

#### TrigonometriskPunkt

varig merket punkt, markert med bolt eller annet merke, der plane koordinater og høyde er bestemt i et trigonometrisk nett, i et geodetisk system<br /><br /><br />-- Definition --<br />permanently marked point, marked with a bolt or other mark in which the plane coordinates and/or height are determined in a Trigonometrical network in a geodetic system

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av punktets høyde, og oppgis i meter<br /><br />-- Definition --<br />indication of the height of the point, to be given with decimals if necessary</td>
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
SOSI_Objekt_PunkterOgLinjer_Høyde

#### Forsenkningskurve

linje i terrenget med fast høydeverdi (z-verdi) som beskriver en forsenkning i terrenget<br /><br />Merknad: Alle kurver som beskriver en forsenkning skal kodes som forsenkningskurver- ikke bare den nederste kurven.<br /><br /><br />-- Definition --<br />line in the terrain with a fixed height value (z value) which describes a depression in the terrain

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir forsenkningskurvens  høyde over høydereferansen i meter<br /><br />-- Definition --<br />indicates the depression curve's height above the height reference in metres - to given with decimals if necessary</td>
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
SOSI_Objekt_PunkterOgLinjer_Høyde

#### Hjelpekurve

linje som følger terrenget med fast høydeverdi (z-verdi) og som brukes for bedre å beskrive terrenget mellom de vanlige høydekurvene<br /><br />Merknad: Tidligere kalt mellomkurve<br /><br /><br />-- Definition --<br />line which follows the terrain with a fixed height value (z value), and which is used to provide a better description of the terrain between the ordinary ??(contour lines / height contours)

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av hjelpekurvens høyde over høydereferansen i meter<br /><br />-- Definition --<br />indication of the auxiliary curve's height above the height reference in metres - to be given with decimals if necessary</td>
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
SOSI_Objekt_PunkterOgLinjer_Høyde

#### Allmenning

område som alle, eller en bestemt gruppe har bruksrett til<br /><br />Merknad: Det er ofte vilkår om at den bruksberettigede må ha en eiendom av en viss størrelse. Eksempel på rettigheter er beiterett, hogstrett, fiskerett.

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
      <td>objektets utstrekning</td>
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
      <td><strong>allmenningtype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nærmere inndeling av allmenninger</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Allmenningtype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/allmenningtype">https://register.geonorge.no/sosi-kodelister/kartdata/allmenningtype</a></td>
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
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på området</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
Allmenninggrense – rolle: avgrensesAvAllmenninggrense – kardinalitet: 0..*

#### Skytefeltgrense

avgrenser skytefelt

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Naturverngrense

avgrenser et naturvernområde

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Allmenninggrense

avgrensning av allmenning

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
      <td>forløp som følger overgang mellom ulike fenomener</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Naturvernområde

naturvernområde

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
      <td>objektets utstrekning</td>
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
      <td><strong>vernedato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for vern av området</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td>ulike type vern sortert under forskjellige lovverk og med tilhørende restriksjoner</td>
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
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/verneform">https://register.geonorge.no/sosi-kodelister/kartdata/verneform</a></td>
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
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på naturvernområdet</td>
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

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
Naturverngrense – rolle: avgrensesAvNaturverngrense – kardinalitet: 0..*

#### Skytefelt

område for militære avdelingers skarpskyteøvelse til lands og/eller til vanns<br /><br />Merknad: Gjelder også testfelt knyttet til våpen- spregningsindustri<br /><br /><br />-- Definition --<br />area where divisions from the armed forces undertake live firing practice on land and/or at sea. Note: Also applies to proving grounds related to the explosive armaments industry

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
      <td>objektets utstrekning</td>
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
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på området</td>
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
      <td><strong>skytefeltstatus</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir skytefeltstatus</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Skytefeltstatus</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/skytefeltstatus">https://register.geonorge.no/sosi-kodelister/kartdata/skytefeltstatus</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_Flater

**Assosiasjoner**
Skytefeltgrense – rolle: avgrensesAvSkytefeltgrense – kardinalitet: 0..*

#### Naturvernpunkt

vernet enkeltobjekt etter gammelt lovverk. Vil ikke bli etablert nye. Trær, stein osv.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>vernedato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for vern av området</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td>ulike typer vern sortert under forskjellige lovverk og med tilhørende restriksjoner</td>
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
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/verneform">https://register.geonorge.no/sosi-kodelister/kartdata/verneform</a></td>
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
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på naturvernområdet</td>
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

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Veglenke

Objekttype som representerer lenker i vegnettet<br />Eksempel: NVDB Referanselenkedeler

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>typeVeg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>type veg (FormOfWay).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TypeVeg</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/typeveg">https://register.geonorge.no/sosi-kodelister/kartdata/typeveg</a></td>
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
      <td><strong>vegsystem</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>definerer hvilke deler av vegnettet som forvaltningsmessig hører sammen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Vegsystem</td>
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
      <td><strong>vegsystem.vegkategori</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>kategorisering som angir på hvilket nivå vegmyndigheten for strekningen ligger</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Vegkategori</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/vegkategori">https://register.geonorge.no/sosi-kodelister/kartdata/vegkategori</a></td>
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
      <td><strong>vegsystem.vegfase</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir vegens fase i livet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Vegfase</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/vegfase">https://register.geonorge.no/sosi-kodelister/kartdata/vegfase</a></td>
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
      <td><strong>vegsystem.vegnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvilke deler av vegnettet som rutemessig hører sammen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>motorvegtype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>klassifisering av veger etter grad av vilkår med hensyn til f.eks. fart, avkjøringer/kryss og antall kjørefelt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Motorvegtype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/motorvegtype">https://register.geonorge.no/sosi-kodelister/kartdata/motorvegtype</a></td>
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
      <td><strong>rutemerking</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forteller om det er merking  langs en sti, løype, veg, sykkelvei mv</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>RuteMerking</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/rutemerking">https://register.geonorge.no/sosi-kodelister/kartdata/rutemerking</a></td>
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
      <td><strong>vedlikeholdsansvarlig</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>institusjon eller andre som har ansvar for vedlikehold av rute</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Vedlikeholdsansvarlig</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/vedlikeholdsansvarlig">https://register.geonorge.no/sosi-kodelister/kartdata/vedlikeholdsansvarlig</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_Linjer_Samferdsel

#### Stasjon

representasjonspunkt for stasjon, holdeplass eller godsterminal<br /><br /><br />-- Definition --<br />representation point for station, stopping place or freight terminal

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på stasjon<br /><br />-- Definition --<br />name of a station</td>
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
      <td><strong>retning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>linjestykke i planet med retning<br /><br /><br />-- Definition - -<br />directed line segment in the plane</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retning</td>
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
      <td><strong>retning.retningsverdi</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>generelt element med angivelse av retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
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
      <td><strong>retning.retningsenhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>enhet for retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retningsenhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet">https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet</a></td>
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
      <td><strong>retning.retningsreferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referansesystem for retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retningsreferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse">https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Vegsperring

fysisk sperring av vegen<br /><br /><br />-- Definition --<br />physical blockage of the road

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>vegsperringtype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir type vegsperring<br /><br />-- Definition --<br />indicates type of roadblock</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Vegsperringtype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/vegsperringtype">https://register.geonorge.no/sosi-kodelister/kartdata/vegsperringtype</a></td>
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
      <td><strong>retning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>linjestykke i planet med retning<br /><br /><br />-- Definition - -<br />directed line segment in the plane</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retning</td>
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
      <td><strong>retning.retningsverdi</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>generelt element med angivelse av retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
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
      <td><strong>retning.retningsenhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>enhet for retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retningsenhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet">https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet</a></td>
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
      <td><strong>retning.retningsreferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referansesystem for retning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Retningsreferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse">https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_PunkterOgLinjer

#### Bane

teoretisk linje som representerer ett enkelt eller flere parallelle spor som del av en banestrekning<br /><br /><br />-- Definition --<br />theoretical line which represents a single or several parallel tracks as part of a railway line<br /><br /><br />-- INSPIRE --<br />Maps to RailwayLink

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
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

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>jernbaneinformasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av jernbanen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Jernbaneinformasjon</td>
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
      <td><strong>jernbaneinformasjon.anleggstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir type jernbaneanlegg</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Jernbanetype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/jernbanetype">https://register.geonorge.no/sosi-kodelister/kartdata/jernbanetype</a></td>
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
      <td><strong>jernbaneinformasjon.banestatus</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>definerer status for drift på en banestrekning. I denne sammenhengen betyr Midlertidig ute av drift at anlegget finnes, men at det ikke er trafikk. Det kan kreves vedlikeholdsarbeid for å sett i drift. Nedlagt betyr at strekningen er nedlagt ved Stortingsvedtak, men at strekningen fortsatt finnes fysisk i terrenget. Nedlagte strekninger kan kreve nytt vedtak for å sette i drift.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Jernbanestatus</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/jernbanestatus">https://register.geonorge.no/sosi-kodelister/kartdata/jernbanestatus</a></td>
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
      <td><strong>sporantall</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>definerer antall spor på en banestrekning<br /><br />-- Definition --<br />defines the number of tracks on a railway line</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Sporantall</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/sporantall">https://register.geonorge.no/sosi-kodelister/kartdata/sporantall</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
SOSI_Objekt_Linjer_Samferdsel

#### StedsnavnTekst

StedsnavnTekst er stedsnavn fra SSR tilpasset visning på kart

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navneobjekthovedgruppe</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hovedgruppene følger i hovedsak Inspire "NamedPlaceTypeValue", men populatedPlace og building er samlet under bebyggelse og hydrography er delt mellom sjø og ferskvann.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Navneobjekthovedgruppe</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjekthovedgruppe">https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjekthovedgruppe</a></td>
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
      <td><strong>navneobjektgruppe</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>inndeling i kategorier under hver hovedgruppe.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Navneobjektgruppe</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjektgruppe">https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjektgruppe</a></td>
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
      <td><strong>navneobjekttype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>stedets navneobjekttype er en underinndeling av navneobjektgruppene som igjen er inndeling av navneobjekthovedgruppene.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Navneobjekttype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjekttype">https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjekttype</a></td>
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
      <td><strong>språk</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvilket språk teksten hører til, norsk, kvensk, nordsamisk, lulesamisk, sørsamisk osv.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>SpråkKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/stedsnavn/spr%C3%A5kkode">https://register.geonorge.no/sosi-kodelister/stedsnavn/spr%C3%A5kkode</a></td>
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
      <td><strong>stedsnavnnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>stedsnummer, stedsnavnnummer og skrivemåtenummer skal sammen utgjøre en såkalt tematisk id som brukes av registerførere som opplslagsnummer. identifikatoren ligner litt på Gnr/Bnr/Fnr.<br /><br />Stedsnavnnummer er et løpende nummer (starter på 1) systemet gir stedsnavnet som en identifikator. stedsnavnnummeret er kun unikt under et stedsnummer og kan ikke brukes om igjen for dette stedsnavnet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>språkprioritering</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>stedsnavnet sin prioritering i forhold til de ulike språkgruppene</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>SpråkprioriteringKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/stedsnavn/spr%C3%A5kprioriteringkode">https://register.geonorge.no/sosi-kodelister/stedsnavn/spr%C3%A5kprioriteringkode</a></td>
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
      <td><strong>stedsnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>stedsnummer, stedsnavnsnummer og skrivemåtenummer skal sammen utgjøre en såkalt tematisk id som brukes av registerførere som opplslagsnummer. Identifikatoren ligner litt på Gnr/Bnr/Fnr.<br /><br />Stedsnummeret er et løpende nummer systemet gir stedet som en identifikator. Stedsnummeret er unikt og kan ikke brukes om igjen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>skrivemåtenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>stedsnummer, stedsnavnsnummer og skrivemåtenummer skal sammen utgjøre en såkalt tematisk id som brukes av registerførere som opplslagsnummer. Identifikatoren ligner litt på Gnr/Bnr/Fnr.<br /><br />Skrivemåtenummer er et løpende nummer systemet gir skrivemåten som en identifikator. skrivemåtenummeret er kun unikt under et stedsnavnsnummer og kan ikke brukes om igjen for dette stedsnavnet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FellesTekst

#### FellesTekst (abstrakt)

abstrakt objekt som bærer en felles egenskaper som brukes på tekstobjektene

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geometri</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>kurve-geometri på tekstobjekter brukes slik: Punkt nr. 1 på kurva er objektets referansekoordinat. Punkt nr. 2 er tekstens plasseringskoordinat. Punkt nr. 3 angir retning på teksten. Dersom kurva inneholder flere koordinater angir disse forløp på teksten.</td>
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

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>streng</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>teksten som skal presenteres på kartet</td>
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
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td><strong>datafangstdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når objektet siste gang ble registrert/observert/målt i terrenget<br /><br />Merknad: I mange tilfeller er denne forskjellig fra Oppdateringsdato, da registrerte endringer kan bufres i en kortere eller lengre periode før disse legges inn i databasen.<br />Ved førstegangsregistrering settes Datafangstdato lik førsteDatafangstdato.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td><strong>tekstformatering</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>ulike egenskaper til brukt for å presentere teksten på mediumet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Tekstformatering</td>
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
      <td><strong>tekstformatering.tekstReferansepunkt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tekstens referansepunkt er det stedet på teksten som en tekstplassering refererer seg til.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TekstReferansePunkt</td>
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
      <td><strong>tekstformatering.tekstReferansepunkt.tekstReferansePunktNord</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>vertikal plassering av teksten.<br />Merknad: N50 Kartdata plasseres alltid teksten langs bunnlinja, dvs. TRNORD = 0</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TekstReferansePunktNord</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/tekstreferansepunktnord">https://register.geonorge.no/sosi-kodelister/kartdata/tekstreferansepunktnord</a></td>
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
      <td><strong>tekstformatering.tekstReferansepunkt.tekstReferansePunktØst</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>horisontal plassering av teksten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TekstReferansePunktØst</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/tekstreferansepunkt%C3%B8st">https://register.geonorge.no/sosi-kodelister/kartdata/tekstreferansepunkt%C3%B8st</a></td>
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
      <td><strong>tekstformatering.tegnavstand</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>avstanden mellom bokstavene i teksten, enhet er prosent</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>tekstformatering.skriftkode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>produktavhengig koplingsnøkkel mot presentasjonsinformasjon</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Skriftkode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/skriftkode">https://register.geonorge.no/sosi-kodelister/kartdata/skriftkode</a></td>
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
      <td><strong>tekstformatering.skrifttype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av den skrifttype eller font som skal benyttes. Default skrifttype er ARIAL</td>
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
      <td><strong>tekstformatering.referansemålestokk</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>egenskap som beskriver hvilken målestokk (oppgitt som målestokkstall) denne teksten er redigert for, både størrelse og<br />plassering. Kan benyttes for å velge hvilke tekster som skal tegnes ut i ulike målestokker.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>fulltekst</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnet i SSR som skal vises på kartet. Vil i de fleste tilfeller være likt Streng, men kan avvike dersom det av kartografiske hensyn bare vises deler av navnet e.l.</td>
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

#### PresentasjonTekst

PresentasjonTekst benyttes for høydetall som skal presenteres på kartet. Kodelista teksttype angir hva slags type objekt høydetall står til.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>teksttype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>kodeliste som angir hva slags type objekt teksten beskriver.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Teksttype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/kartdata/teksttype">https://register.geonorge.no/sosi-kodelister/kartdata/teksttype</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FellesTekst

### Kodelister

#### «CodeList» MediumSamferdsel

**Definisjon:** objektets beliggenhet i forhold til jordoverflaten

Eksempel:
Veg på bro, i tunnel, inne i et bygningsmessig anlegg, etc.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/mediumsamferdsel">https://register.geonorge.no/sosi-kodelister/kartdata/mediumsamferdsel</a></td>
    </tr>
  </tbody>
</table>

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/m%C3%A5lemetode">https://register.geonorge.no/sosi-kodelister/kartdata/m%C3%A5lemetode</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Nøyaktighet

**Definisjon:** punktstandardavviket i grunnriss for punkter samt tverravvik for linjer

Merknad:
Oppgitt i cm

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/n%c3%b8yaktighet">https://register.geonorge.no/sosi-kodelister/kartdata/n%c3%b8yaktighet</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» MediumHøyde

**Definisjon:** objektets beliggenhet i forhold til jordoverflaten

Eksempel:
Veg på bro, i tunnel, inne i et bygningsmessig anlegg, etc.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/mediumh%C3%B8yde">https://register.geonorge.no/sosi-kodelister/kartdata/mediumh%C3%B8yde</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Grensepunkttype

**Definisjon:** Angivelse av hva slags grensemerke som er brukt i terrenget.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/grensepunkttype">https://register.geonorge.no/sosi-kodelister/kartdata/grensepunkttype</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Kommunenummer

**Definisjon:** nummerering av kommuner i henhold til Statistisk sentralbyrå sin offisielle liste samt et utvalg av utgåtte numre

Merknad: Det presiseres at kommune alltid skal ha 4 sifre, dvs. eventuelt med ledende null. Kommune benyttes for kopling mot en rekke andre registre som også benytter 4 sifre.

Merknad 2: Modelleringsverktøyet Enterprise Architect håndterer ikke samiske tegn eller tankestrek. Det betyr at det vil forekomme avvik mellom definisjonene i denne lista i SOSI modellregister og definisjonene i offisielt standarddokument.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer">https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Lufthavntype

**Definisjon:** angivelse av type lufthavn

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/lufthavntype">https://register.geonorge.no/sosi-kodelister/kartdata/lufthavntype</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Trafikktype

**Definisjon:** angivelse av type rutetrafikk

Merknad: Benyttes i N50 Kartdata i forhold til luftfart

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/trafikktype">https://register.geonorge.no/sosi-kodelister/kartdata/trafikktype</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» IATAKode

**Definisjon:** unik kode for lufthavner.

Merknad1: Ikke alle lufthavner har IATA kode.
Merknad 2: Bare norske lufthavner er tatt med her.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/iatakode">https://register.geonorge.no/sosi-kodelister/kartdata/iatakode</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» ICAOKode

**Definisjon:** angivelse av lufthavn ved &lt;a href="C:\\wiki\\Kode"&gt;&lt;font color="#0000ff"&gt;&lt;u&gt;kode&lt;/u&gt;&lt;/font&gt;&lt;/a&gt; på fire &lt;a href="C:\\w\\index.php?title=Alfanumerisk&amp;action=edit&amp;redlink=1"&gt;&lt;font color="#0000ff"&gt;&lt;u&gt;alfanumeriske&lt;/u&gt;&lt;/font&gt;&lt;/a&gt; &lt;a href="C:\\wiki\\Tegn"&gt;&lt;font color="#0000ff"&gt;&lt;u&gt;tegn&lt;/u&gt;&lt;/font&gt;&lt;/a&gt;.

Merknad: Den første bokstaven tilordnes etter kontinent og angir et land eller en gruppe land på det samme kontinentet. Den andre bokstaven angir landet og de to siste angir lufthavn.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/icaokode">https://register.geonorge.no/sosi-kodelister/kartdata/icaokode</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Retningsenhet

**Definisjon:** enhet for retning

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet">https://register.geonorge.no/sosi-kodelister/kartdata/retningsenhet</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Retningsreferanse

**Definisjon:** referansesystem for retning

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse">https://register.geonorge.no/sosi-kodelister/kartdata/retningsreferanse</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» VannBredde

**Definisjon:** grov klassifikasjon av vassdrag etter gjennomsnittelig bredde over lengre strekninger


-- Definition - -
Rough classification of river system according to average width over longer sections.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/vannbredde">https://register.geonorge.no/sosi-kodelister/kartdata/vannbredde</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» BygningstypeKode

**Definisjon:** bygningstype sier hva bygningen er brukt til

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/bygningstypekode">https://register.geonorge.no/sosi-kodelister/kartdata/bygningstypekode</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Betjeningsgrad

**Definisjon:** beskrivelse av hvilke servicefunksjoner som er tilgengelige


-- Definition - -
description of which service functions are available

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/betjeningsgrad">https://register.geonorge.no/sosi-kodelister/kartdata/betjeningsgrad</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Hytteeier

**Definisjon:** eieren av en turisthytte


-- Definition - -
the owner of a cabin

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/hytteeier">https://register.geonorge.no/sosi-kodelister/kartdata/hytteeier</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Tilgjengelighet

**Definisjon:** beskriver om hytta er låst eller ulåst.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/tilgjengelighet">https://register.geonorge.no/sosi-kodelister/kartdata/tilgjengelighet</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» FlerLinjer

**Definisjon:** angivelse av antall kraftlinjer

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/flerlinjer">https://register.geonorge.no/sosi-kodelister/kartdata/flerlinjer</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Allmenningtype

**Definisjon:** nærmere inndeling av allmenninger

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/allmenningtype">https://register.geonorge.no/sosi-kodelister/kartdata/allmenningtype</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Verneform

**Definisjon:** verneformer som sorterer under forskjellig lovverk og restriksjoner

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/verneform">https://register.geonorge.no/sosi-kodelister/kartdata/verneform</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Skytefeltstatus

**Definisjon:** angir skytefeltstatus

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/skytefeltstatus">https://register.geonorge.no/sosi-kodelister/kartdata/skytefeltstatus</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» TypeVeg

**Definisjon:** type veg (FormOfWay).

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/typeveg">https://register.geonorge.no/sosi-kodelister/kartdata/typeveg</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Vegkategori

**Definisjon:** kategorisering som angir på hvilket nivå vegmyndigheten for strekningen ligger

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/vegkategori">https://register.geonorge.no/sosi-kodelister/kartdata/vegkategori</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Vegfase

**Definisjon:** angir vegens fase i livet

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/vegfase">https://register.geonorge.no/sosi-kodelister/kartdata/vegfase</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Motorvegtype

**Definisjon:** klassifisering av veger etter grad av vilkår med hensyn til f.eks. fart, avkjøringer/kryss og antall kjørefelt

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/motorvegtype">https://register.geonorge.no/sosi-kodelister/kartdata/motorvegtype</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» RuteMerking

**Definisjon:** forteller om det er merking  langs en sti, løype, veg, sykkelvei mv

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/rutemerking">https://register.geonorge.no/sosi-kodelister/kartdata/rutemerking</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Vedlikeholdsansvarlig

**Definisjon:** institusjon eller andre som har ansvar for vedlikehold av rute

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/vedlikeholdsansvarlig">https://register.geonorge.no/sosi-kodelister/kartdata/vedlikeholdsansvarlig</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Vegsperringtype

**Definisjon:** angir type vegsperring


-- Definition - -
indicates type of roadblock

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/vegsperringtype">https://register.geonorge.no/sosi-kodelister/kartdata/vegsperringtype</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Jernbanetype

**Definisjon:** klassifisering av jernbaneanlegg i hht. konstruksjon/dimensjonering

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/jernbanetype">https://register.geonorge.no/sosi-kodelister/kartdata/jernbanetype</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Jernbanestatus

**Definisjon:** definerer status for drift på en banestrekning

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/jernbanestatus">https://register.geonorge.no/sosi-kodelister/kartdata/jernbanestatus</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Sporantall

**Definisjon:** antall jernbanespor

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/sporantall">https://register.geonorge.no/sosi-kodelister/kartdata/sporantall</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Navneobjekthovedgruppe

**Definisjon:** hovedgruppene følger i hovedsak Inspire "NamedPlaceTypeValue", men populatedPlace og building er samlet under bebyggelse og hydrography er delt mellom sjø og ferskvann.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjekthovedgruppe">https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjekthovedgruppe</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Navneobjektgruppe

**Definisjon:** inndeling i kategorier under hver hovedgruppe.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjektgruppe">https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjektgruppe</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Navneobjekttype

**Definisjon:** stedets navneobjekttype er en underinndeling av navneobjektgruppene som igjen er inndeling av navneobjekthovedgruppene.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjekttype">https://register.geonorge.no/sosi-kodelister/stedsnavn/navneobjekttype</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» SpråkKode

**Definisjon:** subsett av ISO 639-3 som inneholder trebokstavs-koder de språkene som trengs for å konvertere innholdet fra SSR. Kodelisten kan utvides ved behov etter produksjonssetting.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/stedsnavn/spr%C3%A5kkode">https://register.geonorge.no/sosi-kodelister/stedsnavn/spr%C3%A5kkode</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» SpråkprioriteringKode

**Definisjon:** kodeliste som angir visningsrekkefølgen til stedsnavn på forskjellig språk.

Det er de første fem verdiene i kodene (de norske språkene) som varierer mellom kodene, ellers er det lik (alfabetisk i forhold til ISO-kodeverdien) rekkefølge på språkene som ikke er aktuelle for behandling etter lov om stadnamn.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/stedsnavn/spr%C3%A5kprioriteringkode">https://register.geonorge.no/sosi-kodelister/stedsnavn/spr%C3%A5kprioriteringkode</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» TekstReferansePunktNord

**Definisjon:** vertikal plassering av teksten

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/tekstreferansepunktnord">https://register.geonorge.no/sosi-kodelister/kartdata/tekstreferansepunktnord</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» TekstReferansePunktØst

**Definisjon:** horisontal plassering av teksten

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/tekstreferansepunkt%C3%B8st">https://register.geonorge.no/sosi-kodelister/kartdata/tekstreferansepunkt%C3%B8st</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Skriftkode

**Definisjon:** koblingsnøkkel mot presentasjonsinformasjon. Forslag til presentasjon av stedsnavn og høydetall basert på skriftkoder. Presentasjonskoden er basert på hovedkartserien 1:50 000/M711 produsert av Kartverket. Kartverket har egne fonter, men oversatt til TimesNewRoman slik at enhver kan presentere dataene tilnærmet presentasjonen til Kartverket. Ved bruk av ESRI FGDB filformat ligger fontinformasjon allerede inne i egenskapstabellen.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/skriftkode">https://register.geonorge.no/sosi-kodelister/kartdata/skriftkode</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Teksttype

**Definisjon:** beskriver hva teksten står til.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/kartdata/teksttype">https://register.geonorge.no/sosi-kodelister/kartdata/teksttype</a></td>
    </tr>
  </tbody>
</table>
