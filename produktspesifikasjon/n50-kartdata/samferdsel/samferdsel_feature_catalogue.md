#### Sti

tydelig tråkk i terrenget som er markert gjennom års bruk eller tilrettelagt for ferdsel til fots<br /><br /><br />-- Definition --<br />distinct path in the terrain which has become pronounced through many years' use or prepared for general travel on foot.

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
      <td>forløp som følger objektets sentrale del<br /><br />-- Definition --<br />cource follwed by the central part of the object</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
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
      <td><strong>merking</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>om stien er merket eller ikke<br /><br />-- Definition --<br />whether the trail is marked or not Kommentar-tillegg Kommentar-tillegg Kommentar-tillegg Kommentar-tillegg Kommentar-tillegg</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>RuteMerking</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Merket, uspesifisert<br />- Ikke merket</td>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Alta og Omegn Turlag<br />- Aust-Agder TF<br />- Bergen og Hordaland Turlag<br />- Bodø og Omegns Tf<br />- Brurskanken Turlag<br />- Brønnøysund Turlag<br />- DNT Drammen og Omegn<br />- DNT Gjøvik og Omegn<br />- DNT Gudbrandsdalen<br />- DNT Indre Østfold<br />- DNT Lillehammer<br />- DNT Nedre Glomma<br />- DNT Nord-Østerdal<br />- DNT Oslo og Omegn<br />- DNT Sør<br />- DNT Valdres<br />- DNT Vansjø<br />- Engerdal og Trysil Turlag<br />- Finnskogen Tf<br />- Flekkefjord og Oplands Tf<br />- Hadeland Turlag<br />- Hamar og Hedemarken Tf<br />- Hammerfest og Omegn Turlag<br />- Harstad Turlag<br />- Haugesund Tf<br />- Hemnes Tf<br />- Holmestrand og Omegn Tf<br />- Horten og Omegn Tf<br />- Kongsberg og Omegns Tf<br />- Kristiansund og Nordmøre Tf<br />- Larvik og Omegns Tf<br />- Lofoten Turlag<br />- Molde og Romsdals Tf<br />- Narvik og Omegn Tf<br />- Nord-Salten Turlag<br />- Nord-Trøndelag Tf<br />- Nordkapp og Omegn Tf<br />- Notodden Turlag<br />- Odal Turlag<br />- Rana Tf<br />- Rena og Omegn Tf<br />- Ringerikes Tf<br />- Sandefjord og Oplands Tf<br />- Sandnessjøen og Omegn Tf<br />- Sogn og Fjordane Turlag<br />- Stavanger Tf<br />- Sulitjelma og Omegn Tf<br />- Sør-Varanger Turlag<br />- Telemark Tf<br />- Tistedalen Friluftslag<br />- Troms Turlag<br />- Trondhjems Tf<br />- Tvedestrand og Vegårdshei Turlag<br />- Tønsberg og Omegn Tf<br />- Varangerhalvøya Turlag<br />- Vesterålen Turlag<br />- Voss Utferdslag<br />- Ålesund-Sunnmøre Tf<br />- Andre<br />- Ukjent</td>
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
      <td><strong>rutenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummer på samferdsels- eller friluftsrute</td>
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

#### Veglenke (abstrakt)

abstrakt supertype for objekttyper som representerer lenker i veinettet<br /><br /><br />-- Definition --<br />segment of the road network

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
      <td>forløp som følger objektets sentrale del<br /><br />-- Definition --<br />cource follwed by the central part of the object</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
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
      <td><strong>vegident</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sammensatt identifikator for en vegrute<br /><br />--Definition--<br />compound identifier for a road route</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Vegident</td>
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
      <td><strong>vegident.vegkategori</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir hvilken type veg veglenken beskriver<br /><br />-- Definition --<br />indicates which type of road the road segment describes</td>
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
      <td>- Europaveg<br />- Riksveg<br />- Fylkesveg<br />- Kommunal veg<br />- Privat veg</td>
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
      <td><strong>vegident.vegstatus</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir veglenkens status<br /><br />-- Definition --<br />indicates the status of the road segment</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>VegStatus</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Vedtatt veg<br />- Eksisterende veg</td>
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
      <td><strong>vegident.vegnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir nummeret til en vegrute<br /><br />-- Definition --<br />indicates the number of a road route</td>
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
      <td><strong>rutenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummer på samferdsels- eller friluftsrute</td>
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
      <td>- Grader (360 graders deling) – 360 graders deling med positiv retning med sola<br />- Gon (400 graders deling) – 400 graders deling med positiv retning med sola<br />- Radianer – Radianer med positiv retning med sola</td>
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
      <td>- Sant nord – (default)<br />- Magnetisk nord<br />- Lokal</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Jernbanepunkt

#### Jernbanepunkt (abstrakt)

abstrakt supertype for objekttyper som representerer punktobjekter i eller ved jernbanenettet.<br /><br /><br />-- Definition --<br />abstract supertype for points in, or connected to, the railway network.

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
      <td>sted som objektet eksisterer på<br /><br />-- Definition --<br />location where the object exists</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

#### Jernbanelenke (abstrakt)

abstrakt supertype for objekttyper som representerer lenker i jernbanenettet.<br /><br /><br />-- Definition --<br />abstract supertype for links in the railway network.

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
      <td>forløp som følger objektets sentrale del Kommentar-tillegg Kommentar-tillegg Kommentar-tillegg Kommentar-tillegg</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
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
      <td>beskrivelse av jernbanen</td>
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
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Jernbanetype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Jernbane<br />- Tunnelbane<br />- Museumsbane<br />- Nedlagt</td>
    </tr>
  </tbody>
</table>

#### Barmarksløype

tradisjonelle kjørespor/traktorveger i utmark hvor motorisert ferdsel på barmark er tillatt for allmennheten, etter forskrift gitt av Fylkesmannen<br /><br /><br />-- Definition --<br />traditional driving tracks/tractor roads on uncultivated land where motor traffic for the general public is permitted on snowless ground in accordance with the regulations laid down by the County governor

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
      <td>forløp som følger objektets sentrale del<br /><br />-- Definition --<br />cource follwed by the central part of the object</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
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
      <td><strong>rutenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummer på samferdsels- eller friluftsrute</td>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Enkeltspor<br />- Flere spor</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Jernbanelenke

#### Traktorveg

veg som hele året (eller deler av året) ikke egner seg for vanlig bilkjøring, men som er farbar med traktor<br /><br /><br />-- Definition --<br />road not suitable for ordinary year-round (or only seasonal) car traffic, but which is passable by tractor

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
      <td>forløp som følger objektets sentrale del<br /><br />-- Definition --<br />cource follwed by the central part of the object</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
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
      <td><strong>rutenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummer på samferdsels- eller friluftsrute</td>
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

#### Bilferjestrekning

strekning trafikert av bilferjer som del av vegnettet<br /><br /><br />-- Definition --<br />route serviced by car ferries as part of the road network

Egenskaper

(ingen)

Relasjoner

**Arv**
Veglenke

#### GangSykkelveg

bane for fotgjengere og syklister langs eller nær en kjøreveg<br /><br /><br />-- Definition --<br />lane for pedestrians and cyclists along or near a road

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
      <td>forløp som følger objektets sentrale del<br /><br />-- Definition --<br />cource follwed by the central part of the object</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
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
      <td><strong>rutenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummer på samferdsels- eller friluftsrute</td>
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

#### VegSenterlinje

linje midt mellom vegkanter.<br /><br /><br />-- Definition --<br />line mid-way between edges of road

Egenskaper

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
      <td>klassifisering av type veg</td>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Ikke motorveg – Vanlig veg<br />- Motortrafikkveg – motortrafikkveg. Motortrafikkveger kan være tofelts-, trefelts- eller flerfeltsveger, med eller uten midtdeler eller midtrekkverk, men følgende krav skal være oppfylt:
• Vegen skal vare avkjørselsfri.
• Vegkryss skal være planskilte.
• Det skal finnes et tilfredsstillende parallellvegnett for de kjøretøy og trafikantgruppene som ikke er tillatt på motortrafikkvegen.
Skiltet med skilt 503.
Tidligere motorveg klasse B.<br />- Motorveg – veg med fire eller flere kjørefelt, midtdeler, planskilte kryss og uten direkte tilknytning til eiendommene langs vegen. Skiltet med skilt 502. Tidligere motorveg klasse A.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Veglenke

#### RuteGenerell (abstrakt)

rute for ferdsel generelt<br /><br /><br />-- Definition --<br />route for general ??traffic/travel

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
      <td>forløp som følger objektets sentrale del<br /><br />-- Definition --<br />cource follwed by the central part of the object</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
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
      <td><strong>rutenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummer på samferdsels- eller friluftsrute</td>
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

#### Passasjerferjestrekning

båtrute beregnet på person- og varetransport<br /><br /><br />-- Definition --<br />ferry route for transportation of people and goods

Egenskaper

(ingen)

Relasjoner

**Arv**
RuteGenerell

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
      <td>forløp som følger objektets sentrale del<br /><br />-- Definition --<br />cource follwed by the central part of the object</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
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
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Vegsperringtype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Låst bom</td>
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
      <td>- Grader (360 graders deling) – 360 graders deling med positiv retning med sola<br />- Gon (400 graders deling) – 400 graders deling med positiv retning med sola<br />- Radianer – Radianer med positiv retning med sola</td>
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
      <td>- Sant nord – (default)<br />- Magnetisk nord<br />- Lokal</td>
    </tr>
  </tbody>
</table>

### Kodelister

#### «Enumeration» RuteMerking

**Definisjon:** forteller om det er merking  langs en sti, løype, veg, sykkelvei mv

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
      <td>Merket, uspesifisert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ikke merket</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Vedlikeholdsansvarlig

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
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

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
      <td>Alta og Omegn Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Aust-Agder TF</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bergen og Hordaland Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bodø og Omegns Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Brurskanken Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Brønnøysund Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Drammen og Omegn</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Gjøvik og Omegn</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Gudbrandsdalen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Indre Østfold</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Lillehammer</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Nedre Glomma</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Nord-Østerdal</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Oslo og Omegn</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Sør</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Valdres</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DNT Vansjø</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Engerdal og Trysil Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Finnskogen Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flekkefjord og Oplands Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hadeland Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hamar og Hedemarken Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hammerfest og Omegn Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Harstad Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Haugesund Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hemnes Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Holmestrand og Omegn Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Horten og Omegn Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kongsberg og Omegns Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kristiansund og Nordmøre Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Larvik og Omegns Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lofoten Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Molde og Romsdals Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Narvik og Omegn Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nord-Salten Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nord-Trøndelag Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nordkapp og Omegn Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Notodden Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Odal Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rana Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rena og Omegn Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ringerikes Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sandefjord og Oplands Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sandnessjøen og Omegn Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sogn og Fjordane Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stavanger Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sulitjelma og Omegn Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sør-Varanger Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Telemark Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tistedalen Friluftslag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Troms Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Trondhjems Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tvedestrand og Vegårdshei Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tønsberg og Omegn Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Varangerhalvøya Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vesterålen Turlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Voss Utferdslag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ålesund-Sunnmøre Tf</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Andre</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Vegkategori

**Definisjon:** angir hvilken type veg veglenken beskriver


-- Definition - -
indicates which type of road the road segment describes

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
      <td>Europaveg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Riksveg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fylkesveg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kommunal veg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Privat veg</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» VegStatus

**Definisjon:** angir veglenkens status


-- Definition - -
indicates the status of the road segment

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
      <td>Vedtatt veg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Eksisterende veg</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Retningsenhet

**Definisjon:** enhet for retning

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
      <td>Grader (360 graders deling)</td>
      <td>360 graders deling med positiv retning med sola</td>
      <td></td>
    </tr>
    <tr>
      <td>Gon (400 graders deling)</td>
      <td>400 graders deling med positiv retning med sola</td>
      <td></td>
    </tr>
    <tr>
      <td>Radianer</td>
      <td>Radianer med positiv retning med sola</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Retningsreferanse

**Definisjon:** referansesystem for retning

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
      <td>Sant nord</td>
      <td>(default)</td>
      <td></td>
    </tr>
    <tr>
      <td>Magnetisk nord</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lokal</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Jernbanetype

**Definisjon:** klassifisering av jernbaneanlegg i hht. konstruksjon/dimensjonering. Tunnelbane dekker også metro- og forstadsbaner.


-- Definition --
classification of railway facility in accordance with design/dimensioning


&lt;font color="#008000"&gt;-- INSPIRE --&lt;/font&gt;
&lt;font color="#008000"&gt;Maps to RailwayTypeValue&lt;/font&gt;

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
      <td>Jernbane</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tunnelbane</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Museumsbane</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nedlagt</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Sporantall

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
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

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
      <td>Enkeltspor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flere spor</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Motorvegtype

**Definisjon:** klassifisering av type veg

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
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

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
      <td>Ikke motorveg</td>
      <td>Vanlig veg</td>
      <td></td>
    </tr>
    <tr>
      <td>Motortrafikkveg</td>
      <td>motortrafikkveg. Motortrafikkveger kan være tofelts-, trefelts- eller flerfeltsveger, med eller uten midtdeler eller midtrekkverk, men følgende krav skal være oppfylt:
• Vegen skal vare avkjørselsfri.
• Vegkryss skal være planskilte.
• Det skal finnes et tilfredsstillende parallellvegnett for de kjøretøy og trafikantgruppene som ikke er tillatt på motortrafikkvegen.
Skiltet med skilt 503.
Tidligere motorveg klasse B.</td>
      <td></td>
    </tr>
    <tr>
      <td>Motorveg</td>
      <td>veg med fire eller flere kjørefelt, midtdeler, planskilte kryss og uten direkte tilknytning til eiendommene langs vegen. Skiltet med skilt 502. Tidligere motorveg klasse A.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Vegsperringtype

**Definisjon:** angir type vegsperring


-- Definition - -
indicates type of roadblock

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
      <td>Låst bom</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
