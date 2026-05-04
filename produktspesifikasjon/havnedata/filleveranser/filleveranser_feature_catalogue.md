#### Havneområde

Havn er et avgrenset område som inneholder kai/kaier tilknyttet land- og sjøarealer som er tilrettelagt for overføring av gods, personer eller lignende mellom land og sjø.<br />Havneområde kjennetegnes ved at de har en UNLOCODE tilknyttet seg, og innenfor området må det være minst én kai og én kaifront.<br />Havneområdet kan inneholde mange havneanlegg, mange kaier og andre objekter.

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
      <td>Polygon som viser geografisk utstrekning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td>Opsjonelt representasjonspunkt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>forvaltesAv</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Felt for å angi hvem som forvalter eller administrerer havneområdet.</td>
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
HavnId

**Assosiasjoner**
HavneområdeGrense – rolle: avgrensning – kardinalitet: 0..*

#### Havneanlegg

Med havneanlegg menes arealer, bygninger, innretninger og annen infrastruktur som brukes i havnevirksomhet eller havneformål. Herunder: kaier, terminalbygninger, laste-, losse- og omlastningsinnretninger og lager- og administrasjonsbygninger.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>eier</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Eier av havneanlegget.</td>
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
      <td><strong>eierskap</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Felt for å angi type eierskap.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Eierskap</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/eierskap">https://register.geonorge.no/sosi-kodelister/havnedata/eierskap</a><br />- Stat – Statlig eierskap.<br />- Privat – Privat eierskap.<br />- Fylke – Fylkeskommunalt eierskap.<br />- Annet – Annen type egenskap.<br />- Kommune – Kommunalt eierskap.<br />- Offentlig – Offentlig eierskap.<br />- Ukjent – Ukjent eierskap.</td>
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
      <td><strong>forvaltesAv</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Felt for å angi hvem havneanlegget forvaltes av.</td>
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
      <td><strong>ISPSHavneanlegg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Egenskaper spesifikke for ISPSHavneanlegg.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>ISPSHavneanlegg</td>
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
      <td><strong>ISPSHavneanlegg.portFacilityNrIMO</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Lokasjonskode for ISPS-området. Består av UNLOCODE, samt en 4-siffret tallkode.</td>
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
      <td><strong>ISPSHavneanlegg.sikringstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver sikring/tilgang til havnesikkerhetsområdet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Sikringstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/sikringstype">https://register.geonorge.no/sosi-kodelister/havnedata/sikringstype</a><br />- Permanent sikret – Havnesikkerhetsområdet som er permanent sikret.<br />- Sikret ved anløp – Havnesikkerhetsområde som kun er sikret ved anløp av skip.<br />- Annen sikring – Annen type sikring.</td>
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
      <td><strong>ISPSHavneanlegg.statusGodkjenning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Felt for å angi status på ISPS godkjenning.</td>
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
      <td><strong>ISPSHavneanlegg.sikkerhetsbarriere</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Attributt for å spesifisere om et havnesikkerhetsområde ikke har inngjerding eller annen form for sikkerhetsbarriere.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
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
      <td><strong>ISPSHavneanlegg.kontaktinformasjonPFSO</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kontaktinformasjon til PFSP eller assisterende PFSO på det aktuelle ISPS-området.</td>
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
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Polygon som viser geografisk utstrekning.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td>Opsjonelt representasjonspunkt for området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
HavneanleggId

**Assosiasjoner**
HavneanleggGrense – rolle: avgrensning – kardinalitet: 0..*

#### HavnegjerdeInngang

Inngang, åpning eller innkjørsel til området som er avsperret av Havnegjerde.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>avsperringstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste for å angi type avsperring for inngangen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Avsperringstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/avsperringstype">https://register.geonorge.no/sosi-kodelister/havnedata/avsperringstype</a><br />- Manuell port – Manuell port som avsperring av inngang.<br />- Manuell bom – Manuell bom som avsperring av inngang.<br />- Elektrisk bom – Elektrisk bom som avsperring av inngang.<br />- Annen – Annen type avsperring av inngang.<br />- Ukjent – Ukjent type avsperring av inngang.<br />- Dør – Dør som tilkomst eller avsperring av inngang til område avgrenset av havnegjerde.<br />- Rotasjonsport – Roterende port som tillater passering av én person om gangen. Som adgangskontroll for personer inn/ut av et område.<br />- Sluse – Sluse for gjennomslipp av en person om gangen. Som adgangskontroll for personer inn/ut av et område.<br />- Personsperre – Adgangssperrer for personer inn/ut av et område.<br />- Skyveport – Port som åpnes ved å skyve porten til siden, parallellt med gjerdet.<br />- Foldeport – Port som åpnes ved å folde seg sammen.<br />- Heveport – Port som ånes ved å heve seg vertikalt opp, på samme måte som en veibom åpnes.<br />- Nedleggbar port – Port som kan legges ned for åpning av bred transport eller lignende.<br />- Kombinasjonsport – Port som har en kombinasjon av flere åpningsmekanismer, f.eks. en kombinasjon av skyveport med et spesialfelt med nedleggbar port i midten.<br />- Svingport – Svingbar port som åpnes som en grind.</td>
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
      <td><strong>åpningstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste for å spesifisere åpningsmekanisme av port, bom eller annet som avsperrer havnesikkerhetsområde.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Åpningstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/apningstype">https://register.geonorge.no/sosi-kodelister/havnedata/apningstype</a><br />- Fjernstyrt – Fjernstyrt åpning av port eller veibom.<br />- Må betjenes – Åpning av port eller veibom som krever betjening på stedet.<br />- Annet – Annen type åpningsmekanisme.<br />- Ukjent – Ukjent type åpningsmekanisme.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Havnegjerde

#### Havnegjerde

Gjerde eller annen barriere. Følger ofte Havnesikkerhetsområde, men brukes ikke som avgrensning. Havnesikkerhetsområde avgrenses av HavnesikkerhetsområdeGrense.<br />Havnegjerde vil også ofte være kartlagt i FKB-BygnAnlegg som AnnetGjerde, mur e.l. I så fall bør disse objektene ha sammenfallende geometri.

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
      <td>Forløp som følger overgang mellom ulike fenomener.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>periode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Periode havnegjerdet er satt opp. Brukes i tilfeller der havnegjerde er kun satt opp i visse tidsrom eller deler av året.  Attributt trengs ikke benyttes ved permanent gjerde.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Periode</td>
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
      <td><strong>periode.mndFra</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Måned fra.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Måned</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/maned">https://register.geonorge.no/sosi-kodelister/havnedata/maned</a><br />- Januar<br />- Februar<br />- Mars<br />- April<br />- Mai<br />- Juni<br />- Juli<br />- August<br />- September<br />- Oktober<br />- November<br />- Desember</td>
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
      <td><strong>periode.mndTil</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Måned til.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Måned</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/maned">https://register.geonorge.no/sosi-kodelister/havnedata/maned</a><br />- Januar<br />- Februar<br />- Mars<br />- April<br />- Mai<br />- Juni<br />- Juli<br />- August<br />- September<br />- Oktober<br />- November<br />- Desember</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
HavneanleggId

#### Drivstofftilkobling

Tilkoblingspunkt for drivstoff på kaia.

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
      <td>Posisjon</td>
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
      <td><strong>drivstofftype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Type drivstoff.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Drivstofftype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/drivstofftype">https://register.geonorge.no/sosi-kodelister/havnedata/drivstofftype</a><br />- Diesel – Mulighet for å fylle diesel.<br />- Bensin – Mulighet for å fylle bensin.<br />- Annen – Mulighet for å fylle annen type drivstoff.
Angi ved bruk av informasjonsegenskapen.<br />- LNG – Mulighet for å fylle LNG.<br />- Bensin, diesel – Mulighet for å fylle bensin og diesel.</td>
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
      <td><strong>kapasitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kapasitet til fylling av drivstoff angitt i antall m3/time.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>mobilitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Egenskap for å anngi om drivstoffpunktet er fast montert eller flyttbart (mobilt drivstoffpunkt i form av en tankbil eller lignende).<br /><br />For mobile tilkoblingspunkt er det vanskelig/meningsløst å stedfeste punktet nøyaktig. Punktet plasseres da på et passelig representativt punkt og gis en kvalitetskode som angir stor usikkerhet i innmåling.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
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
      <td><strong>tilgangstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste for å spesifisere hvem som har mulighet til å benytte punktet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Tilgangstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype">https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype</a><br />- Annet – Annen tilgang.<br />- Leietager – Tilgang for leietager.<br />- Havnedrift – Tilgang for havnedrift.<br />- Alle – Tilgang for alle.<br />- Godsfartøy – Tilgang for godsfartøy.<br />- Alle skip – Tilgang for alle typer skip eller fartøy.<br />- Fiskebåter – Tilgang for fiskebåter.<br />- Fritidsbåter – Tilgang for fritidsbåter.<br />- Cruise fartøy – Tilgang for cruisefartøy.<br />- Annet fartøy – Tilgang for andre fartøy.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
ObjektId

#### ObjektId (abstrakt)

Abstrakt objekt som holder egenskaper for unik identifisering av objekt på kaien.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>objektLøpenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Unikt løpenummer for identifisering av det enkelte objekt på kaien, i form av nummer/tekst.</td>
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
KaiId

#### Kran

Innretning for å løfte eller flytte tunge gjenstander, og hører til på kaien/havnen.

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
      <td>Posisjon</td>
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
      <td><strong>krantype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Krantype.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Krantype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/krantype">https://register.geonorge.no/sosi-kodelister/havnedata/krantype</a><br />- Annen – Annen type kran.<br />- Mobilkran – Kran som er montert på et kjøretøy.<br />- Skinnegående kran – Kran som går på skinner.<br />- Bulk kran – Kran for bulkhåndtering, med integrert gripe for løfting av bulk masser.<br />- Tranverskran – Kran som kan bevege seg i tre plan (to horisontale og ett vertikalt) og består av en kranbro, med en eller flere løpekatter med et heismaskineri.<br />- Havnekran – Kran som tilhører havnen. Vanligvis montert på kaien.<br />- Portalkran – Kran formet som en portal, med en horisontal bærebjelke. Gantry kraner og stablekraner er portalkraner.<br />- Reachstacker – Kjøretøy for løfting og transport av containere.<br />- Svingkran – Svingbar kran</td>
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
      <td><strong>maksbelastning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maks løfteevne for krana angitt i tonn (ved liten arm).</td>
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
      <td><strong>rekkevidde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Rekkevidden til kranen, ut fra kaifronten, i antall meter.</td>
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
      <td><strong>maksbelastningRekkevidde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maks løfteevne for krana ved maksimal arm/rekkevidde angitt i antall tonn.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>kranspesifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Spesifikasjon for kranen.</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>mobilitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Egenskap for å angi om en krane er fastmontert eller flyttbar (mobil).<br />Fastmontert krane står i et fast punkt på kaia, mens mobile kraner kan flyttes. Skinnegående kraner eller andre semi-mobile kraner angis som mobile.<br />For mobile kraner registreres punktet som en skjønnsmessig representativ koordinat for krana.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
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
      <td><strong>energikilde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste for å spesifisere energikilden til kranen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Energikilde</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/energikilde">https://register.geonorge.no/sosi-kodelister/havnedata/energikilde</a><br />- Diesel – Diesel som energikilde.<br />- Elektrisk – Elektrisk tilkobling som energikilde.<br />- Batteri – Batteri som energikilde.<br />- Annen – Annen energikilde.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
ObjektId

#### Slipp

Skinnegående bane eller et forseggjort opptrekk som fartøy kan hales opp ved landsetting, fra flytende posisjon og opp på tørt land. Skråplanet går vanligvis ut og ned i vannet.

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
      <td>Polygon som viser geografisk utstrekning.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td>Opsjonelt representasjonspunkt for området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>kaidekketype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskrivelse av materialebruk på dekket av slippen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kaidekketype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/kaidekketype">https://register.geonorge.no/sosi-kodelister/havnedata/kaidekketype</a><br />- Asfalt – Asfaltdekke<br />- Betong – Betongdekke<br />- Belegningsstein, heller – Dekke av belegningsstein eller heller.<br />- Tredekke<br />- Annet – Annet materiale.</td>
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
      <td>Navn på slippen.</td>
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
      <td><strong>spesifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Attributt for å spesifisere opptrekksmekanisme (vinsj, skinner el.) eller annen relevant informasjon.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>høydeSjøkartnull</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angitt høyde på høyeste del av slippen, i meter over vannet. Egenskapen høyde angis i forhold til sjøkartnull (dvs. høyder over lokal LAT-verdi) dersom ikke annet er angitt.</td>
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
      <td><strong>maksLengdeFartøy</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal lengde på fartøy som slippen kan ta. Angis i meter.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>tilgangstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste for å spesifisere hvem som har mulighet til å benytte slippen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Tilgangstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype">https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype</a><br />- Annet – Annen tilgang.<br />- Leietager – Tilgang for leietager.<br />- Havnedrift – Tilgang for havnedrift.<br />- Alle – Tilgang for alle.<br />- Godsfartøy – Tilgang for godsfartøy.<br />- Alle skip – Tilgang for alle typer skip eller fartøy.<br />- Fiskebåter – Tilgang for fiskebåter.<br />- Fritidsbåter – Tilgang for fritidsbåter.<br />- Cruise fartøy – Tilgang for cruisefartøy.<br />- Annet fartøy – Tilgang for andre fartøy.</td>
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
      <td><strong>slippKapasitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Løftekapasitet til slippen, angitt i tonn.</td>
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
      <td><strong>maksBreddeFartøy</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal bredde på fartøyet som slippen kan ta. Angis i meter.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>maksDyptgåendeFartøy</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal dyptgående på fartøyet som slippen kan ta. Angis i meter.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>kranKapasitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kapasitet til kran tilknyttet slipp, angitt i tonn.</td>
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
KaiId

**Assosiasjoner**
SlippGrense – rolle: avgrensning – kardinalitet: 0..*

#### Tømmestasjon

Tømmestasjon eller punkt for tømming av væske (avløpsvann, septik eller tilsvarende).

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>kapasitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kapasitet til tømming, angitt i antall m3/time.</td>
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
      <td><strong>kumnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>ID-merking av kummer. Kan tas fra havnas eget merkesystem eller kommunens SID-nr.</td>
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
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Posisjon</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>tilkoblingsdimensjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Størrelse/dimensjon på rørene som skal kobles sammen.</td>
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
      <td><strong>avløpstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskrivelse av hva slags tømming/avløpstype som er tilgjengelig.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Avløpstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/avlopstype">https://register.geonorge.no/sosi-kodelister/havnedata/avlopstype</a><br />- Gråvann – Anlegg for mottak av gråvann fra båt.<br />- Svartvann – Anlegg for mottak av svartvann (vann som inneholder olje e.l. og må håndteres spesielt)<br />- Annen – Annen type for avløp.<br />- Septik – Tømmestasjon med mottak for septik/klokakk.</td>
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
      <td><strong>mobilitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Egenskap for å anngi om tømmestasjonen er fast montert eller flyttbart (i form av en tankbil eller lignende).<br /><br />For mobile tilkoblingspunkt er det vanskelig/meningsløst å stedfeste punktet nøyaktig. Punktet plasseres da på et passelig representativt punkt og gis en kvalitetskode som angir stor usikkerhet i innmåling.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
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
      <td><strong>tilgangstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste for å spesifisere hvem som har mulighet til å benytte tømmestasjonen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Tilgangstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype">https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype</a><br />- Annet – Annen tilgang.<br />- Leietager – Tilgang for leietager.<br />- Havnedrift – Tilgang for havnedrift.<br />- Alle – Tilgang for alle.<br />- Godsfartøy – Tilgang for godsfartøy.<br />- Alle skip – Tilgang for alle typer skip eller fartøy.<br />- Fiskebåter – Tilgang for fiskebåter.<br />- Fritidsbåter – Tilgang for fritidsbåter.<br />- Cruise fartøy – Tilgang for cruisefartøy.<br />- Annet fartøy – Tilgang for andre fartøy.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
ObjektId

#### FlytedokkGrense

Avgrensning av Flytedokk.

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
      <td>Forløp som følger overgang mellom ulike fenomener.</td>
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

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### HavneanleggId (abstrakt)

Abstrakt objekt som holder egenskaper for unik identifisering av et havneanlegg. Egenskapene arves ned til øvrige objektklasser i Havnedata.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>ISPS</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Boolsk verdi (JA/NEI) om angir om havneanlegget er et ISPS Havneanlegg.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
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
      <td><strong>havneanleggNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navn på havneanlegg. Navn bør stemme overens med SafeSeaNet.</td>
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
      <td><strong>havneanleggId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Unik identifisering av det enkelte havneanlegg.</td>
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
HavnId

#### Tørrdokk

Et basseng stort nok til at skip kan seile ut og inn. Bunnen ligger lavere enn havnivået og innløpet kan lukkes med porter. Vann kan pumpes ut, slik skip kan stå tørt, for vedlikehold og reperasjon.

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
      <td>Polygon som viser geografisk utstrekning.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td>Opsjonelt representasjonspunkt for området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>maksFartøyBredde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal bredde på fartøyet som dokken kan romme. Angis i meter.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>maksFartøyLengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal lengde på fartøyet som dokken kan romme. Angis i meter.</td>
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
      <td><strong>maksFartøyDyptgående</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal dyptgående på fartøyet som dokken kan romme. Angis i meter.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>løftekapasitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal løftekapasitet, angitt i tonn.</td>
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
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navn på tørrdokken.</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
HavneanleggId

**Assosiasjoner**
TørrdokkGrense – rolle: avgrensning – kardinalitet: 0..*

#### Toalett

Offentlig toalett.

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
      <td>Posisjon</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
ObjektId

#### ForvaltningsområdeGrense

Avgrensning av forvaltningsområde.

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
      <td>Forløp som følger overgang mellom ulike fenomener.</td>
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

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### SlippGrense

Avgrensning av Slipp.

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
      <td>forløp som følger overgang mellom ulike fenomener.</td>
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

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### TørrdokkGrense

Avgrensning av Tørrdokk.

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
      <td>forløp som følger overgang mellom ulike fenomener.</td>
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

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### HavnId (abstrakt)

Abstrakt objekt som holder egenskaper for unik identifisering av en havn. Egenskapene arves ned til øvrige objektklasser i Havnedata.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>havn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Stedsnavn på havnen som har blitt tildelt en UNLOCODE. Navnet må samsvare med UNLOCODE.</td>
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
      <td><strong>UNLOCODE</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Lokaliseringskode fra UNLOCODE-systemet som identifiserer et havneområde. Koden består av 5 bokstaver: de to første bokstavene angir landskode, mens de tre siste identifiserer havnen. Eks: NOSVG (Stavanger).<br />Se liste med lovlige kodeverdier her: <a href="https://service.unece.org/trade/locode/no.htm">https://service.unece.org/trade/locode/no.htm</a></td>
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
FellesegenskaperOpsjonell

#### Kamera

Kamera tilknyttet havnen.

Egenskaper

(ingen)

Relasjoner

**Arv**
Havnesensor

#### Lastbegrensningsområde

Område i havnen eller på kai som har begrensinger for hva det tåler av belastning.

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
      <td>Område</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td>Opsjonelt representasjonspunkt for området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>vektbegrensning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Vekten av jevnt fordelt last over et område. Øvre grense for jevnt fordelt last. Måles i antall tonn pr. kvadratmeter (t/m2).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>akseltrykk</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Det trykk som må bæres av én aksel på en vogn eller kjøretøy.<br />Øvre grense for akseltrykk. Måles i tonn (t).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>minsteAvstandPunktlast</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Hvor tett to punktlaster kan stå for å ikke overbelaste kaien. Henger sammen med egenskapen punktlast. Måles i meter (m).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>lastreferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Referanse til originaldokument, tegning e.l. som inneholder informasjon om lastebegrensing.</td>
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
      <td><strong>bruksklassetype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Bruksklasse</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Bruksklassetype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/bruksklassetype">https://register.geonorge.no/sosi-kodelister/havnedata/bruksklassetype</a><br />- Bk10 – Bruksklasse 10<br />- Bk8 – Bruksklasse 8<br />- Bk6 – Bruksklasse 6<br />- Annen – Annen type bruksklasse.<br />- BkT8 – BkT er en variant av Bk8. Den har same maksimale aksellast som Bk8, men totalvekten er høyere.</td>
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
      <td><strong>punktlast</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Vekten av last fordelt i et punkt. Øvre grense for maksimal vekt av en punktlast. Måles i tonn (t).</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>kaidekketype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kaidekke</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kaidekketype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/kaidekketype">https://register.geonorge.no/sosi-kodelister/havnedata/kaidekketype</a><br />- Asfalt – Asfaltdekke<br />- Betong – Betongdekke<br />- Belegningsstein, heller – Dekke av belegningsstein eller heller.<br />- Tredekke<br />- Annet – Annet materiale.</td>
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
      <td><strong>lastId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Tall eller tekst havnen bruker for å identifisere et lastbegrensningsområde.</td>
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
KaiId

**Assosiasjoner**
LastbegrensningsområdeGrense – rolle: avgrensning – kardinalitet: 0..*

#### Kaiområde

Kaiområde er området direkte innenfor kaifronten som tilhører den samme kaien.<br />Kaiområde avgrenses av KaiområdeGrense. Kaifront brukes ikke som avgrensning til kaiområde, men ligger som et eget objekt.

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
      <td>Område</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td>Opsjonelt representasjonspunkt for området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>kaitype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angivelse av kaitype.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kaitype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/kaitype">https://register.geonorge.no/sosi-kodelister/havnedata/kaitype</a><br />- Bulk – Kai for lasting av våt- eller tørrbulk.<br />- Container – Kai for lasting/lossing av containere.<br />- Lo-lo – Lift-on - lift-off. Lasting og lossing av containere ved hjelp av containerkran.<br />- Ro-ro – Roll-on - roll-off. Kai hvor rullende last kan kjøres ifra kaien og direkte ombord.<br />- Fritid – Mindre kai for fritidsbåter etc.<br />- Annen – Annen type kai. Beskriv ved hjelp av egenskapen informasjon.<br />- Lokale ferger – Kai for lokale ferger.<br />- Utland ferger – Kai for internasjonale ferger.<br />- Cruise – Kai for cruiseskip.<br />- Charter – Kai for charterbåter.<br />- Fiskeri – Fiskerikai<br />- Offshore – Offshorekai<br />- Opplag – Opplagskai<br />- Service og reparasjon – Kai for service og reparasjon.<br />- Hurtigbåt – Kai for hurtigbåt.<br />- Ventekai<br />- Flerbrukskai – Flerbrukskai. Spesifiser hvilken bruk under egenskapen informasjon.<br />- Trelast – Kai for trelast eller tømmer.<br />- Stein – Kai for stein eller steinmateriale.<br />- Dypvannskai – Kai anlagt ved dypt vann, slik at dyptgående fartøyer kan legge til.</td>
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
      <td><strong>kaidekketype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskrivelse av materialbruk på dekke av kaia (betong, asfalt, tre e.l.)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kaidekketype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/kaidekketype">https://register.geonorge.no/sosi-kodelister/havnedata/kaidekketype</a><br />- Asfalt – Asfaltdekke<br />- Betong – Betongdekke<br />- Belegningsstein, heller – Dekke av belegningsstein eller heller.<br />- Tredekke<br />- Annet – Annet materiale.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
KaiId

**Assosiasjoner**
KaiområdeGrense – rolle: avgrensning – kardinalitet: 0..*

#### KaiområdeGrense

Avgrensning av kaiområde.

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
      <td>Forløp som følger overgang mellom ulike fenomener.</td>
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

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### Flytedokk

En flytedokk eller våtdokk er en flytende plattform for å heve skip opp av sjøen når det skal gjøres vedlikehold eller reperasjoner av skip.

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
      <td>Polygon som viser geografisk utstrekning.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td>Opsjonelt representasjonspunkt for området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>maksFartøyBredde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal bredde på fartøyet som dokken kan romme. Angis i meter.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>maksFartøyLengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal lengde på fartøyet som dokken kan romme. Angis i meter.</td>
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
      <td><strong>maksFartøyDyptgående</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal dyptgående på fartøyet som dokken kan romme. Angis i meter.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>løftekapasitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal løftekapasitet, angitt i tonn.</td>
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
      <td><strong>navn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navn på flytedokken.</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
HavneanleggId

**Assosiasjoner**
FlytedokkGrense – rolle: avgrensning – kardinalitet: 0..*

#### Beredskapspunkt

Punkt på kaia der det er plassert utstyr for beredskap/sikkerhet.

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
      <td>Posisjon</td>
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
      <td><strong>beredskapstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beredskapstype</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Beredskapstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/beredskapstype">https://register.geonorge.no/sosi-kodelister/havnedata/beredskapstype</a><br />- Stige<br />- Redningsbøye<br />- Annen – Annen type beredskapspunkt.<br />- Oljelenser – Oljelenser. Anretning for å redusere oljesøl som flyter på vannet.<br />- Båtshake<br />- Nødplakat, infopunkt – Nødplakat/infopunkt<br />- Angrepsvei – Tilrettelagt adkomst til en bygning berenget for brannvesenet/beredskap.<br />- Brannkum – Fast montert utstyr i kum, som er beregnet for kopling til brannvesenets utstyr.<br />- Samlingsplass – Oppmøtested ved evakuering ved brannalarm.<br />- Nøkkelskap – Nøkkelskap eller nøkkelsafe for bruk av brannvesenet.<br />- Høyspenning – Anlegg med høyspenning (f.eks. trafo eller tilsvarende).<br />- Gass under trykk – Rom eller bygning hvor beholdere med gass under trykk oppbevares<br />- Talevarslingsentral – Sentral for talevarsling av brann eller annen nødsituasjon.<br />- Brannalarmsentral – Sentralapparatet i et brannalarmsanlegg.<br />- Røyklukepanel – Luke, panel eller annen bygningsdel som skal kunne åpnes eller fjernes for å ventilere ut varme og røyk fra bygning i brann.<br />- Sprinklersentral – Samlet arrangement av ventiler, manometre og annet utstyr som er nødvendig for funksjonen til et sprinkleranlegg.<br />- Brannfarlig opplag – Lager eller oppbevaring av varer/materiale som er brannfarlig.<br />- Eksplosjonsfare – Fare eller risiko for eksplosjon.<br />- Førstehjelp – Førstehjelpsutstyr.<br />- Hjertestarter – En hjertestarter (defibrillator) er førstehjelpsutstyr som kan brukes til å starte hjertet på nytt i tilfeller av hjertestans.<br />- Brannslange<br />- Brannslukningsapparat</td>
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
      <td><strong>spesifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Egenskap for å spesifisere beredskapstype.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
ObjektId

#### Havnesensor

Sensor som måler, samler inn data eller registrerer annet i tilknytning til havnen.

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
      <td>Posisjon</td>
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
      <td><strong>sensortype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Type sensor.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Sensortype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/sensortype">https://register.geonorge.no/sosi-kodelister/havnedata/sensortype</a><br />- Temperatur – Termometer<br />- Vind – Vindmåler<br />- Annen – Annen type sensor.<br />- Strøm – Sensor for måling av strøm i vann.<br />- Vannstand – Vannstandsmåler<br />- Kamera<br />- Værstasjon – Sensor til å måle vind, temperatur, vannstand.<br />- Portsensor – Sensor til overvåkning av port.<br />- Dørsensor – Sensor til overvåkning av dør.<br />- Støymåler – Sensor for måling av støy.<br />- Fartsmåler – Sensor som måler fart til kjøretøy, med fartstavle for visning av fart.<br />- Redningsbøyeskapsensor – Sensor på redningsbøyeskap. Varseler om en redningsbøye er tatt i bruk.<br />- Luftkvalitet – Sensor for måling av luftkvalitet.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>objektLøpenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Unik identisfisering av det enkelte objekt på kaia i form av URL, nummer, navn eller annet.</td>
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
HavnId

#### ELkobling

Tilkoblingspunkt for strøm på kaia.

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
      <td>Posisjon</td>
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
      <td><strong>ELanleggstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskrivelse av hva slags type strømtilkobling som kan gjøres.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>ELanleggstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/el-anleggstype">https://register.geonorge.no/sosi-kodelister/havnedata/el-anleggstype</a><br />- Strømskap – Strømskap med diverse tilkoblingsmuligheter.<br />- Landstrøm – Landstrømanlegg.<br />- Annen – Annen type strømanlegg.<br />- Ladeanlegg – Strømanlegget brukes til lading.<br />- Strømtilførsel kran – EL-anlegg hvor det er mulig å koble til strømtilførsel for kran.</td>
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
      <td><strong>rekkeviddeLadeanlegg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Attributt som benyttes ved ladeannlegg, for å spesifisere lengde på kabeltrommel som er tilgjengelig. Oppgis i meter.</td>
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
      <td><strong>tilgangstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste for å spesifisere hvem som har mulighet til å benytte punktet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Tilgangstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype">https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype</a><br />- Annet – Annen tilgang.<br />- Leietager – Tilgang for leietager.<br />- Havnedrift – Tilgang for havnedrift.<br />- Alle – Tilgang for alle.<br />- Godsfartøy – Tilgang for godsfartøy.<br />- Alle skip – Tilgang for alle typer skip eller fartøy.<br />- Fiskebåter – Tilgang for fiskebåter.<br />- Fritidsbåter – Tilgang for fritidsbåter.<br />- Cruise fartøy – Tilgang for cruisefartøy.<br />- Annet fartøy – Tilgang for andre fartøy.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>ELkoblinger</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Spesifikasjon av de ulike kombinasjonene EL-koblingspunkt som finnes.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>ELkoblingEgenskaper</td>
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
      <td><strong>ELkoblinger.effekt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Watt. Arbeid pr. sekund.</td>
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
      <td><strong>ELkoblinger.frekvens</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Hvor mange ganger en elektrisk spenning veksler i løpet av ett sekund. Måles i Hz.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Frekvens</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/frekvens">https://register.geonorge.no/sosi-kodelister/havnedata/frekvens</a><br />- 50 Hz – Frekvens 50 Hz.<br />- 60 Hz – Frekvens 60 Hz.<br />- Likestrøm<br />- Ukjent – Ukjent frekvens<br />- 50 eller 60 Hz – Kontakt som kan levere frekvens på 50 eller 60 Hz.</td>
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
      <td><strong>ELkoblinger.spenning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Volt. Elektrisk spenning.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Spenning</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/spenning">https://register.geonorge.no/sosi-kodelister/havnedata/spenning</a><br />- 230V – 230 Volt<br />- 400V – 400 Volt<br />- 690V – 690 Volt<br />- 11000V – Høyspenning, 11kV.<br />- 22000V – Høyspenning 22 kV.<br />- Ukjent – Ukjent spenning.<br />- 440V – 440 Volt<br />- 6600V – Høyspenning 6,6 kV.<br />- 440V eller 690V – Kontakt som kan levere 440V eller 690V over samme kontakt.<br />- 6600V eller 11000V – Høyspenning. Kontakt som kan levere 6.6kV eller 11kV over samme kontakt.</td>
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
      <td><strong>ELkoblinger.sikringstørrelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Strømstyrke, oppgis i ampere, SI-enheten for elektrisk strøm. Strømstyrke er lik ladning som passerer et tverrsnitt av en leder pr. sekund.</td>
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
      <td><strong>ELkoblinger.kontaktId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Id-nummer eller annen beskrivelse som spesifiserer hvilken type kontakt.</td>
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
      <td><strong>ELkoblinger.faser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Betegnelse på de enkelte polene eller lederne i et vekselstrømsystem.</td>
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
ObjektId

#### Forvaltningsområde

Areal som viser utstrekningen på det område en kommune eller en kommunal/interkommunal havneadministrasjonen har ansvaret for. Dette området er ofte sammenfallende med kommunens sjøområde, som er det område hvor kommunen har planmyndighet etter plan- og bygningsloven med unntak av hoved- og biled (Hoved- og biled forvaltes av Kystverket).

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forvaltesAv</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Felt for å angi hvem som forvalter området. Vanligvis kommune, IKS eller havneadministrasjon på vegne av kommune.</td>
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
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Polygon som viser geografisk utstrekning.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td>Opsjonelt representasjonspunkt for området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
HavnId

**Assosiasjoner**
ForvaltningsområdeGrense – rolle: avgrensning – kardinalitet: 0..*

#### HavneområdeGrense

Avgrensning av havneområde.

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
      <td>Forløp som følger overgang mellom ulike fenomener.</td>
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

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### Fender

Beskytter/demper for bevegelse mellom båt og kai. Monteres ofte fast på kaikanten.

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
      <td>Posisjon</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>fendertype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Fendertype</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Fendertype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/fendertype">https://register.geonorge.no/sosi-kodelister/havnedata/fendertype</a><br />- Firkantet fender – Firkantet fender.<br />- D-fender – Gummirør med D-formet tverrsnitt.<br />- Bildekkfender – Fender av bildekk.<br />- Slepebåtfender – Slepebåtfender.<br />- Rullefender – Rullende fender.<br />- Rund fender – Rund fender.<br />- PUR-fender – Fender av polyuretan.<br />- Flytefender – Flytende fender.<br />- Pneumatisk fender – Stor pølseformet flytende gummifender fylt med høytrykksluft, ofte dekket av hjul.<br />- Conefender – Kjegleformet fender som står vertikalt ut fra kaien, med en flense på toppen.<br />- Sirkelfender – Sirkel- eller halvsirkel-formet fender.<br />- Trapesfender – Trapesformet fender.<br />- V-fender – Fender med V-formet tverrsnitt.<br />- Torsjonsfender – Fender som har en torsjonsfjæroppheng/torsjonsarm.<br />- Bunnfundamentert fender – Fender som er bunnfundamentert.<br />- Fenderpanel – Fender som et panel.<br />- Dumperdekk – Fender av bildekk fra dumpere.<br />- Annen fender – Annen type fender.</td>
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
      <td><strong>fenderspesifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Egenskap for å spesifisere fender. Fenderen kan beskrives med mål, for eksempel bredde, høyde, diameter etc.</td>
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
      <td><strong>høydeSjøkartnull</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angitt høyde i meter over vannet. Egenskapen høyde angis i forhold til sjøkartnull (dvs. høyder over lokal LAT-verdi) dersom ikke annet er angitt.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>fenderorientering</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Retning/orientering på fenderen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Fenderorientering</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/fenderorientering">https://register.geonorge.no/sosi-kodelister/havnedata/fenderorientering</a><br />- Annen orientering – Annen orientering.<br />- Stående fender – Stående fender.<br />- Liggende fender – Liggende fender.</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>fendergruppering</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kurve geometri som brukes ved gruppering av fendere.<br />Geometrien skal følge kaifront der hvor det er mange like fendere. Antall fendere oppgis i antall-felt, og avstand spesifiseres i informasjonsfeltet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>antall</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Oppgi antall fendere. Benyttes ved gruppering av fendere.</td>
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
ObjektId

#### VAuttak

Tilkoblingspunkt for vann på kaia.

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
      <td>Posisjon</td>
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
      <td><strong>VAuttakstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskrivelse av hva slags uttakstype som kan gjøres.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>VAuttakstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/va-uttakstype">https://register.geonorge.no/sosi-kodelister/havnedata/va-uttakstype</a><br />- Ferskvann – Ferskvann/drikkevann til påfylling på båt.<br />- Annen – Annen type for VA-uttak.
Spesifiseres ved bruk av egenskapen informasjon.</td>
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
      <td><strong>kapasitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kapasitet til fylling av vann angitt i antall m3/time.</td>
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
      <td><strong>tilkoblingsdimensjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Størrelse/dimensjon på rørene som skal kobles sammen.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>kumnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>ID-merking av kummer. Kan tas fra havnas eget merkesystem eller kommunens SID-nr.</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>tilgangstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste for å spesifisere hvem som har mulighet til å benytte uttaket.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Tilgangstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype">https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype</a><br />- Annet – Annen tilgang.<br />- Leietager – Tilgang for leietager.<br />- Havnedrift – Tilgang for havnedrift.<br />- Alle – Tilgang for alle.<br />- Godsfartøy – Tilgang for godsfartøy.<br />- Alle skip – Tilgang for alle typer skip eller fartøy.<br />- Fiskebåter – Tilgang for fiskebåter.<br />- Fritidsbåter – Tilgang for fritidsbåter.<br />- Cruise fartøy – Tilgang for cruisefartøy.<br />- Annet fartøy – Tilgang for andre fartøy.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
ObjektId

#### HavneanleggGrense

Avgrensning av havneanlegg.

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
      <td>Forløp som følger overgang mellom ulike fenomener.</td>
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

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### Avfallspunkt

punkt for å kaste avfall

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
      <td>Posisjon</td>
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
      <td><strong>avfallstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Avfallstype</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Avfallstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/avfallstype">https://register.geonorge.no/sosi-kodelister/havnedata/avfallstype</a><br />- Annet – Annen type avfall.<br />- Papp, papir, kartong – Avfallspunkt for papp, papir eller kartong.<br />- Matavfall – Avfallspunkt for matavfall.<br />- Plast – Avfallspunkt for plast.<br />- Glass – Avfallspunkt for glass.<br />- Metall – Avfallspunkt for metall.<br />- Restavfall – Avfallspunkt for restavfall.<br />- Oljeholdig avfall – Avfallspunkt for oljeholdig avfall.<br />- Lyspærer – Avfallspunkt for lyspærer.<br />- EE-avfall – Avfallspunkt for elektriske og elektroniske produkter. Inkludert lysrør.<br />- Maling – Avfallspunkt for maling.<br />- Asfalt – Avfallspunkt for asfalt.<br />- Stein – Avfallspunkt for stein.<br />- Impregnert tre – Avfallspunkt for impregnert tre.<br />- Batterier – Avfallspunkt for batterier.</td>
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
      <td><strong>avfallsplan</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Henvisning til avfallsplan som gjør rede for planlagt håndtering av avfall.</td>
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
      <td><strong>tilgangstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste for å spesifisere hvem som har mulighet til å benytte avfallspunktet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Tilgangstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype">https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype</a><br />- Annet – Annen tilgang.<br />- Leietager – Tilgang for leietager.<br />- Havnedrift – Tilgang for havnedrift.<br />- Alle – Tilgang for alle.<br />- Godsfartøy – Tilgang for godsfartøy.<br />- Alle skip – Tilgang for alle typer skip eller fartøy.<br />- Fiskebåter – Tilgang for fiskebåter.<br />- Fritidsbåter – Tilgang for fritidsbåter.<br />- Cruise fartøy – Tilgang for cruisefartøy.<br />- Annet fartøy – Tilgang for andre fartøy.</td>
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
      <td><strong>beholdertype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beholdertype</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Beholdertype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/beholdertype">https://register.geonorge.no/sosi-kodelister/havnedata/beholdertype</a><br />- Annet – Annen type avfallsbeholder.<br />- Avfallsbeholder – Avfallsbeholder.<br />- Nedgravd avfallsløsning<br />- Søppelbøtte<br />- Container</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>mobilitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Egenskap for å anngi om avfallspunktet er fast montert eller flyttbart ( i form av en bil eller lignende).<br /><br />For mobile tilkoblingspunkt er det vanskelig/meningsløst å stedfeste punktet nøyaktig. Punktet plasseres da på et passelig representativt punkt og gis en kvalitetskode som angir stor usikkerhet i innmåling.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
ObjektId

#### Fortøyningsinnretning

Fortøyningsinnretning som tilhører kaia.

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
      <td>Posisjon</td>
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
      <td><strong>fortøyningstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Fortøyningstype</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Fortøyningstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/fortoyningstype">https://register.geonorge.no/sosi-kodelister/havnedata/fortoyningstype</a><br />- Ring – Fortøyningsring<br />- Pullert<br />- Slipphake – Krok med hengsel og en bøyle som kan slås til side for å åpnes.<br />- Mantel – Søyleformet pullert. Trosser kan festes i hvilken som helst retning ut fra mantel.<br />- Bøye – Fortøyningsbøye<br />- Dykdalb – Bunt av stokker eller påler som er drevet ned i sjøbunnen, og som fartøy kan fortøyes i. De plasseres ofte i forlengelsen av en kaifront for å gjøre det mulig å fotøye skip som er lengre enn kaia.<br />- Kabel, wire – Kabel eller wire som kan brukes til fortøyning.<br />- Annen – Annen type fortøyningsinnretning.</td>
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
      <td><strong>maksbelastning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskrivelse av maks belastning for pullerten i antall tonn</td>
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
      <td><strong>spesifikasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Egenskap for å spesifisere fortøyningsinnretning.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
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
      <td><strong>høydeSjøkartnull</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angitt høyde i meter over vannet. Egenskapen høyde angis i forhold til sjøkartnull (dvs. høyder over lokal LAT-verdi) dersom ikke annet er angitt.</td>
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
      <td><strong>sertifiseringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Dato for forrige sertifisering.</td>
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
      <td><strong>tillattFortøyningsvinkelGrunnriss</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Tillatt område for fortøyning sett i grunnriss. Eksempel: +/-90°.</td>
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
      <td><strong>tillattFortøyningsvinkelOppriss</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Tillatt område for fortøyning sett i oppriss. Eksempel: +75°/-15°.</td>
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
ObjektId

#### KaiId (abstrakt)

Abstrakt objekt som holder egenskaper for unik identifisering av en kai. Egenskapene arves ned til øvrige objektklasser i Havnedata.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kaiId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Unik identifisering av den enkelte kai.</td>
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
      <td><strong>kainavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navn på kaien. Det samme kainavnet brukes på alle kaifronter og kaiområder som regnes å tilhøre samme kai. Navn bør stemme overens med SafeSeaNet.</td>
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
      <td><strong>kaiIdIntern</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Havnens interne egendefinerte nummering av kaier.<br />Nummerering varierer fra havn til havn, noen bruker utelukkende tall eller bokstaver, mens andre bruker en kombinasjon.</td>
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
HavneanleggId

#### LastbegrensningsområdeGrense

Avgrensning av lastbegrensningsområde.

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
      <td>Forløp som følger overgang mellom ulike fenomener.</td>
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

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### Kaifront

Kaifront er den ytterste delen av kaien, som avgrenser sjøen fra land, hvor fartøy kan ligge fortøyd langs.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kaitype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Type kai</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kaitype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/kaitype">https://register.geonorge.no/sosi-kodelister/havnedata/kaitype</a><br />- Bulk – Kai for lasting av våt- eller tørrbulk.<br />- Container – Kai for lasting/lossing av containere.<br />- Lo-lo – Lift-on - lift-off. Lasting og lossing av containere ved hjelp av containerkran.<br />- Ro-ro – Roll-on - roll-off. Kai hvor rullende last kan kjøres ifra kaien og direkte ombord.<br />- Fritid – Mindre kai for fritidsbåter etc.<br />- Annen – Annen type kai. Beskriv ved hjelp av egenskapen informasjon.<br />- Lokale ferger – Kai for lokale ferger.<br />- Utland ferger – Kai for internasjonale ferger.<br />- Cruise – Kai for cruiseskip.<br />- Charter – Kai for charterbåter.<br />- Fiskeri – Fiskerikai<br />- Offshore – Offshorekai<br />- Opplag – Opplagskai<br />- Service og reparasjon – Kai for service og reparasjon.<br />- Hurtigbåt – Kai for hurtigbåt.<br />- Ventekai<br />- Flerbrukskai – Flerbrukskai. Spesifiser hvilken bruk under egenskapen informasjon.<br />- Trelast – Kai for trelast eller tømmer.<br />- Stein – Kai for stein eller steinmateriale.<br />- Dypvannskai – Kai anlagt ved dypt vann, slik at dyptgående fartøyer kan legge til.</td>
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
      <td>Angitt lengde på kaifronten i antall meter. Kailengden måles opp på den delen av kaifronten som egner seg for anløp av skip. Lengde kan også beregnes ut fra lengden på geometrien.</td>
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
      <td><strong>høydereferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Høydereferanse til kartobjektet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a><br />- Fot – Høyden målt til foten av objektet.<br />- Topp – Høyden målt til toppen av objektet.<br />- Ukjent – Ukjent (benyttes ikke ved nyregistrering).</td>
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
      <td><strong>kaifronttype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver type konstruksjon kaifronten har mot sjøen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kaifronttype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/kaifronttype">https://register.geonorge.no/sosi-kodelister/havnedata/kaifronttype</a><br />- Kai – Konstruksjon, vanligvis parallell med kystkonturen, hvor fartøy kan fortøye eller laste/losse. Horisontalt plan.<br />- Rampe – Trinnfritt skråplan som fungerer som forbindelse mellom to horisontale plan som ikke ligger på samme nivå. Brukes ofte til i landkjøring av rullende objekter (ro-ro). Stopper ved vannkant.<br />- Slipp – Bane som fartøy kan hales opp ved landsetting, fra flytende posisjon og opp på tørt land. Skråplanet går vanligvis ut og ned i vannet.<br />- Trapp – Kai hvor trappetrinn er en del av kaikonstruksjonen eller utgjør den ytterste delen på kaien.<br />- Annen – Annen type kaifront.<br />- Ro-ro rampe – (Roll on/roll off) justerbar rampe eller ombordkjøringsplattform, tilsvarende ferjelem, som er tilpasset for at rullende last kan kjøres fra kai og direkte om bord.<br />- Spunt – Støttekonstruksjon som settes opp som en vegg for å holde på plass løsmasser fra sjø.<br />- Søylekai – Kai på pæler eller søyler.<br />- Mur – Kai som er steinmurt eller konstruert av mur.<br />- Ukjent – Ukjent kaifronttype.</td>
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
      <td><strong>høydeSjøkartnull</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angitt høyde på kaien i meter over vannet. Egenskapen høyde angis i forhold til sjøkartnull (dvs. høyder over lokal LAT-verdi) dersom ikke annet er angitt.</td>
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
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Forløp som følger overgang mellom ulike fenomener.</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Beskriver status til et objekt.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a><br />- I bruk – Objektet er i bruk.<br />- Ikke i bruk – Objektet er ikke i bruk.<br />- Skadet – Objektet er skadet.<br />- Planlagt – Objektet er planlagt.<br />- Foreldet – Objektet er foreldet.<br />- Privat – Privat objekt.<br />- Nedlagt – Nedlagt objekt.<br />- Fjernet – Objektet er fjernet.<br />- Under arbeid – Objektet er under arbeid.<br />- Tilstand uviss – Ukjent tilstand.<br />- I forfall – Objektet er i forfall.<br />- Periodisk – Periodisk objekt.<br />- Midlertidig – Midlertidig objekt.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
ObjektId

#### FellesegenskaperPåkrevd (abstrakt)

abstrakt objekt som bærer en felles egenskaper som brukes på alle objekttyper i FKB.<br />Påkrevde egenskaper.

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
      <td>Unik identifikasjon av objektet.</td>
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
      <td>Unik identifikator innenfor navnerommet. For FKB benyttes UUID.</td>
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
      <td>navnerom i form av en URI</td>
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
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterers. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen. Benyttes normalt ikke i FKB.</td>
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
      <td><strong>kvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Stedfestingskvalitet</td>
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
      <td><strong>kvalitet.datafangstmetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Metode for datafangst.<br />Egenskapen beskriver datafangstmetode for grunnrisskoordinater (x,y), eller for både grunnriss og høyde (x,y,z) dersom det ikke er oppgitt noen verdi for datafangstmetodeHøyde.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Datafangstmetode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/datafangstmetode">https://register.geonorge.no/sosi-kodelister/havnedata/datafangstmetode</a></td>
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
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer.<br /><br />Merknad:<br />Oppgitt i cm</td>
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
      <td><strong>kvalitet.synbarhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Hvor godt den kartlagte detalj var synbar ved kartleggingen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Synbarhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/synbarhet">https://register.geonorge.no/sosi-kodelister/havnedata/synbarhet</a><br />- Fullt ut synlig/gjenfinnbar i terrenget – Fullt ut synlig/gjenfinnbar i terrenget (default-verdi).<br />- Dårlig gjenfinnbar i terreng – Forøvrig grei å innmåle. (Benyttes bl.a. for innmåling av ledninger på lukket grøft).<br />- Middels synlig i flybilde/modell – Middels synlig i flybilde/modell.<br />- Dårlig/ikke synlig i flybilde/modell – Dårlig/ikke synlig i flybilde/modell.</td>
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
      <td><strong>kvalitet.datafangstmetodeHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Metode brukt for høyderegistrering av posisjon.<br />Det er bare nødvending å angi en verdi for egenskapen dersom datafangstmetode for høyde avviker fra datafangstmetode for grunnriss.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Datafangstmetode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/datafangstmetode">https://register.geonorge.no/sosi-kodelister/havnedata/datafangstmetode</a></td>
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
      <td><strong>kvalitet.nøyaktighetHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Nøyaktighet for høyden i cm.</td>
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

#### FellesegenskaperOpsjonell (abstrakt)

abstrakt objekt som bærer en felles egenskaper som brukes på alle objekttyper i FKB.<br />Opsjonelle egenskaper.

Egenskaper

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
      <td>generell opplysning</td>
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
      <td><strong>link</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Link i form av URL eller annet til mer informasjon om objektet.</td>
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
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektetdataene.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### Forbudsområde

Område som er omfattet av forbud, som f.eks. ferdselsforbud for vannscooter.

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
      <td>Polygon som viser geografisk utstrekning.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td>Opsjonelt representasjonspunkt for området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>fastsattAv</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir hvem forskriften er fastsatt av.</td>
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
      <td><strong>forskriftLenke</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Lenke til forskiften på lovdata.no.</td>
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
      <td><strong>forskriftNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navnet på forskrift som regulerer forbudsområdet. Ved langt navn kan korttittel benyttes.</td>
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
      <td><strong>gjelderFor</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Geografisk område som forskriften gjelder for. Står spesifisert i lovteksten, kan være en kommune eller et havneområde.</td>
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
      <td><strong>gjelderForFartøytype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste som spesifiserer hvilken type fartøy som er omfattet av forbudet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Fartøytype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/fartoytype">https://register.geonorge.no/sosi-kodelister/havnedata/fartoytype</a><br />- Alle – Alle flytende innretninger som er laget for å bevege seg igjennom vannet.<br />- Fritidsfartøy under 24 m – Fartøy som ikke brukes til nyttetrafikk og er under24 meter.<br />- Vannscooter – Farkost med skroglengde mindre enn 4 meter, utstyrt med innenbords forbrenningsmotor som driver et vannjetaggregat som hovedfremkomstmiddel.<br />- Nyttefartøy – Fartøy som brukes til nyttetrafikk eller i næring.<br />- Annet – Annen type.</td>
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
      <td><strong>lovhjemmel</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Lov som forbudet eller forskriften har hjemmel i.</td>
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
      <td><strong>periodeGyldigFra</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Periode gyldig fra. Oppgis for forbudsområder som har tidsavgrensning eller gjelder deler av året (f.eks. bare i sommermånedene). Årstall er ikke nødvendig. Dersom årstall ikke oppgis regnes datoen å gjelde hvert år.</td>
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
      <td><strong>periodeGyldigTil</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Periode gyldig til. Oppgis for forbudsområder som har tidsavgrensning eller gjelder deler av året (f.eks. bare i sommermånedene). Årstall er ikke nødvendig. Dersom årstall ikke oppgis regnes datoen å gjelde hvert år.</td>
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
      <td><strong>forbudstype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir hvilket type forbud som gjelder for området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Forbudstype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/forbudstype">https://register.geonorge.no/sosi-kodelister/havnedata/forbudstype</a><br />- Ferdsel – Forbud mot ferdsel.<br />- Ankring – Forbud mot ankring.<br />- Dykking – Forbud mot dykking.<br />- Tømming – Forbud mot tømming eller dumping.<br />- Fisking – Forbud mot fisking.<br />- Annet – Annet forbud.<br />- Snøtømming – Forbud mot snøtømming.<br />- Ukjent – Ukjent forbud.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FellesegenskaperOpsjonell

**Assosiasjoner**
ForbudsområdeGrense – rolle: avgrensning – kardinalitet: 0..*

#### FartsrestriksjonerGrense

Avgrensning av Fartsrestriksjoner.

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
      <td>Forløp som følger overgang mellom ulike fenomener.</td>
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

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### ForbudsområdeGrense

Avgrensning av forbudsområde.

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
      <td>Forløp som følger overgang mellom ulike fenomener.</td>
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

Relasjoner

**Arv**
FellesegenskaperPåkrevd

#### Fartsrestriksjoner

Område som har restriksjoner knyttet til ferdsel og fart for fartøyer som ferdes på sjøen.

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
      <td>Polygon som viser geografisk utstrekning.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
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
      <td>Opsjonelt representasjonspunkt for området.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>forskriftNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navnet på forskriften. Ved langt navn korttittel benyttes.</td>
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
      <td><strong>gjelderForFartøytype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Kodeliste som spesifiserer hvilken type fartøy som er omfattet av forskriften.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Fartøytype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/havnedata/fartoytype">https://register.geonorge.no/sosi-kodelister/havnedata/fartoytype</a><br />- Alle – Alle flytende innretninger som er laget for å bevege seg igjennom vannet.<br />- Fritidsfartøy under 24 m – Fartøy som ikke brukes til nyttetrafikk og er under24 meter.<br />- Vannscooter – Farkost med skroglengde mindre enn 4 meter, utstyrt med innenbords forbrenningsmotor som driver et vannjetaggregat som hovedfremkomstmiddel.<br />- Nyttefartøy – Fartøy som brukes til nyttetrafikk eller i næring.<br />- Annet – Annen type.</td>
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
      <td><strong>hastighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Maksimal tillatte hastighet, angitt i knop.</td>
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
      <td><strong>lovhjemmel</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Lov som forskriften har hjemmel i.</td>
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
      <td><strong>periodeGyldigFra</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Periode gyldig fra. Oppgis for fartsrestriksjoner som har tidsavgrensning eller gjelder deler av året (f.eks. bare i sommermånedene). Årstall er ikke nødvendig. Dersom årstall ikke oppgis regnes datoen å gjelde hvert år.</td>
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
      <td><strong>periodeGyldigTil</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Periode gyldig til. Oppgis for fartsrestriksjoner som har tidsavgrensning eller gjelder deler av året (f.eks. bare i sommermånedene). Årstall er ikke nødvendig. Dersom årstall ikke oppgis regnes datoen å gjelde hvert år.</td>
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
      <td><strong>fastsattAv</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Angir hvem forskriften er fastsatt av.</td>
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
      <td><strong>forskriftLenke</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Lenke til forskriften på lovdata.no.</td>
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
      <td><strong>gjelderFor</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Geografisk område som forskriften gjelder for. Står spesifisert i lovteksten, og er vanligvis en kommune eller havneområde,</td>
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
FellesegenskaperOpsjonell

**Assosiasjoner**
FartsrestriksjonerGrense – rolle: avgrensning – kardinalitet: 0..*

### Kodelister

#### «Enumeration» Eierskap

**Definisjon:** Angir type eierskap.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/eierskap">https://register.geonorge.no/sosi-kodelister/havnedata/eierskap</a></td>
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
      <td>Stat</td>
      <td>Statlig eierskap.</td>
      <td></td>
    </tr>
    <tr>
      <td>Privat</td>
      <td>Privat eierskap.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fylke</td>
      <td>Fylkeskommunalt eierskap.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td>Annen type egenskap.</td>
      <td></td>
    </tr>
    <tr>
      <td>Kommune</td>
      <td>Kommunalt eierskap.</td>
      <td></td>
    </tr>
    <tr>
      <td>Offentlig</td>
      <td>Offentlig eierskap.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Ukjent eierskap.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Sikringstype

**Definisjon:** Angir sikring til havneobjekt.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/sikringstype">https://register.geonorge.no/sosi-kodelister/havnedata/sikringstype</a></td>
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
      <td>Permanent sikret</td>
      <td>Havnesikkerhetsområdet som er permanent sikret.</td>
      <td></td>
    </tr>
    <tr>
      <td>Sikret ved anløp</td>
      <td>Havnesikkerhetsområde som kun er sikret ved anløp av skip.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen sikring</td>
      <td>Annen type sikring.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Avsperringstype

**Definisjon:** Type avsperring for HavnegjerdeInngang.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/avsperringstype">https://register.geonorge.no/sosi-kodelister/havnedata/avsperringstype</a></td>
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
      <td>Manuell port</td>
      <td>Manuell port som avsperring av inngang.</td>
      <td></td>
    </tr>
    <tr>
      <td>Manuell bom</td>
      <td>Manuell bom som avsperring av inngang.</td>
      <td></td>
    </tr>
    <tr>
      <td>Elektrisk bom</td>
      <td>Elektrisk bom som avsperring av inngang.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen type avsperring av inngang.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Ukjent type avsperring av inngang.</td>
      <td></td>
    </tr>
    <tr>
      <td>Dør</td>
      <td>Dør som tilkomst eller avsperring av inngang til område avgrenset av havnegjerde.</td>
      <td></td>
    </tr>
    <tr>
      <td>Rotasjonsport</td>
      <td>Roterende port som tillater passering av én person om gangen. Som adgangskontroll for personer inn/ut av et område.</td>
      <td></td>
    </tr>
    <tr>
      <td>Sluse</td>
      <td>Sluse for gjennomslipp av en person om gangen. Som adgangskontroll for personer inn/ut av et område.</td>
      <td></td>
    </tr>
    <tr>
      <td>Personsperre</td>
      <td>Adgangssperrer for personer inn/ut av et område.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skyveport</td>
      <td>Port som åpnes ved å skyve porten til siden, parallellt med gjerdet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Foldeport</td>
      <td>Port som åpnes ved å folde seg sammen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Heveport</td>
      <td>Port som ånes ved å heve seg vertikalt opp, på samme måte som en veibom åpnes.</td>
      <td></td>
    </tr>
    <tr>
      <td>Nedleggbar port</td>
      <td>Port som kan legges ned for åpning av bred transport eller lignende.</td>
      <td></td>
    </tr>
    <tr>
      <td>Kombinasjonsport</td>
      <td>Port som har en kombinasjon av flere åpningsmekanismer, f.eks. en kombinasjon av skyveport med et spesialfelt med nedleggbar port i midten.</td>
      <td></td>
    </tr>
    <tr>
      <td>Svingport</td>
      <td>Svingbar port som åpnes som en grind.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Åpningstype

**Definisjon:** Beskriver åpningsmekanisme av port, bom eller annen avsperringstype for HavnegjerdeInngang.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/apningstype">https://register.geonorge.no/sosi-kodelister/havnedata/apningstype</a></td>
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
      <td>Fjernstyrt</td>
      <td>Fjernstyrt åpning av port eller veibom.</td>
      <td></td>
    </tr>
    <tr>
      <td>Må betjenes</td>
      <td>Åpning av port eller veibom som krever betjening på stedet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td>Annen type åpningsmekanisme.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Ukjent type åpningsmekanisme.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Høydereferanse

**Definisjon:** Angivelse av hvor på objektet koordinatregistreringen er utført.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse">https://register.geonorge.no/sosi-kodelister/havnedata/hoydereferanse</a></td>
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
      <td>Fot</td>
      <td>Høyden målt til foten av objektet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Topp</td>
      <td>Høyden målt til toppen av objektet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Ukjent (benyttes ikke ved nyregistrering).</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Status

**Definisjon:** Angir status til havneobjekt.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/status">https://register.geonorge.no/sosi-kodelister/havnedata/status</a></td>
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
      <td>I bruk</td>
      <td>Objektet er i bruk.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ikke i bruk</td>
      <td>Objektet er ikke i bruk.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skadet</td>
      <td>Objektet er skadet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Planlagt</td>
      <td>Objektet er planlagt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Foreldet</td>
      <td>Objektet er foreldet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Privat</td>
      <td>Privat objekt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Nedlagt</td>
      <td>Nedlagt objekt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjernet</td>
      <td>Objektet er fjernet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Under arbeid</td>
      <td>Objektet er under arbeid.</td>
      <td></td>
    </tr>
    <tr>
      <td>Tilstand uviss</td>
      <td>Ukjent tilstand.</td>
      <td></td>
    </tr>
    <tr>
      <td>I forfall</td>
      <td>Objektet er i forfall.</td>
      <td></td>
    </tr>
    <tr>
      <td>Periodisk</td>
      <td>Periodisk objekt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Midlertidig</td>
      <td>Midlertidig objekt.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Måned

**Definisjon:** Kodeliste over årets måneder.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/maned">https://register.geonorge.no/sosi-kodelister/havnedata/maned</a></td>
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
      <td>Januar</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Februar</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mars</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>April</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mai</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Juni</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Juli</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>August</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>September</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oktober</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>November</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Desember</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Drivstofftype

**Definisjon:** Angir hvilke typer drivstoff som kan fylles.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/drivstofftype">https://register.geonorge.no/sosi-kodelister/havnedata/drivstofftype</a></td>
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
      <td>Diesel</td>
      <td>Mulighet for å fylle diesel.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bensin</td>
      <td>Mulighet for å fylle bensin.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Mulighet for å fylle annen type drivstoff.
Angi ved bruk av informasjonsegenskapen.</td>
      <td></td>
    </tr>
    <tr>
      <td>LNG</td>
      <td>Mulighet for å fylle LNG.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bensin, diesel</td>
      <td>Mulighet for å fylle bensin og diesel.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Tilgangstype

**Definisjon:** Angir tilgang til havneobjekt.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype">https://register.geonorge.no/sosi-kodelister/havnedata/tilgangstype</a></td>
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
      <td>Annet</td>
      <td>Annen tilgang.</td>
      <td></td>
    </tr>
    <tr>
      <td>Leietager</td>
      <td>Tilgang for leietager.</td>
      <td></td>
    </tr>
    <tr>
      <td>Havnedrift</td>
      <td>Tilgang for havnedrift.</td>
      <td></td>
    </tr>
    <tr>
      <td>Alle</td>
      <td>Tilgang for alle.</td>
      <td></td>
    </tr>
    <tr>
      <td>Godsfartøy</td>
      <td>Tilgang for godsfartøy.</td>
      <td></td>
    </tr>
    <tr>
      <td>Alle skip</td>
      <td>Tilgang for alle typer skip eller fartøy.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fiskebåter</td>
      <td>Tilgang for fiskebåter.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fritidsbåter</td>
      <td>Tilgang for fritidsbåter.</td>
      <td></td>
    </tr>
    <tr>
      <td>Cruise fartøy</td>
      <td>Tilgang for cruisefartøy.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet fartøy</td>
      <td>Tilgang for andre fartøy.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Krantype

**Definisjon:** Angir hvilken type kran.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/krantype">https://register.geonorge.no/sosi-kodelister/havnedata/krantype</a></td>
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
      <td>Annen</td>
      <td>Annen type kran.</td>
      <td></td>
    </tr>
    <tr>
      <td>Mobilkran</td>
      <td>Kran som er montert på et kjøretøy.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skinnegående kran</td>
      <td>Kran som går på skinner.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bulk kran</td>
      <td>Kran for bulkhåndtering, med integrert gripe for løfting av bulk masser.</td>
      <td></td>
    </tr>
    <tr>
      <td>Tranverskran</td>
      <td>Kran som kan bevege seg i tre plan (to horisontale og ett vertikalt) og består av en kranbro, med en eller flere løpekatter med et heismaskineri.</td>
      <td></td>
    </tr>
    <tr>
      <td>Havnekran</td>
      <td>Kran som tilhører havnen. Vanligvis montert på kaien.</td>
      <td></td>
    </tr>
    <tr>
      <td>Portalkran</td>
      <td>Kran formet som en portal, med en horisontal bærebjelke. Gantry kraner og stablekraner er portalkraner.</td>
      <td></td>
    </tr>
    <tr>
      <td>Reachstacker</td>
      <td>Kjøretøy for løfting og transport av containere.</td>
      <td></td>
    </tr>
    <tr>
      <td>Svingkran</td>
      <td>Svingbar kran</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Energikilde

**Definisjon:** Kodeliste for å spesifisere energikilden til et objekt, f.eks. kran.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/energikilde">https://register.geonorge.no/sosi-kodelister/havnedata/energikilde</a></td>
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
      <td>Diesel</td>
      <td>Diesel som energikilde.</td>
      <td></td>
    </tr>
    <tr>
      <td>Elektrisk</td>
      <td>Elektrisk tilkobling som energikilde.</td>
      <td></td>
    </tr>
    <tr>
      <td>Batteri</td>
      <td>Batteri som energikilde.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen energikilde.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Kaidekketype

**Definisjon:** Angivelse av ulike typer dekke på kai.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/kaidekketype">https://register.geonorge.no/sosi-kodelister/havnedata/kaidekketype</a></td>
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
      <td>Asfalt</td>
      <td>Asfaltdekke</td>
      <td></td>
    </tr>
    <tr>
      <td>Betong</td>
      <td>Betongdekke</td>
      <td></td>
    </tr>
    <tr>
      <td>Belegningsstein, heller</td>
      <td>Dekke av belegningsstein eller heller.</td>
      <td></td>
    </tr>
    <tr>
      <td>Tredekke</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td>Annet materiale.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Avløpstype

**Definisjon:** Angir hvilken type væske som kan tømmes.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/avlopstype">https://register.geonorge.no/sosi-kodelister/havnedata/avlopstype</a></td>
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
      <td>Gråvann</td>
      <td>Anlegg for mottak av gråvann fra båt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Svartvann</td>
      <td>Anlegg for mottak av svartvann (vann som inneholder olje e.l. og må håndteres spesielt)</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen type for avløp.</td>
      <td></td>
    </tr>
    <tr>
      <td>Septik</td>
      <td>Tømmestasjon med mottak for septik/klokakk.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Bruksklassetype

**Definisjon:** Kodelisten angir bruksklasse på kai. Bruksklassetype er kodeliste for egenskap bruksklasse på objekttype Lastbegrensningsområde. Bruksklassen forkortes Bk og etterfølges av et tall. Den angir største tillatte aksellast, last fra akselkombinasjoner og totalvekt avhengig av avstanden mellom akslene. Som beskrevet i "Forskrift om bruk av kjøretøy" og Statens vegvesen sin håndbok R412.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/bruksklassetype">https://register.geonorge.no/sosi-kodelister/havnedata/bruksklassetype</a></td>
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
      <td>Bk10</td>
      <td>Bruksklasse 10</td>
      <td></td>
    </tr>
    <tr>
      <td>Bk8</td>
      <td>Bruksklasse 8</td>
      <td></td>
    </tr>
    <tr>
      <td>Bk6</td>
      <td>Bruksklasse 6</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen type bruksklasse.</td>
      <td></td>
    </tr>
    <tr>
      <td>BkT8</td>
      <td>BkT er en variant av Bk8. Den har same maksimale aksellast som Bk8, men totalvekten er høyere.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Kaitype

**Definisjon:** Angivelse av ulik bruk av kai.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/kaitype">https://register.geonorge.no/sosi-kodelister/havnedata/kaitype</a></td>
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
      <td>Bulk</td>
      <td>Kai for lasting av våt- eller tørrbulk.</td>
      <td></td>
    </tr>
    <tr>
      <td>Container</td>
      <td>Kai for lasting/lossing av containere.</td>
      <td></td>
    </tr>
    <tr>
      <td>Lo-lo</td>
      <td>Lift-on - lift-off. Lasting og lossing av containere ved hjelp av containerkran.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ro-ro</td>
      <td>Roll-on - roll-off. Kai hvor rullende last kan kjøres ifra kaien og direkte ombord.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fritid</td>
      <td>Mindre kai for fritidsbåter etc.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen type kai. Beskriv ved hjelp av egenskapen informasjon.</td>
      <td></td>
    </tr>
    <tr>
      <td>Lokale ferger</td>
      <td>Kai for lokale ferger.</td>
      <td></td>
    </tr>
    <tr>
      <td>Utland ferger</td>
      <td>Kai for internasjonale ferger.</td>
      <td></td>
    </tr>
    <tr>
      <td>Cruise</td>
      <td>Kai for cruiseskip.</td>
      <td></td>
    </tr>
    <tr>
      <td>Charter</td>
      <td>Kai for charterbåter.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fiskeri</td>
      <td>Fiskerikai</td>
      <td></td>
    </tr>
    <tr>
      <td>Offshore</td>
      <td>Offshorekai</td>
      <td></td>
    </tr>
    <tr>
      <td>Opplag</td>
      <td>Opplagskai</td>
      <td></td>
    </tr>
    <tr>
      <td>Service og reparasjon</td>
      <td>Kai for service og reparasjon.</td>
      <td></td>
    </tr>
    <tr>
      <td>Hurtigbåt</td>
      <td>Kai for hurtigbåt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ventekai</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flerbrukskai</td>
      <td>Flerbrukskai. Spesifiser hvilken bruk under egenskapen informasjon.</td>
      <td></td>
    </tr>
    <tr>
      <td>Trelast</td>
      <td>Kai for trelast eller tømmer.</td>
      <td></td>
    </tr>
    <tr>
      <td>Stein</td>
      <td>Kai for stein eller steinmateriale.</td>
      <td></td>
    </tr>
    <tr>
      <td>Dypvannskai</td>
      <td>Kai anlagt ved dypt vann, slik at dyptgående fartøyer kan legge til.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Beredskapstype

**Definisjon:** Angir type beredskap eller beredskapsutstyr.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/beredskapstype">https://register.geonorge.no/sosi-kodelister/havnedata/beredskapstype</a></td>
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
      <td>Stige</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Redningsbøye</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen type beredskapspunkt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Oljelenser</td>
      <td>Oljelenser. Anretning for å redusere oljesøl som flyter på vannet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Båtshake</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nødplakat, infopunkt</td>
      <td>Nødplakat/infopunkt</td>
      <td></td>
    </tr>
    <tr>
      <td>Angrepsvei</td>
      <td>Tilrettelagt adkomst til en bygning berenget for brannvesenet/beredskap.</td>
      <td></td>
    </tr>
    <tr>
      <td>Brannkum</td>
      <td>Fast montert utstyr i kum, som er beregnet for kopling til brannvesenets utstyr.</td>
      <td></td>
    </tr>
    <tr>
      <td>Samlingsplass</td>
      <td>Oppmøtested ved evakuering ved brannalarm.</td>
      <td></td>
    </tr>
    <tr>
      <td>Nøkkelskap</td>
      <td>Nøkkelskap eller nøkkelsafe for bruk av brannvesenet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Høyspenning</td>
      <td>Anlegg med høyspenning (f.eks. trafo eller tilsvarende).</td>
      <td></td>
    </tr>
    <tr>
      <td>Gass under trykk</td>
      <td>Rom eller bygning hvor beholdere med gass under trykk oppbevares</td>
      <td></td>
    </tr>
    <tr>
      <td>Talevarslingsentral</td>
      <td>Sentral for talevarsling av brann eller annen nødsituasjon.</td>
      <td></td>
    </tr>
    <tr>
      <td>Brannalarmsentral</td>
      <td>Sentralapparatet i et brannalarmsanlegg.</td>
      <td></td>
    </tr>
    <tr>
      <td>Røyklukepanel</td>
      <td>Luke, panel eller annen bygningsdel som skal kunne åpnes eller fjernes for å ventilere ut varme og røyk fra bygning i brann.</td>
      <td></td>
    </tr>
    <tr>
      <td>Sprinklersentral</td>
      <td>Samlet arrangement av ventiler, manometre og annet utstyr som er nødvendig for funksjonen til et sprinkleranlegg.</td>
      <td></td>
    </tr>
    <tr>
      <td>Brannfarlig opplag</td>
      <td>Lager eller oppbevaring av varer/materiale som er brannfarlig.</td>
      <td></td>
    </tr>
    <tr>
      <td>Eksplosjonsfare</td>
      <td>Fare eller risiko for eksplosjon.</td>
      <td></td>
    </tr>
    <tr>
      <td>Førstehjelp</td>
      <td>Førstehjelpsutstyr.</td>
      <td></td>
    </tr>
    <tr>
      <td>Hjertestarter</td>
      <td>En hjertestarter (defibrillator) er førstehjelpsutstyr som kan brukes til å starte hjertet på nytt i tilfeller av hjertestans.</td>
      <td></td>
    </tr>
    <tr>
      <td>Brannslange</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Brannslukningsapparat</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Sensortype

**Definisjon:** Type sensor.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/sensortype">https://register.geonorge.no/sosi-kodelister/havnedata/sensortype</a></td>
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
      <td>Temperatur</td>
      <td>Termometer</td>
      <td></td>
    </tr>
    <tr>
      <td>Vind</td>
      <td>Vindmåler</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen type sensor.</td>
      <td></td>
    </tr>
    <tr>
      <td>Strøm</td>
      <td>Sensor for måling av strøm i vann.</td>
      <td></td>
    </tr>
    <tr>
      <td>Vannstand</td>
      <td>Vannstandsmåler</td>
      <td></td>
    </tr>
    <tr>
      <td>Kamera</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Værstasjon</td>
      <td>Sensor til å måle vind, temperatur, vannstand.</td>
      <td></td>
    </tr>
    <tr>
      <td>Portsensor</td>
      <td>Sensor til overvåkning av port.</td>
      <td></td>
    </tr>
    <tr>
      <td>Dørsensor</td>
      <td>Sensor til overvåkning av dør.</td>
      <td></td>
    </tr>
    <tr>
      <td>Støymåler</td>
      <td>Sensor for måling av støy.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fartsmåler</td>
      <td>Sensor som måler fart til kjøretøy, med fartstavle for visning av fart.</td>
      <td></td>
    </tr>
    <tr>
      <td>Redningsbøyeskapsensor</td>
      <td>Sensor på redningsbøyeskap. Varseler om en redningsbøye er tatt i bruk.</td>
      <td></td>
    </tr>
    <tr>
      <td>Luftkvalitet</td>
      <td>Sensor for måling av luftkvalitet.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» ELanleggstype

**Definisjon:** Type EL-anlegg/strømanlegg.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/el-anleggstype">https://register.geonorge.no/sosi-kodelister/havnedata/el-anleggstype</a></td>
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
      <td>Strømskap</td>
      <td>Strømskap med diverse tilkoblingsmuligheter.</td>
      <td></td>
    </tr>
    <tr>
      <td>Landstrøm</td>
      <td>Landstrømanlegg.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen type strømanlegg.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ladeanlegg</td>
      <td>Strømanlegget brukes til lading.</td>
      <td></td>
    </tr>
    <tr>
      <td>Strømtilførsel kran</td>
      <td>EL-anlegg hvor det er mulig å koble til strømtilførsel for kran.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Frekvens

**Definisjon:** Angir frekvensen for EL-koblingen, som er hvor mange ganger en elektrisk spenning veksler i løpet av ett sekund. Måles i Hz.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/frekvens">https://register.geonorge.no/sosi-kodelister/havnedata/frekvens</a></td>
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
      <td>50 Hz</td>
      <td>Frekvens 50 Hz.</td>
      <td></td>
    </tr>
    <tr>
      <td>60 Hz</td>
      <td>Frekvens 60 Hz.</td>
      <td></td>
    </tr>
    <tr>
      <td>Likestrøm</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Ukjent frekvens</td>
      <td></td>
    </tr>
    <tr>
      <td>50 eller 60 Hz</td>
      <td>Kontakt som kan levere frekvens på 50 eller 60 Hz.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Spenning

**Definisjon:** Kodeliste for å angi den eletriske spenningen. Måleenhet i volt.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/spenning">https://register.geonorge.no/sosi-kodelister/havnedata/spenning</a></td>
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
      <td>230V</td>
      <td>230 Volt</td>
      <td></td>
    </tr>
    <tr>
      <td>400V</td>
      <td>400 Volt</td>
      <td></td>
    </tr>
    <tr>
      <td>690V</td>
      <td>690 Volt</td>
      <td></td>
    </tr>
    <tr>
      <td>11000V</td>
      <td>Høyspenning, 11kV.</td>
      <td></td>
    </tr>
    <tr>
      <td>22000V</td>
      <td>Høyspenning 22 kV.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Ukjent spenning.</td>
      <td></td>
    </tr>
    <tr>
      <td>440V</td>
      <td>440 Volt</td>
      <td></td>
    </tr>
    <tr>
      <td>6600V</td>
      <td>Høyspenning 6,6 kV.</td>
      <td></td>
    </tr>
    <tr>
      <td>440V eller 690V</td>
      <td>Kontakt som kan levere 440V eller 690V over samme kontakt.</td>
      <td></td>
    </tr>
    <tr>
      <td>6600V eller 11000V</td>
      <td>Høyspenning. Kontakt som kan levere 6.6kV eller 11kV over samme kontakt.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Fendertype

**Definisjon:** Angivelse av ulike fendertyper.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/fendertype">https://register.geonorge.no/sosi-kodelister/havnedata/fendertype</a></td>
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
      <td>Firkantet fender</td>
      <td>Firkantet fender.</td>
      <td></td>
    </tr>
    <tr>
      <td>D-fender</td>
      <td>Gummirør med D-formet tverrsnitt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bildekkfender</td>
      <td>Fender av bildekk.</td>
      <td></td>
    </tr>
    <tr>
      <td>Slepebåtfender</td>
      <td>Slepebåtfender.</td>
      <td></td>
    </tr>
    <tr>
      <td>Rullefender</td>
      <td>Rullende fender.</td>
      <td></td>
    </tr>
    <tr>
      <td>Rund fender</td>
      <td>Rund fender.</td>
      <td></td>
    </tr>
    <tr>
      <td>PUR-fender</td>
      <td>Fender av polyuretan.</td>
      <td></td>
    </tr>
    <tr>
      <td>Flytefender</td>
      <td>Flytende fender.</td>
      <td></td>
    </tr>
    <tr>
      <td>Pneumatisk fender</td>
      <td>Stor pølseformet flytende gummifender fylt med høytrykksluft, ofte dekket av hjul.</td>
      <td></td>
    </tr>
    <tr>
      <td>Conefender</td>
      <td>Kjegleformet fender som står vertikalt ut fra kaien, med en flense på toppen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Sirkelfender</td>
      <td>Sirkel- eller halvsirkel-formet fender.</td>
      <td></td>
    </tr>
    <tr>
      <td>Trapesfender</td>
      <td>Trapesformet fender.</td>
      <td></td>
    </tr>
    <tr>
      <td>V-fender</td>
      <td>Fender med V-formet tverrsnitt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Torsjonsfender</td>
      <td>Fender som har en torsjonsfjæroppheng/torsjonsarm.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bunnfundamentert fender</td>
      <td>Fender som er bunnfundamentert.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fenderpanel</td>
      <td>Fender som et panel.</td>
      <td></td>
    </tr>
    <tr>
      <td>Dumperdekk</td>
      <td>Fender av bildekk fra dumpere.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen fender</td>
      <td>Annen type fender.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Fenderorientering

**Definisjon:** Angir orientering til fender.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/fenderorientering">https://register.geonorge.no/sosi-kodelister/havnedata/fenderorientering</a></td>
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
      <td>Annen orientering</td>
      <td>Annen orientering.</td>
      <td></td>
    </tr>
    <tr>
      <td>Stående fender</td>
      <td>Stående fender.</td>
      <td></td>
    </tr>
    <tr>
      <td>Liggende fender</td>
      <td>Liggende fender.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» VAuttakstype

**Definisjon:** Type vanntilkobling som kan gjøres.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/va-uttakstype">https://register.geonorge.no/sosi-kodelister/havnedata/va-uttakstype</a></td>
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
      <td>Ferskvann</td>
      <td>Ferskvann/drikkevann til påfylling på båt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen type for VA-uttak.
Spesifiseres ved bruk av egenskapen informasjon.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Avfallstype

**Definisjon:** Angir type avfall.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/avfallstype">https://register.geonorge.no/sosi-kodelister/havnedata/avfallstype</a></td>
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
      <td>Annet</td>
      <td>Annen type avfall.</td>
      <td></td>
    </tr>
    <tr>
      <td>Papp, papir, kartong</td>
      <td>Avfallspunkt for papp, papir eller kartong.</td>
      <td></td>
    </tr>
    <tr>
      <td>Matavfall</td>
      <td>Avfallspunkt for matavfall.</td>
      <td></td>
    </tr>
    <tr>
      <td>Plast</td>
      <td>Avfallspunkt for plast.</td>
      <td></td>
    </tr>
    <tr>
      <td>Glass</td>
      <td>Avfallspunkt for glass.</td>
      <td></td>
    </tr>
    <tr>
      <td>Metall</td>
      <td>Avfallspunkt for metall.</td>
      <td></td>
    </tr>
    <tr>
      <td>Restavfall</td>
      <td>Avfallspunkt for restavfall.</td>
      <td></td>
    </tr>
    <tr>
      <td>Oljeholdig avfall</td>
      <td>Avfallspunkt for oljeholdig avfall.</td>
      <td></td>
    </tr>
    <tr>
      <td>Lyspærer</td>
      <td>Avfallspunkt for lyspærer.</td>
      <td></td>
    </tr>
    <tr>
      <td>EE-avfall</td>
      <td>Avfallspunkt for elektriske og elektroniske produkter. Inkludert lysrør.</td>
      <td></td>
    </tr>
    <tr>
      <td>Maling</td>
      <td>Avfallspunkt for maling.</td>
      <td></td>
    </tr>
    <tr>
      <td>Asfalt</td>
      <td>Avfallspunkt for asfalt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Stein</td>
      <td>Avfallspunkt for stein.</td>
      <td></td>
    </tr>
    <tr>
      <td>Impregnert tre</td>
      <td>Avfallspunkt for impregnert tre.</td>
      <td></td>
    </tr>
    <tr>
      <td>Batterier</td>
      <td>Avfallspunkt for batterier.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Beholdertype

**Definisjon:** Angir type avfallsbeholder.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/beholdertype">https://register.geonorge.no/sosi-kodelister/havnedata/beholdertype</a></td>
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
      <td>Annet</td>
      <td>Annen type avfallsbeholder.</td>
      <td></td>
    </tr>
    <tr>
      <td>Avfallsbeholder</td>
      <td>Avfallsbeholder.</td>
      <td></td>
    </tr>
    <tr>
      <td>Nedgravd avfallsløsning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Søppelbøtte</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Container</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Fortøyningstype

**Definisjon:** Type fortøyningsinnretning.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/fortoyningstype">https://register.geonorge.no/sosi-kodelister/havnedata/fortoyningstype</a></td>
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
      <td>Ring</td>
      <td>Fortøyningsring</td>
      <td></td>
    </tr>
    <tr>
      <td>Pullert</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Slipphake</td>
      <td>Krok med hengsel og en bøyle som kan slås til side for å åpnes.</td>
      <td></td>
    </tr>
    <tr>
      <td>Mantel</td>
      <td>Søyleformet pullert. Trosser kan festes i hvilken som helst retning ut fra mantel.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bøye</td>
      <td>Fortøyningsbøye</td>
      <td></td>
    </tr>
    <tr>
      <td>Dykdalb</td>
      <td>Bunt av stokker eller påler som er drevet ned i sjøbunnen, og som fartøy kan fortøyes i. De plasseres ofte i forlengelsen av en kaifront for å gjøre det mulig å fotøye skip som er lengre enn kaia.</td>
      <td></td>
    </tr>
    <tr>
      <td>Kabel, wire</td>
      <td>Kabel eller wire som kan brukes til fortøyning.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen type fortøyningsinnretning.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Kaifronttype

**Definisjon:** Ulike typer kaifronter. Beskriver kaifronten sin konstruksjon mot sjøen.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/kaifronttype">https://register.geonorge.no/sosi-kodelister/havnedata/kaifronttype</a></td>
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
      <td>Kai</td>
      <td>Konstruksjon, vanligvis parallell med kystkonturen, hvor fartøy kan fortøye eller laste/losse. Horisontalt plan.</td>
      <td></td>
    </tr>
    <tr>
      <td>Rampe</td>
      <td>Trinnfritt skråplan som fungerer som forbindelse mellom to horisontale plan som ikke ligger på samme nivå. Brukes ofte til i landkjøring av rullende objekter (ro-ro). Stopper ved vannkant.</td>
      <td></td>
    </tr>
    <tr>
      <td>Slipp</td>
      <td>Bane som fartøy kan hales opp ved landsetting, fra flytende posisjon og opp på tørt land. Skråplanet går vanligvis ut og ned i vannet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Trapp</td>
      <td>Kai hvor trappetrinn er en del av kaikonstruksjonen eller utgjør den ytterste delen på kaien.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen</td>
      <td>Annen type kaifront.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ro-ro rampe</td>
      <td>(Roll on/roll off) justerbar rampe eller ombordkjøringsplattform, tilsvarende ferjelem, som er tilpasset for at rullende last kan kjøres fra kai og direkte om bord.</td>
      <td></td>
    </tr>
    <tr>
      <td>Spunt</td>
      <td>Støttekonstruksjon som settes opp som en vegg for å holde på plass løsmasser fra sjø.</td>
      <td></td>
    </tr>
    <tr>
      <td>Søylekai</td>
      <td>Kai på pæler eller søyler.</td>
      <td></td>
    </tr>
    <tr>
      <td>Mur</td>
      <td>Kai som er steinmurt eller konstruert av mur.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Ukjent kaifronttype.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Datafangstmetode

**Definisjon:** Metode for datafangst. Datafangstmetoden beskriver hvordan selve vektordataene er posisjonert fra et datagrunnlag (observasjoner med landmålingsutstyr, fotogrammetrisk stereomodell, digital terrengmodell etc.) og ikke prosessen med å innhente det bakenforliggende datagrunnlaget.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/datafangstmetode">https://register.geonorge.no/sosi-kodelister/havnedata/datafangstmetode</a></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Synbarhet

**Definisjon:** hvor godt den kartlagte detalj var synbar ved kartleggingen

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/synbarhet">https://register.geonorge.no/sosi-kodelister/havnedata/synbarhet</a></td>
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
      <td>Fullt ut synlig/gjenfinnbar i terrenget</td>
      <td>Fullt ut synlig/gjenfinnbar i terrenget (default-verdi).</td>
      <td></td>
    </tr>
    <tr>
      <td>Dårlig gjenfinnbar i terreng</td>
      <td>Forøvrig grei å innmåle. (Benyttes bl.a. for innmåling av ledninger på lukket grøft).</td>
      <td></td>
    </tr>
    <tr>
      <td>Middels synlig i flybilde/modell</td>
      <td>Middels synlig i flybilde/modell.</td>
      <td></td>
    </tr>
    <tr>
      <td>Dårlig/ikke synlig i flybilde/modell</td>
      <td>Dårlig/ikke synlig i flybilde/modell.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Fartøytype

**Definisjon:** Kodeliste for å spesifisere hvilket type fartøy en regulering eller restriksjon omfatter.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/fartoytype">https://register.geonorge.no/sosi-kodelister/havnedata/fartoytype</a></td>
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
      <td>Alle</td>
      <td>Alle flytende innretninger som er laget for å bevege seg igjennom vannet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fritidsfartøy under 24 m</td>
      <td>Fartøy som ikke brukes til nyttetrafikk og er under24 meter.</td>
      <td></td>
    </tr>
    <tr>
      <td>Vannscooter</td>
      <td>Farkost med skroglengde mindre enn 4 meter, utstyrt med innenbords forbrenningsmotor som driver et vannjetaggregat som hovedfremkomstmiddel.</td>
      <td></td>
    </tr>
    <tr>
      <td>Nyttefartøy</td>
      <td>Fartøy som brukes til nyttetrafikk eller i næring.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td>Annen type.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Forbudstype

**Definisjon:** Kodeliste for å angi forbudstype for forbudsområde.

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/havnedata/forbudstype">https://register.geonorge.no/sosi-kodelister/havnedata/forbudstype</a></td>
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
      <td>Ferdsel</td>
      <td>Forbud mot ferdsel.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ankring</td>
      <td>Forbud mot ankring.</td>
      <td></td>
    </tr>
    <tr>
      <td>Dykking</td>
      <td>Forbud mot dykking.</td>
      <td></td>
    </tr>
    <tr>
      <td>Tømming</td>
      <td>Forbud mot tømming eller dumping.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fisking</td>
      <td>Forbud mot fisking.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td>Annet forbud.</td>
      <td></td>
    </tr>
    <tr>
      <td>Snøtømming</td>
      <td>Forbud mot snøtømming.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Ukjent forbud.</td>
      <td></td>
    </tr>
  </tbody>
</table>
