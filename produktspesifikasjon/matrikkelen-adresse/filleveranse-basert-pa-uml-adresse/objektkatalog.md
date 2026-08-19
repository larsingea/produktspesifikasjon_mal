### Datamodell

**Kilde:** [SOSI UML XMI-fil](https://sosi.geonorge.no/svn/SOSI/SOSI%20Del%203/Matrikkelen/Matrikkelen-Adresse.xml)

<a href="filleveranse-basert-pa-uml-adresse_feature_catalogue.png" title="Klikk for stor visning"><img src="filleveranse-basert-pa-uml-adresse_feature_catalogue.png" alt="Datamodell Filleveranse basert på UML adresse" style="max-width: 100%; height: auto;" /></a>

#### SOSI_Objekt-Adresse (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er fagområde-uavhengige og kan benyttes for alle objekttyper<br /><br />Merknad:<br />Spesielt i produktspesifikasjonsarbeid vil en velge egenskaper og av grensningslinjer fra denne klassen.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>datauttaksdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for uttak fra en database<br /><br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
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
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />NOTE: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
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
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />NOTE 1 : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
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
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterers. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />NOTE Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
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
      <td>dato for siste endring på objektetdataene<br /><br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
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
      <td><strong>stedfestingVerifisert</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse om stedfestingen (koordinatene) er  kontrollert  og funnet i orden (verifisert)</td>
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

#### Adresse (abstrakt)

Matrikkelforskriften § 2d definerer den offisielle adressen som den fullstendige adressen for en<br />bygning, bygningsendring, bruksenhet, eiendom eller annet objekt som er registrert med adresse i matrikkelen.<br />I den offisielle adressen vil bruksenhetsnummer (for bolig eller annen bruksenhet) inngå når dette er nødvendig for å oppnå unik adresse.<br /><br />Merknad: Adresse realiseres enten som Vegadresse eller Matrikkeladresse

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>adresseTekst</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Del av offisiell adresse, men uten bruksenhetsnummer for adresser som ligger til bruksenheter/boliger<br /><br />Vegadresse:<br />,<br />ev= hvis fins. Hvis ikke skal formateringstegn utgå foran/bak.<br /><br />Matrikkeladresse:<br />, //-<br />ev= hvis fins. Hvis ikke skal formateringstegn utgå foran/bak.<br /><br />Eksempel:<br />"Storgata 2B" eller "123/4-2"<br />Der det i tillegg er adressetilleggsnavn:<br />"Haugen, Storgata 2B" eller "Midtgard, 123/4-2"<br /><br />Merknad:<br />Adressene er unike innenfor en kommune.<br /><br />Merknad2: Adressetilleggsnavn av typen "Matrikkeladressenavn" kan inneholde andre ting enn adressetilleggsnavn</td>
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
      <td><strong>adresseTekstUtenAdressetilleggsnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Del av offisiell adresse, men uten bruksenhetsnummer for adresser som ligger til bruksenheter/boliger, - og uten eventuelle adressetilleggsnavn<br /><br />Vegadresse:<br /><br />ev= hvis fins. Hvis ikke skal formateringstegn utgå foran/bak.<br /><br />Matrikkeladresse:<br />//-<br />ev= hvis fins. Hvis ikke skal formateringstegn utgå foran/bak.<br /><br />Eksempel:<br />"Fjellvegen 2B" eller "12/4"<br />"Storgata 3" eller "12/5/3-2"</td>
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
      <td><strong>adressetilleggsnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Nedarvet bruksnavn, navn på en institusjon eller bygning eller grend brukt som del av den offisielle adressen<br /><br />Merknad:<br />Eier kan kreve og kommunen kan tildele adressetilleggsnavn til en offisiell adresse etter vilkår i matrikkelforskriften § 54  og § 55. Hvilken regel den er tildelt etter skal registreres i matrikkelen (adressetilleggsnavnkilde)</td>
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
      <td><strong>adressetilleggsnavnKilde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>opprinnelsen til adressetilleggsnavnet (§§ 54 og 55 i matrikkelforskriften)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>AdressetilleggsnavnKildeKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- anmodetAvHjemmelshaver – &lt;font color="#333333"&gt;Når adressen gjelder en særlig kjent institusjon eller bygning og allmenne hensyn taler for det, kan kommunen på anmodning fra registrert eier fastsette at den offisielle adressen også skal omfatte et navn på institusjonen eller bygningen (&lt;/font&gt;matrikkelforskriftens § 54 2. ledd)<br />- ikkeOppgitt – "Ikke oppgitt" brukes på adresser uten adressetilleggsnavn.<br />- krevdAvEier – &lt;font color="#333333"&gt;Når adressen gjelder et gårdsbruk, kan den som har grunnbokshjemmel til eiendommen som eier, kreve at den offisielle adressen også skal omfatte gårdens bruksnavn, dersom navnet faller språklig og geografisk sammen med et nedarvet stedsnavn, jf. lov 18. mai 1990 nr. 11 om stadnamn (&lt;/font&gt;matrikkelforskriftens § 54 1. ledd)<br />- matrikkeladressenavn – &lt;font color="#333333"&gt;Adresser i område med matrikkeladresser som ikke har tildelt et adressetilleggsnavn etter reglene i § 54, kan tilordnes et matrikkeladressenavn etter &lt;/font&gt;matrikkelforskriftens § 55 3. ledd. Hvis det tildeles adressetilleggsnavn etter § 54 strykes matrikkeladressenavnet<br />- tildeltAvKommunen – &lt;font color="#333333"&gt;Kommunen kan tildele adresser innenfor mindre grender, bolig- eller hyttefelt eller andre avgrensede områder et felles adressetilleggsnavn (&lt;/font&gt;Matrikkelforskriftens § 54 3. ledd, men tildeling etter 1. eller 2. ledd går foran 3. ledd)</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>bruksenhetsnummerTekst</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Del av offisiell adresse (bruksenhetsnummer) til en bruksenhet, f.eks en leilighet i flerboligbygg.<br /><br />Merknad:<br />Bokstaven og de to første tallene angir hvilken etasje leiligheten ligger i, og de to siste angir leilighetens nummer i etasjen, regnet fra venstre mot høyre.<br /><br />Eksempel: "H0102", "K0101"</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
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
      <td><strong>grunnkrets</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>adressens knytning til grunnkrets. Grunnkrets er den minste geografiske enhet det blir beregnet statistikk på<br /><br />Merknad:<br />En kommune er delt inn i flere grunnkretser.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GrunnkretsId</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>grunnkrets.grunnkretsnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>offisielt navn fra grunnkretskatalogen til SSB</td>
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
      <td><strong>grunnkrets.grunnkretsnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>består av 8 siffer, hvor de fire første er kommunenummer, de to neste er delområdenummer og de to siste angir grunnkrets<br /><br />Merknad:<br />Det skal benyttes ledende nuller.<br /><br />Grunnkretskatalogen utgis og ajourføres av SSB, og er den offisielle listen over grunnkretser.</td>
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
      <td><strong>kommunenavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn (norsk) på en kommune</td>
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
      <td>nummerering av kommunen i henhold til Statistisk sentralbyrå sin offisielle liste<br /><br />Merknad: Det presiseres at kommunenummer alltid skal ha 4 siffer, dvs. eventuelt med ledende null.</td>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/SOSI/kodeliste/AdmEnheter/2019/Kommunenummer">http://skjema.geonorge.no/SOSI/kodeliste/AdmEnheter/2019/Kommunenummer</a><br />- 0101 – Halden<br />- 0102 – Sarpsborg (utgått)<br />- 0103 – Fredrikstad (utgått)<br />- 0104 – Moss<br />- 0105 – Sarpsborg<br />- 0106 – Fredrikstad<br />- 0111 – Hvaler<br />- 0113 – Borge (utgått)<br />- 0114 – Varteig (utgått)<br />- 0115 – Skjeberg (utgått)<br />- 0118 – Aremark<br />- 0119 – Marker<br />- 0121 – Rømskog<br />- 0122 – Trøgstad<br />- 0123 – Spydeberg<br />- 0124 – Askim<br />- 0125 – Eidsberg<br />- 0127 – Skiptvet<br />- 0128 – Rakkestad<br />- 0130 – Tune (utgått)<br />- 0131 – Rolvsøy (utgått)<br />- 0133 – Kråkerøy (utgått)<br />- 0134 – Onsøy (utgått)<br />- 0135 – Råde<br />- 0136 – Rygge<br />- 0137 – Våler i Østfold<br />- 0138 – Hobøl<br />- 0211 – Vestby<br />- 0213 – Ski<br />- 0214 – Ås<br />- 0215 – Frogn<br />- 0216 – Nesodden<br />- 0217 – Oppegård<br />- 0219 – Bærum<br />- 0220 – Asker<br />- 0221 – Aurskog-Høland<br />- 0226 – Sørum<br />- 0227 – Fet<br />- 0228 – Rælingen<br />- 0229 – Enebakk<br />- 0230 – Lørenskog<br />- 0231 – Skedsmo<br />- 0233 – Nittedal<br />- 0234 – Gjerdrum<br />- 0235 – Ullensaker<br />- 0236 – Nes i Akershus<br />- 0237 – Eidsvoll<br />- 0238 – Nannestad<br />- 0239 – Hurdal<br />- 0301 – Oslo<br />- 0401 – Hamar (utgått)<br />- 0402 – Kongsvinger<br />- 0403 – Hamar<br />- 0412 – Ringsaker<br />- 0414 – Vang (utgått)<br />- 0415 – Løten<br />- 0417 – Stange<br />- 0418 – Nord-Odal<br />- 0419 – Sør-Odal<br />- 0420 – Eidskog<br />- 0423 – Grue<br />- 0425 – Åsnes<br />- 0426 – Våler i Hedmark<br />- 0427 – Elverum<br />- 0428 – Trysil<br />- 0429 – Åmot<br />- 0430 – Stor-Elvdal<br />- 0432 – Rendalen<br />- 0434 – Engerdal<br />- 0436 – Tolga<br />- 0437 – Tynset<br />- 0438 – Alvdal<br />- 0439 – Folldal<br />- 0441 – Os i Hedmark<br />- 0501 – Lillehammer<br />- 0502 – Gjøvik<br />- 0511 – Dovre<br />- 0512 – Lesja<br />- 0513 – Skjåk<br />- 0514 – Lom<br />- 0515 – Vågå<br />- 0516 – Nord-Fron<br />- 0517 – Sel<br />- 0519 – Sør-Fron<br />- 0520 – Ringebu<br />- 0521 – Øyer<br />- 0522 – Gausdal<br />- 0528 – Østre Toten<br />- 0529 – Vestre Toten<br />- 0532 – Jevnaker<br />- 0533 – Lunner<br />- 0534 – Gran<br />- 0536 – Søndre Land<br />- 0538 – Nordre Land<br />- 0540 – Sør-Aurdal<br />- 0541 – Etnedal<br />- 0542 – Nord-Aurdal<br />- 0543 – Vestre Slidre<br />- 0544 – Øystre Slidre<br />- 0545 – Vang<br />- 0602 – Drammen<br />- 0604 – Kongsberg<br />- 0605 – Ringerike<br />- 0612 – Hole<br />- 0615 – Flå<br />- 0616 – Nes i Buskerud<br />- 0617 – Gol<br />- 0618 – Hemsedal<br />- 0619 – Ål<br />- 0620 – Hol<br />- 0621 – Sigdal<br />- 0622 – Krødsherad<br />- 0623 – Modum<br />- 0624 – Øvre Eiker<br />- 0625 – Nedre Eiker<br />- 0626 – Lier<br />- 0627 – Røyken<br />- 0628 – Hurum<br />- 0631 – Flesberg<br />- 0632 – Rollag<br />- 0633 – Nore og Uvdal<br />- 0701 – Horten<br />- 0702 – Holmestrand (utgått)<br />- 0703 – Horten (utgått)<br />- 0704 – Tønsberg<br />- 0705 – Tønsberg (utgått)<br />- 0706 – Sandefjord (utgått)<br />- 0707 – Larvik (utgått)<br />- 0708 – Stavern (utgått)<br />- 0709 – Larvik (utgått)<br />- 0710 – Sandefjord<br />- 0711 – Svelvik<br />- 0712 – Larvik<br />- 0713 – Sande i Vestfold<br />- 0714 – Hof (utgått)<br />- 0715 – Holmestrand<br />- 0716 – Re<br />- 0717 – Borre (utgått)<br />- 0718 – Ramnes (utgått)<br />- 0719 – Andebu (utgått)<br />- 0720 – Stokke (utgått)<br />- 0721 – Sem (utgått)<br />- 0722 – Nøtterøy (utgått)<br />- 0723 – Tjøme (utgått)<br />- 0725 – Tjølling (utgått)<br />- 0726 – Brunlanes (utgått)<br />- 0727 – Hedrum (utgått)<br />- 0728 – Lardal (utgått)<br />- 0729 – Færder<br />- 0805 – Porsgrunn<br />- 0806 – Skien<br />- 0807 – Notodden<br />- 0811 – Siljan<br />- 0814 – Bamble<br />- 0815 – Kragerø<br />- 0817 – Drangedal<br />- 0819 – Nome<br />- 0821 – Bø i Telemark<br />- 0822 – Sauherad<br />- 0826 – Tinn<br />- 0827 – Hjartdal<br />- 0828 – Seljord<br />- 0829 – Kviteseid<br />- 0830 – Nissedal<br />- 0831 – Fyresdal<br />- 0833 – Tokke<br />- 0834 – Vinje<br />- 0901 – Risør<br />- 0903 – Arendal (utgått)<br />- 0904 – Grimstad<br />- 0906 – Arendal<br />- 0911 – Gjerstad<br />- 0912 – Vegårshei<br />- 0914 – Tvedestrand<br />- 0918 – Moland (utgått)<br />- 0919 – Froland<br />- 0920 – Øyestad (utgått)<br />- 0921 – Tromøy (utgått)<br />- 0922 – Hisøy (utgått)<br />- 0926 – Lillesand<br />- 0928 – Birkenes<br />- 0929 – Åmli<br />- 0935 – Iveland<br />- 0937 – Evje og Hornnes<br />- 0938 – Bygland<br />- 0940 – Valle<br />- 0941 – Bykle<br />- 1001 – Kristiansand<br />- 1002 – Mandal<br />- 1003 – Farsund<br />- 1004 – Flekkefjord<br />- 1014 – Vennesla<br />- 1017 – Songdalen<br />- 1018 – Søgne<br />- 1021 – Marnardal<br />- 1026 – Åseral<br />- 1027 – Audnedal<br />- 1029 – Lindesnes<br />- 1032 – Lyngdal<br />- 1034 – Hægebostad<br />- 1037 – Kvinesdal<br />- 1046 – Sirdal<br />- 1101 – Eigersund<br />- 1102 – Sandnes<br />- 1103 – Stavanger<br />- 1106 – Haugesund<br />- 1111 – Sokndal<br />- 1112 – Lund<br />- 1114 – Bjerkreim<br />- 1119 – Hå<br />- 1120 – Klepp<br />- 1121 – Time<br />- 1122 – Gjesdal<br />- 1124 – Sola<br />- 1127 – Randaberg<br />- 1129 – Forsand<br />- 1130 – Strand<br />- 1133 – Hjelmeland<br />- 1134 – Suldal<br />- 1135 – Sauda<br />- 1141 – Finnøy<br />- 1142 – Rennesøy<br />- 1144 – Kvitsøy<br />- 1145 – Bokn<br />- 1146 – Tysvær<br />- 1149 – Karmøy<br />- 1151 – Utsira<br />- 1154 – Vindafjord ((utgått)<br />- 1159 – Ølen (utgått)<br />- 1160 – Vindafjord<br />- 1201 – Bergen<br />- 1211 – Etne<br />- 1214 – Ølen (utgått)<br />- 1216 – Sveio<br />- 1219 – Bømlo<br />- 1221 – Stord<br />- 1222 – Fitjar<br />- 1223 – Tysnes<br />- 1224 – Kvinnherad<br />- 1227 – Jondal<br />- 1228 – Odda<br />- 1231 – Ullensvang<br />- 1232 – Eidfjord<br />- 1233 – Ulvik<br />- 1234 – Granvin<br />- 1235 – Voss<br />- 1238 – Kvam<br />- 1241 – Fusa<br />- 1242 – Samnanger<br />- 1243 – Os i Hordaland<br />- 1244 – Austevoll<br />- 1245 – Sund<br />- 1246 – Fjell<br />- 1247 – Askøy<br />- 1251 – Vaksdal<br />- 1252 – Modalen<br />- 1253 – Osterøy<br />- 1256 – Meland<br />- 1259 – Øygarden<br />- 1260 – Radøy<br />- 1263 – Lindås<br />- 1264 – Austrheim<br />- 1265 – Fedje<br />- 1266 – Masfjorden<br />- 1401 – Flora<br />- 1411 – Gulen<br />- 1412 – Solund<br />- 1413 – Hyllestad<br />- 1416 – Høyanger<br />- 1417 – Vik<br />- 1418 – Balestrand<br />- 1419 – Leikanger<br />- 1420 – Sogndal<br />- 1421 – Aurland<br />- 1422 – Lærdal<br />- 1424 – Årdal<br />- 1426 – Luster<br />- 1428 – Askvoll<br />- 1429 – Fjaler<br />- 1430 – Gaular<br />- 1431 – Jølster<br />- 1432 – Førde<br />- 1433 – Naustdal<br />- 1438 – Bremanger<br />- 1439 – Vågsøy<br />- 1441 – Selje<br />- 1443 – Eid<br />- 1444 – Hornindal<br />- 1445 – Gloppen<br />- 1449 – Stryn<br />- 1502 – Molde<br />- 1504 – Ålesund<br />- 1505 – Kristiansund<br />- 1511 – Vanylven<br />- 1514 – Sande i Møre og Romsdal<br />- 1515 – Herøy i Møre og Romsdal<br />- 1516 – Ulstein<br />- 1517 – Hareid<br />- 1519 – Volda<br />- 1520 – Ørsta<br />- 1523 – Ørskog<br />- 1524 – Norddal<br />- 1525 – Stranda<br />- 1526 – Stordal<br />- 1528 – Sykkylven<br />- 1529 – Skodje<br />- 1531 – Sula<br />- 1532 – Giske<br />- 1534 – Haram<br />- 1535 – Vestnes<br />- 1539 – Rauma<br />- 1543 – Nesset<br />- 1545 – Midsund<br />- 1546 – Sandøy<br />- 1547 – Aukra<br />- 1548 – Fræna<br />- 1551 – Eide<br />- 1554 – Averøy<br />- 1557 – Gjemnes<br />- 1560 – Tingvoll<br />- 1563 – Sunndal<br />- 1566 – Surnadal<br />- 1567 – Rindal (utgått)<br />- 1569 – Aure (utgått)<br />- 1571 – Halsa<br />- 1572 – Tustna (utgått)<br />- 1573 – Smøla<br />- 1576 – Aure<br />- 1601 – Trondheim (utgått)<br />- 1612 – Hemne (utgått)<br />- 1613 – Snillfjord (utgått)<br />- 1617 – Hitra (utgått)<br />- 1620 – Frøya (utgått)<br />- 1621 – Ørland (utgått)<br />- 1622 – Agdenes (utgått)<br />- 1624 – Rissa (utgått)<br />- 1627 – Bjugn (utgått)<br />- 1630 – Åfjord (utgått)<br />- 1632 – Roan (utgått)<br />- 1633 – Osen (utgått)<br />- 1634 – Oppdal (utgått)<br />- 1635 – Rennebu (utgått)<br />- 1636 – Meldal (utgått)<br />- 1638 – Orkdal (utgått)<br />- 1640 – Røros (utgått)<br />- 1644 – Holtålen (utgått)<br />- 1648 – Midtre Gauldal (utgått)<br />- 1653 – Melhus (utgått)<br />- 1657 – Skaun (utgått)<br />- 1662 – Klæbu (utgått)<br />- 1663 – Malvik (utgått)<br />- 1664 – Selbu (utgått)<br />- 1665 – Tydal (utgått)<br />- 1702 – Steinkjer (utgått)<br />- 1703 – Namsos (utgått)<br />- 1711 – Meråker (utgått)<br />- 1714 – Stjørdal (utgått)<br />- 1717 – Frosta (utgått)<br />- 1718 – Leksvik (utgått)<br />- 1719 – Levanger (utgått)<br />- 1721 – Verdal (utgått)<br />- 1723 – Mosvik (utgått)<br />- 1724 – Verran (utgått)<br />- 1725 – Namdalseid (utgått)<br />- 1729 – Inderøy (utgått)<br />- 1736 – Snåase – Snåsa (utgått)<br />- 1738 – Lierne (utgått)<br />- 1739 – Raarvihke – Røyrvik (utgått)<br />- 1740 – Namsskogan (utgått)<br />- 1742 – Grong (utgått)<br />- 1743 – Høylandet (utgått)<br />- 1744 – Overhalla (utgått)<br />- 1748 – Fosnes (utgått)<br />- 1749 – Flatanger (utgått)<br />- 1750 – Vikna (utgått)<br />- 1751 – Nærøy (utgått)<br />- 1755 – Leka (utgått)<br />- 1756 – Inderøy (utgått)<br />- 1804 – Bodø<br />- 1805 – Narvik<br />- 1811 – Bindal<br />- 1812 – Sømna<br />- 1813 – Brønnøy<br />- 1815 – Vega<br />- 1816 – Vevelstad<br />- 1818 – Herøy i Nordland<br />- 1820 – Alstahaug<br />- 1822 – Leirfjord<br />- 1824 – Vefsn<br />- 1825 – Grane<br />- 1826 – Hattfjelldal<br />- 1827 – Dønna<br />- 1828 – Nesna<br />- 1832 – Hemnes<br />- 1833 – Rana<br />- 1834 – Lurøy<br />- 1835 – Træna<br />- 1836 – Rødøy<br />- 1837 – Meløy<br />- 1838 – Gildeskål<br />- 1839 – Beiarn<br />- 1840 – Saltdal<br />- 1841 – Fauske – Fuossko<br />- 1842 – Skjerstad (utgått)<br />- 1845 – Sørfold<br />- 1848 – Steigen<br />- 1849 – Hamarøy – Hábmer<br />- 1850 – Divtasvuodna – Tysfjord<br />- 1851 – Lødingen<br />- 1852 – Tjeldsund<br />- 1853 – Evenes<br />- 1854 – Ballangen<br />- 1856 – Røst<br />- 1857 – Værøy<br />- 1859 – Flakstad<br />- 1860 – Vestvågøy<br />- 1865 – Vågan<br />- 1866 – Hadsel<br />- 1867 – Bø i Nordland<br />- 1868 – Øksnes<br />- 1870 – Sortland – Suortá<br />- 1871 – Andøy<br />- 1874 – Moskenes<br />- 1901 – Harstad (utgått)<br />- 1902 – Tromsø<br />- 1903 – Harstad – Hárstták<br />- 1911 – Kvæfjord<br />- 1913 – Skånland<br />- 1915 – Bjarkøy (utgått)<br />- 1917 – Ibestad<br />- 1919 – Gratangen<br />- 1920 – Loabák – Lavangen<br />- 1922 – Bardu<br />- 1923 – Salangen<br />- 1924 – Målselv<br />- 1925 – Sørreisa<br />- 1926 – Dyrøy<br />- 1927 – Tranøy<br />- 1928 – Torsken<br />- 1929 – Berg<br />- 1931 – Lenvik<br />- 1933 – Balsfjord<br />- 1936 – Karlsøy<br />- 1938 – Lyngen<br />- 1939 – Storfjord – Omasvuotna – Omasvuono<br />- 1940 – Gáivuotna – Kåfjord – Kaivuono<br />- 1941 – Skjervøy<br />- 1942 – Nordreisa – Ráisa – Raisi<br />- 1943 – Kvænangen<br />- 2001 – Hammerfest (utgått)<br />- 2002 – Vardø<br />- 2003 – Vadsø<br />- 2004 – Hammerfest<br />- 2011 – Guovdageaidnu – Kautokeino<br />- 2012 – Alta<br />- 2014 – Loppa<br />- 2015 – Hasvik<br />- 2016 – Sørøysund (utgått)<br />- 2017 – Kvalsund<br />- 2018 – Måsøy<br />- 2019 – Nordkapp<br />- 2020 – Porsanger – Porsáŋgu – Porsanki<br />- 2021 – Kárášjohka – Karasjok<br />- 2022 – Lebesby<br />- 2023 – Gamvik<br />- 2024 – Berlevåg<br />- 2025 – Deatnu – Tana<br />- 2027 – Unjárga – Nesseby<br />- 2028 – Båtsfjord<br />- 2030 – Sør-Varanger<br />- 2100 – Svalbard<br />- 2111 – Spitsbergen (utgått)<br />- 2121 – Bjørnøya (utgått)<br />- 2131 – Hopen (utgått)<br />- 2211 – Jan Mayen<br />- 2311 – Sokkelen sør for 62 grader Nord<br />- 2321 – Sokkelen nord for 62 grader Nord<br />- 5001 – Trondheim<br />- 5004 – Steinkjer<br />- 5005 – Namsos<br />- 5011 – Hemne<br />- 5012 – Snillfjord<br />- 5013 – Hitra<br />- 5014 – Frøya<br />- 5015 – Ørland<br />- 5016 – Agdenes<br />- 5017 – Bjugn<br />- 5018 – Åfjord<br />- 5019 – Roan<br />- 5020 – Osen<br />- 5021 – Oppdal<br />- 5022 – Rennebu<br />- 5023 – Meldal<br />- 5024 – Orkdal<br />- 5025 – Røros<br />- 5026 – Holtålen<br />- 5027 – Midtre Gauldal<br />- 5028 – Melhus<br />- 5029 – Skaun<br />- 5030 – Klæbu<br />- 5031 – Malvik<br />- 5032 – Selbu<br />- 5033 – Tydal<br />- 5034 – Meråker<br />- 5035 – Stjørdal<br />- 5036 – Frosta<br />- 5037 – Levanger<br />- 5038 – Verdal<br />- 5039 – Verran<br />- 5040 – Namdalseid<br />- 5041 – Snåase – Snåsa<br />- 5042 – Lierne<br />- 5043 – Raarvihke – Røyrvik<br />- 5044 – Namsskogan<br />- 5045 – Grong<br />- 5046 – Høylandet<br />- 5047 – Overhalla<br />- 5048 – Frosnes<br />- 5049 – Flatanger<br />- 5050 – Vikna<br />- 5051 – Nærøy<br />- 5052 – Leka<br />- 5053 – Inderøy<br />- 5054 – Indre Fosen<br />- 5061 – Rindal</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>matrikkelnummerAdresse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>entydig identifisering av matrikkelenhet innen kommune, definert i matrikkelforskrift § 7e<br /><br />Merknad (teknisk): Hentes fra adresse (link til matrikkelenhet fra adresse i matrikkelen)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Matrikkelnummer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>matrikkelnummerAdresse.bruksnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Hver gård er delt opp i et eller flere bruk. Neste ledige bruksnummer innen et gårdsnummer tildeles automatisk. Forkortelsen er bnr</td>
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
      <td><strong>matrikkelnummerAdresse.festenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Fortløpende nummerering av fester under gårdsnummer/bruksnummer. Forkortelsen er fnr</td>
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
      <td><strong>matrikkelnummerAdresse.gardsnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>En kommune er delt inn i flere gårder, og alle matrikkelenheter ligger på en gårdsenhet. Gårdsnummer er nummeret på en gårdsenhet i matrikkelen og er unikt innenfor hver kommune. Forkortelsen er gnr</td>
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
      <td><strong>matrikkelnummerAdresse.kommunenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummerering av kommuner i henhold til Statistisk sentralbyrå sin offisielle liste<br /><br />Merknad: Det presiseres at kommune alltid skal ha 4 siffer, dvs. eventuelt med ledende null. Kommune benyttes for kopling mot en rekke andre registre som også benytter 4 siffer.</td>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/SOSI/kodeliste/AdmEnheter/2019/Kommunenummer">http://skjema.geonorge.no/SOSI/kodeliste/AdmEnheter/2019/Kommunenummer</a><br />- 0101 – Halden<br />- 0102 – Sarpsborg (utgått)<br />- 0103 – Fredrikstad (utgått)<br />- 0104 – Moss<br />- 0105 – Sarpsborg<br />- 0106 – Fredrikstad<br />- 0111 – Hvaler<br />- 0113 – Borge (utgått)<br />- 0114 – Varteig (utgått)<br />- 0115 – Skjeberg (utgått)<br />- 0118 – Aremark<br />- 0119 – Marker<br />- 0121 – Rømskog<br />- 0122 – Trøgstad<br />- 0123 – Spydeberg<br />- 0124 – Askim<br />- 0125 – Eidsberg<br />- 0127 – Skiptvet<br />- 0128 – Rakkestad<br />- 0130 – Tune (utgått)<br />- 0131 – Rolvsøy (utgått)<br />- 0133 – Kråkerøy (utgått)<br />- 0134 – Onsøy (utgått)<br />- 0135 – Råde<br />- 0136 – Rygge<br />- 0137 – Våler i Østfold<br />- 0138 – Hobøl<br />- 0211 – Vestby<br />- 0213 – Ski<br />- 0214 – Ås<br />- 0215 – Frogn<br />- 0216 – Nesodden<br />- 0217 – Oppegård<br />- 0219 – Bærum<br />- 0220 – Asker<br />- 0221 – Aurskog-Høland<br />- 0226 – Sørum<br />- 0227 – Fet<br />- 0228 – Rælingen<br />- 0229 – Enebakk<br />- 0230 – Lørenskog<br />- 0231 – Skedsmo<br />- 0233 – Nittedal<br />- 0234 – Gjerdrum<br />- 0235 – Ullensaker<br />- 0236 – Nes i Akershus<br />- 0237 – Eidsvoll<br />- 0238 – Nannestad<br />- 0239 – Hurdal<br />- 0301 – Oslo<br />- 0401 – Hamar (utgått)<br />- 0402 – Kongsvinger<br />- 0403 – Hamar<br />- 0412 – Ringsaker<br />- 0414 – Vang (utgått)<br />- 0415 – Løten<br />- 0417 – Stange<br />- 0418 – Nord-Odal<br />- 0419 – Sør-Odal<br />- 0420 – Eidskog<br />- 0423 – Grue<br />- 0425 – Åsnes<br />- 0426 – Våler i Hedmark<br />- 0427 – Elverum<br />- 0428 – Trysil<br />- 0429 – Åmot<br />- 0430 – Stor-Elvdal<br />- 0432 – Rendalen<br />- 0434 – Engerdal<br />- 0436 – Tolga<br />- 0437 – Tynset<br />- 0438 – Alvdal<br />- 0439 – Folldal<br />- 0441 – Os i Hedmark<br />- 0501 – Lillehammer<br />- 0502 – Gjøvik<br />- 0511 – Dovre<br />- 0512 – Lesja<br />- 0513 – Skjåk<br />- 0514 – Lom<br />- 0515 – Vågå<br />- 0516 – Nord-Fron<br />- 0517 – Sel<br />- 0519 – Sør-Fron<br />- 0520 – Ringebu<br />- 0521 – Øyer<br />- 0522 – Gausdal<br />- 0528 – Østre Toten<br />- 0529 – Vestre Toten<br />- 0532 – Jevnaker<br />- 0533 – Lunner<br />- 0534 – Gran<br />- 0536 – Søndre Land<br />- 0538 – Nordre Land<br />- 0540 – Sør-Aurdal<br />- 0541 – Etnedal<br />- 0542 – Nord-Aurdal<br />- 0543 – Vestre Slidre<br />- 0544 – Øystre Slidre<br />- 0545 – Vang<br />- 0602 – Drammen<br />- 0604 – Kongsberg<br />- 0605 – Ringerike<br />- 0612 – Hole<br />- 0615 – Flå<br />- 0616 – Nes i Buskerud<br />- 0617 – Gol<br />- 0618 – Hemsedal<br />- 0619 – Ål<br />- 0620 – Hol<br />- 0621 – Sigdal<br />- 0622 – Krødsherad<br />- 0623 – Modum<br />- 0624 – Øvre Eiker<br />- 0625 – Nedre Eiker<br />- 0626 – Lier<br />- 0627 – Røyken<br />- 0628 – Hurum<br />- 0631 – Flesberg<br />- 0632 – Rollag<br />- 0633 – Nore og Uvdal<br />- 0701 – Horten<br />- 0702 – Holmestrand (utgått)<br />- 0703 – Horten (utgått)<br />- 0704 – Tønsberg<br />- 0705 – Tønsberg (utgått)<br />- 0706 – Sandefjord (utgått)<br />- 0707 – Larvik (utgått)<br />- 0708 – Stavern (utgått)<br />- 0709 – Larvik (utgått)<br />- 0710 – Sandefjord<br />- 0711 – Svelvik<br />- 0712 – Larvik<br />- 0713 – Sande i Vestfold<br />- 0714 – Hof (utgått)<br />- 0715 – Holmestrand<br />- 0716 – Re<br />- 0717 – Borre (utgått)<br />- 0718 – Ramnes (utgått)<br />- 0719 – Andebu (utgått)<br />- 0720 – Stokke (utgått)<br />- 0721 – Sem (utgått)<br />- 0722 – Nøtterøy (utgått)<br />- 0723 – Tjøme (utgått)<br />- 0725 – Tjølling (utgått)<br />- 0726 – Brunlanes (utgått)<br />- 0727 – Hedrum (utgått)<br />- 0728 – Lardal (utgått)<br />- 0729 – Færder<br />- 0805 – Porsgrunn<br />- 0806 – Skien<br />- 0807 – Notodden<br />- 0811 – Siljan<br />- 0814 – Bamble<br />- 0815 – Kragerø<br />- 0817 – Drangedal<br />- 0819 – Nome<br />- 0821 – Bø i Telemark<br />- 0822 – Sauherad<br />- 0826 – Tinn<br />- 0827 – Hjartdal<br />- 0828 – Seljord<br />- 0829 – Kviteseid<br />- 0830 – Nissedal<br />- 0831 – Fyresdal<br />- 0833 – Tokke<br />- 0834 – Vinje<br />- 0901 – Risør<br />- 0903 – Arendal (utgått)<br />- 0904 – Grimstad<br />- 0906 – Arendal<br />- 0911 – Gjerstad<br />- 0912 – Vegårshei<br />- 0914 – Tvedestrand<br />- 0918 – Moland (utgått)<br />- 0919 – Froland<br />- 0920 – Øyestad (utgått)<br />- 0921 – Tromøy (utgått)<br />- 0922 – Hisøy (utgått)<br />- 0926 – Lillesand<br />- 0928 – Birkenes<br />- 0929 – Åmli<br />- 0935 – Iveland<br />- 0937 – Evje og Hornnes<br />- 0938 – Bygland<br />- 0940 – Valle<br />- 0941 – Bykle<br />- 1001 – Kristiansand<br />- 1002 – Mandal<br />- 1003 – Farsund<br />- 1004 – Flekkefjord<br />- 1014 – Vennesla<br />- 1017 – Songdalen<br />- 1018 – Søgne<br />- 1021 – Marnardal<br />- 1026 – Åseral<br />- 1027 – Audnedal<br />- 1029 – Lindesnes<br />- 1032 – Lyngdal<br />- 1034 – Hægebostad<br />- 1037 – Kvinesdal<br />- 1046 – Sirdal<br />- 1101 – Eigersund<br />- 1102 – Sandnes<br />- 1103 – Stavanger<br />- 1106 – Haugesund<br />- 1111 – Sokndal<br />- 1112 – Lund<br />- 1114 – Bjerkreim<br />- 1119 – Hå<br />- 1120 – Klepp<br />- 1121 – Time<br />- 1122 – Gjesdal<br />- 1124 – Sola<br />- 1127 – Randaberg<br />- 1129 – Forsand<br />- 1130 – Strand<br />- 1133 – Hjelmeland<br />- 1134 – Suldal<br />- 1135 – Sauda<br />- 1141 – Finnøy<br />- 1142 – Rennesøy<br />- 1144 – Kvitsøy<br />- 1145 – Bokn<br />- 1146 – Tysvær<br />- 1149 – Karmøy<br />- 1151 – Utsira<br />- 1154 – Vindafjord ((utgått)<br />- 1159 – Ølen (utgått)<br />- 1160 – Vindafjord<br />- 1201 – Bergen<br />- 1211 – Etne<br />- 1214 – Ølen (utgått)<br />- 1216 – Sveio<br />- 1219 – Bømlo<br />- 1221 – Stord<br />- 1222 – Fitjar<br />- 1223 – Tysnes<br />- 1224 – Kvinnherad<br />- 1227 – Jondal<br />- 1228 – Odda<br />- 1231 – Ullensvang<br />- 1232 – Eidfjord<br />- 1233 – Ulvik<br />- 1234 – Granvin<br />- 1235 – Voss<br />- 1238 – Kvam<br />- 1241 – Fusa<br />- 1242 – Samnanger<br />- 1243 – Os i Hordaland<br />- 1244 – Austevoll<br />- 1245 – Sund<br />- 1246 – Fjell<br />- 1247 – Askøy<br />- 1251 – Vaksdal<br />- 1252 – Modalen<br />- 1253 – Osterøy<br />- 1256 – Meland<br />- 1259 – Øygarden<br />- 1260 – Radøy<br />- 1263 – Lindås<br />- 1264 – Austrheim<br />- 1265 – Fedje<br />- 1266 – Masfjorden<br />- 1401 – Flora<br />- 1411 – Gulen<br />- 1412 – Solund<br />- 1413 – Hyllestad<br />- 1416 – Høyanger<br />- 1417 – Vik<br />- 1418 – Balestrand<br />- 1419 – Leikanger<br />- 1420 – Sogndal<br />- 1421 – Aurland<br />- 1422 – Lærdal<br />- 1424 – Årdal<br />- 1426 – Luster<br />- 1428 – Askvoll<br />- 1429 – Fjaler<br />- 1430 – Gaular<br />- 1431 – Jølster<br />- 1432 – Førde<br />- 1433 – Naustdal<br />- 1438 – Bremanger<br />- 1439 – Vågsøy<br />- 1441 – Selje<br />- 1443 – Eid<br />- 1444 – Hornindal<br />- 1445 – Gloppen<br />- 1449 – Stryn<br />- 1502 – Molde<br />- 1504 – Ålesund<br />- 1505 – Kristiansund<br />- 1511 – Vanylven<br />- 1514 – Sande i Møre og Romsdal<br />- 1515 – Herøy i Møre og Romsdal<br />- 1516 – Ulstein<br />- 1517 – Hareid<br />- 1519 – Volda<br />- 1520 – Ørsta<br />- 1523 – Ørskog<br />- 1524 – Norddal<br />- 1525 – Stranda<br />- 1526 – Stordal<br />- 1528 – Sykkylven<br />- 1529 – Skodje<br />- 1531 – Sula<br />- 1532 – Giske<br />- 1534 – Haram<br />- 1535 – Vestnes<br />- 1539 – Rauma<br />- 1543 – Nesset<br />- 1545 – Midsund<br />- 1546 – Sandøy<br />- 1547 – Aukra<br />- 1548 – Fræna<br />- 1551 – Eide<br />- 1554 – Averøy<br />- 1557 – Gjemnes<br />- 1560 – Tingvoll<br />- 1563 – Sunndal<br />- 1566 – Surnadal<br />- 1567 – Rindal (utgått)<br />- 1569 – Aure (utgått)<br />- 1571 – Halsa<br />- 1572 – Tustna (utgått)<br />- 1573 – Smøla<br />- 1576 – Aure<br />- 1601 – Trondheim (utgått)<br />- 1612 – Hemne (utgått)<br />- 1613 – Snillfjord (utgått)<br />- 1617 – Hitra (utgått)<br />- 1620 – Frøya (utgått)<br />- 1621 – Ørland (utgått)<br />- 1622 – Agdenes (utgått)<br />- 1624 – Rissa (utgått)<br />- 1627 – Bjugn (utgått)<br />- 1630 – Åfjord (utgått)<br />- 1632 – Roan (utgått)<br />- 1633 – Osen (utgått)<br />- 1634 – Oppdal (utgått)<br />- 1635 – Rennebu (utgått)<br />- 1636 – Meldal (utgått)<br />- 1638 – Orkdal (utgått)<br />- 1640 – Røros (utgått)<br />- 1644 – Holtålen (utgått)<br />- 1648 – Midtre Gauldal (utgått)<br />- 1653 – Melhus (utgått)<br />- 1657 – Skaun (utgått)<br />- 1662 – Klæbu (utgått)<br />- 1663 – Malvik (utgått)<br />- 1664 – Selbu (utgått)<br />- 1665 – Tydal (utgått)<br />- 1702 – Steinkjer (utgått)<br />- 1703 – Namsos (utgått)<br />- 1711 – Meråker (utgått)<br />- 1714 – Stjørdal (utgått)<br />- 1717 – Frosta (utgått)<br />- 1718 – Leksvik (utgått)<br />- 1719 – Levanger (utgått)<br />- 1721 – Verdal (utgått)<br />- 1723 – Mosvik (utgått)<br />- 1724 – Verran (utgått)<br />- 1725 – Namdalseid (utgått)<br />- 1729 – Inderøy (utgått)<br />- 1736 – Snåase – Snåsa (utgått)<br />- 1738 – Lierne (utgått)<br />- 1739 – Raarvihke – Røyrvik (utgått)<br />- 1740 – Namsskogan (utgått)<br />- 1742 – Grong (utgått)<br />- 1743 – Høylandet (utgått)<br />- 1744 – Overhalla (utgått)<br />- 1748 – Fosnes (utgått)<br />- 1749 – Flatanger (utgått)<br />- 1750 – Vikna (utgått)<br />- 1751 – Nærøy (utgått)<br />- 1755 – Leka (utgått)<br />- 1756 – Inderøy (utgått)<br />- 1804 – Bodø<br />- 1805 – Narvik<br />- 1811 – Bindal<br />- 1812 – Sømna<br />- 1813 – Brønnøy<br />- 1815 – Vega<br />- 1816 – Vevelstad<br />- 1818 – Herøy i Nordland<br />- 1820 – Alstahaug<br />- 1822 – Leirfjord<br />- 1824 – Vefsn<br />- 1825 – Grane<br />- 1826 – Hattfjelldal<br />- 1827 – Dønna<br />- 1828 – Nesna<br />- 1832 – Hemnes<br />- 1833 – Rana<br />- 1834 – Lurøy<br />- 1835 – Træna<br />- 1836 – Rødøy<br />- 1837 – Meløy<br />- 1838 – Gildeskål<br />- 1839 – Beiarn<br />- 1840 – Saltdal<br />- 1841 – Fauske – Fuossko<br />- 1842 – Skjerstad (utgått)<br />- 1845 – Sørfold<br />- 1848 – Steigen<br />- 1849 – Hamarøy – Hábmer<br />- 1850 – Divtasvuodna – Tysfjord<br />- 1851 – Lødingen<br />- 1852 – Tjeldsund<br />- 1853 – Evenes<br />- 1854 – Ballangen<br />- 1856 – Røst<br />- 1857 – Værøy<br />- 1859 – Flakstad<br />- 1860 – Vestvågøy<br />- 1865 – Vågan<br />- 1866 – Hadsel<br />- 1867 – Bø i Nordland<br />- 1868 – Øksnes<br />- 1870 – Sortland – Suortá<br />- 1871 – Andøy<br />- 1874 – Moskenes<br />- 1901 – Harstad (utgått)<br />- 1902 – Tromsø<br />- 1903 – Harstad – Hárstták<br />- 1911 – Kvæfjord<br />- 1913 – Skånland<br />- 1915 – Bjarkøy (utgått)<br />- 1917 – Ibestad<br />- 1919 – Gratangen<br />- 1920 – Loabák – Lavangen<br />- 1922 – Bardu<br />- 1923 – Salangen<br />- 1924 – Målselv<br />- 1925 – Sørreisa<br />- 1926 – Dyrøy<br />- 1927 – Tranøy<br />- 1928 – Torsken<br />- 1929 – Berg<br />- 1931 – Lenvik<br />- 1933 – Balsfjord<br />- 1936 – Karlsøy<br />- 1938 – Lyngen<br />- 1939 – Storfjord – Omasvuotna – Omasvuono<br />- 1940 – Gáivuotna – Kåfjord – Kaivuono<br />- 1941 – Skjervøy<br />- 1942 – Nordreisa – Ráisa – Raisi<br />- 1943 – Kvænangen<br />- 2001 – Hammerfest (utgått)<br />- 2002 – Vardø<br />- 2003 – Vadsø<br />- 2004 – Hammerfest<br />- 2011 – Guovdageaidnu – Kautokeino<br />- 2012 – Alta<br />- 2014 – Loppa<br />- 2015 – Hasvik<br />- 2016 – Sørøysund (utgått)<br />- 2017 – Kvalsund<br />- 2018 – Måsøy<br />- 2019 – Nordkapp<br />- 2020 – Porsanger – Porsáŋgu – Porsanki<br />- 2021 – Kárášjohka – Karasjok<br />- 2022 – Lebesby<br />- 2023 – Gamvik<br />- 2024 – Berlevåg<br />- 2025 – Deatnu – Tana<br />- 2027 – Unjárga – Nesseby<br />- 2028 – Båtsfjord<br />- 2030 – Sør-Varanger<br />- 2100 – Svalbard<br />- 2111 – Spitsbergen (utgått)<br />- 2121 – Bjørnøya (utgått)<br />- 2131 – Hopen (utgått)<br />- 2211 – Jan Mayen<br />- 2311 – Sokkelen sør for 62 grader Nord<br />- 2321 – Sokkelen nord for 62 grader Nord<br />- 5001 – Trondheim<br />- 5004 – Steinkjer<br />- 5005 – Namsos<br />- 5011 – Hemne<br />- 5012 – Snillfjord<br />- 5013 – Hitra<br />- 5014 – Frøya<br />- 5015 – Ørland<br />- 5016 – Agdenes<br />- 5017 – Bjugn<br />- 5018 – Åfjord<br />- 5019 – Roan<br />- 5020 – Osen<br />- 5021 – Oppdal<br />- 5022 – Rennebu<br />- 5023 – Meldal<br />- 5024 – Orkdal<br />- 5025 – Røros<br />- 5026 – Holtålen<br />- 5027 – Midtre Gauldal<br />- 5028 – Melhus<br />- 5029 – Skaun<br />- 5030 – Klæbu<br />- 5031 – Malvik<br />- 5032 – Selbu<br />- 5033 – Tydal<br />- 5034 – Meråker<br />- 5035 – Stjørdal<br />- 5036 – Frosta<br />- 5037 – Levanger<br />- 5038 – Verdal<br />- 5039 – Verran<br />- 5040 – Namdalseid<br />- 5041 – Snåase – Snåsa<br />- 5042 – Lierne<br />- 5043 – Raarvihke – Røyrvik<br />- 5044 – Namsskogan<br />- 5045 – Grong<br />- 5046 – Høylandet<br />- 5047 – Overhalla<br />- 5048 – Frosnes<br />- 5049 – Flatanger<br />- 5050 – Vikna<br />- 5051 – Nærøy<br />- 5052 – Leka<br />- 5053 – Inderøy<br />- 5054 – Indre Fosen<br />- 5061 – Rindal</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>matrikkelnummerAdresse.seksjonsnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Fortløpende nummerering av seksjoner under gårdsnummer/bruksnummer og eventuelt festenummer.</td>
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
      <td><strong>postnummerområde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>adressens knytning til postnummerområde, geografisk område med felles postnummer, og en underinndeling av postområde</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>PostnummerområdeId</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>postnummerområde.postnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>firesifret kode som identifiserer et postnummerområde<br /><br />Merknad: Det første sifferet angir postsone, de to første sifrene angir postregion, de tre første sifrene angir postområde og alle fire sifrene angir postnummerområde/poststed.</td>
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
      <td><strong>postnummerområde.poststed</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på poststed i henhold til Postens egne lister</td>
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
      <td><strong>representasjonspunkt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Representasjonspunkt for adressen. Angir normalt atkomsten til en bygning, bolig eller andre objekter og steder.<br /><br />Merknad:<br />Dersom en adresse kun gjelder en bygning med en adresse, plasseres punktet innenfor bygningens omriss like ved inngang /atkomst.<br />Det samme gjelder dersom det er knyttet flere adresser til flere innganger/atkomster til en bygning. Adressepunktene plasseres like ved de respektive innganger/atkomster innenfor bygningens omriss. For bygg med altangang eller svalgang med atkomst til den enkelte bolig via utvendig atkomsttrapp, plasseres adressepunktet i trapp nærmest terrengnivå<br /><br />For ubebygde eiendommer verifiseres det at punktet er innenfor teigen og ved atkomst.</td>
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
      <td><strong>sokn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>adressens kobling til sokn, den minste geistlige enheten og bestyres av en sokneprest<br /><br />Merknad:<br />Folket som er medlem i Den norske kirke og bosatt innenfor et sokn betegnes som menighet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>SokneId</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>sokn.organisasjonsnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>entydig identifisering av foretak i Brønnøysundregisteret</td>
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
      <td><strong>sokn.soknenavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på soknet</td>
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
      <td><strong>sokn.soknenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et sokn i form av 8-sifre<br /><br />Merknad:<br />De to første siffer står for bispedømme, to neste for prosti, to neste for prestegjeld (utgått, men inngår i nummerering) og to siste for sokn.</td>
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
      <td><strong>tettsted</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>adressens tilknytning til tettsted, område hvor det bor minst 200 personer, og avstanden mellom husene normalt ikke overstiger 50 meter (SSB)<br /><br />Merknad:<br />Hussamlinger som naturlig  hører med til tettstedet, tas med inntil en avstand på 400 meter fra tettstedskjernen.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TettstedId</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tettsted.tettstednavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på tettsted bestemt av SSB</td>
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
      <td><strong>tettsted.tettstednummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>består av en 4-sifret kode<br /><br />Merknad: Det skal benyttes ledende nuller.</td>
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
      <td><strong>valgkrets</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>adressens knytning til valgkrets, valgkretsene har som formål å være en hensiktsmessig inndeling av kommuner ved valg, bl.a. for at velgerne ikke skal få for stor avstand til valglokalet<br /><br />Merknad: Inndelingen skal ivareta administrative formål, men har også i en viss grad blitt nyttet til å samle inn statistikk for planleggingsformål.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>ValgkretsId</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>valgkrets.valgkretsnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn til valgkrets</td>
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
      <td><strong>valgkrets.valgkretsnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>løpenummer innenfor valgkretsens kommune</td>
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
SOSI_Objekt-Adresse

#### Vegadresse

Offisiell adresse i form av et adressenavn og et adressenummer (matrikkelforskriften § 2i).<br /><br />Merknad:<br />Vegadresser er enkeltadresser innen en "veg" (adresseområde) i en kommune. Vegadresse identifiseres innen kommunen ved adressekode, husnummer (nummer) og eventuelt bokstav<br /><br />Merknad2: Eventuelle bruksenhetsnummer som del av offisiell adresse kan ligge som egenskaper til Vegadressen

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>adressekode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Et nummer som entydig identifiserer adresserbare gater, veger, stier, plasser og områder som er ført i matrikkelen. For hvert adressenavn skal det således foreligge en adressekode, jf. matrikkelforskriften § 51.2.<br />Merknad: Adressekode er unik innenfor kommunen<br /><br />Merknad (teknisk): Avledet fra Veg-objektet</td>
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
      <td><strong>adressenavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navn på gate, veg, sti, plass eller område som er ført i matrikkelen. (matrikkelforskriften § 2e)<br /><br />Merknad (teknisk): Avledet fra Veg-objektet</td>
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
      <td><strong>bokstav</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>del av adressenummer (jfr Matrikkelforskrift § 2f).<br /><br />Ved behov kan det i tillegg til tallet brukes en etterfølgende bokstav. Bokstav skal bare brukes for å unngå omnummerering i tidligere tildelte adresser. Bokstav skal gis i alfabetisk rekkefølge. (matrikkelforskrift § 52 tredje ledd).<br /><br />Merknad: Høyst en bokstav</td>
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
      <td><strong>nummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Del av adressenummer som er definert slik i matrikkelforskrift:<br /><br />et nummer og en eventuell bokstav (husnummer) som entydig identifiserer eiendommer, anlegg, bygninger eller innganger til bygninger innenfor en adresserbar gate, veg, sti, plass eller område (Forskrift § 2f).</td>
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
Adresse

#### Matrikkeladresse

offisiell adresse i form av et gårds- og bruksnummer og eventuelt et festenummer, eventuelt også et undernummer (Matrikkelforskriften § 2j)<br /><br />Merknad:<br />Matrikkeladresse er adresseidentifikasjon i et område der det ikke er tildelt vegadresse.<br /><br />Merknad2: Eventuelle bruksenhetsnummer som del av offisiell adresse kan ligge som egenskaper til matrikkeladressen<br /><br />Merknad3: Seksjonsnummer er ikke en del av den logiske identen for matrikkeladresse, - se egenskapen adressetekst.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>undernummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Fortløpende nummerering av matrikkeladresser med samme gårds-, bruks- og festenummer.</td>
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
Adresse

### Kodelister

#### «Enumeration» AdressetilleggsnavnKildeKode

**Definisjon:** Kodeliste over opphav til adressetilleggsnavn, som også er årsaken til at de er registrert i matrikkelen.

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
      <td>anmodetAvHjemmelshaver</td>
      <td>&lt;font color="#333333"&gt;Når adressen gjelder en særlig kjent institusjon eller bygning og allmenne hensyn taler for det, kan kommunen på anmodning fra registrert eier fastsette at den offisielle adressen også skal omfatte et navn på institusjonen eller bygningen (&lt;/font&gt;matrikkelforskriftens § 54 2. ledd)</td>
      <td></td>
    </tr>
    <tr>
      <td>ikkeOppgitt</td>
      <td>"Ikke oppgitt" brukes på adresser uten adressetilleggsnavn.</td>
      <td></td>
    </tr>
    <tr>
      <td>krevdAvEier</td>
      <td>&lt;font color="#333333"&gt;Når adressen gjelder et gårdsbruk, kan den som har grunnbokshjemmel til eiendommen som eier, kreve at den offisielle adressen også skal omfatte gårdens bruksnavn, dersom navnet faller språklig og geografisk sammen med et nedarvet stedsnavn, jf. lov 18. mai 1990 nr. 11 om stadnamn (&lt;/font&gt;matrikkelforskriftens § 54 1. ledd)</td>
      <td></td>
    </tr>
    <tr>
      <td>matrikkeladressenavn</td>
      <td>&lt;font color="#333333"&gt;Adresser i område med matrikkeladresser som ikke har tildelt et adressetilleggsnavn etter reglene i § 54, kan tilordnes et matrikkeladressenavn etter &lt;/font&gt;matrikkelforskriftens § 55 3. ledd. Hvis det tildeles adressetilleggsnavn etter § 54 strykes matrikkeladressenavnet</td>
      <td></td>
    </tr>
    <tr>
      <td>tildeltAvKommunen</td>
      <td>&lt;font color="#333333"&gt;Kommunen kan tildele adresser innenfor mindre grender, bolig- eller hyttefelt eller andre avgrensede områder et felles adressetilleggsnavn (&lt;/font&gt;Matrikkelforskriftens § 54 3. ledd, men tildeling etter 1. eller 2. ledd går foran 3. ledd)</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Kommunenummer

**Definisjon:** nummerering av kommuner i henhold til Statistisk sentralbyrå sin offisielle liste samt et utvalg av utgåtte numre

Merknad: Det presiseres at kommune alltid skal ha 4 sifre, dvs. eventuelt med ledende null. Kommune benyttes for kopling mot en rekke andre registre som også benytter 4 sifre.

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
      <td><a href="http://skjema.geonorge.no/SOSI/kodeliste/AdmEnheter/2019/Kommunenummer">http://skjema.geonorge.no/SOSI/kodeliste/AdmEnheter/2019/Kommunenummer</a></td>
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
      <td></td>
      <td>Halden</td>
      <td>0101</td>
    </tr>
    <tr>
      <td></td>
      <td>Sarpsborg (utgått)</td>
      <td>0102</td>
    </tr>
    <tr>
      <td></td>
      <td>Fredrikstad (utgått)</td>
      <td>0103</td>
    </tr>
    <tr>
      <td></td>
      <td>Moss</td>
      <td>0104</td>
    </tr>
    <tr>
      <td></td>
      <td>Sarpsborg</td>
      <td>0105</td>
    </tr>
    <tr>
      <td></td>
      <td>Fredrikstad</td>
      <td>0106</td>
    </tr>
    <tr>
      <td></td>
      <td>Hvaler</td>
      <td>0111</td>
    </tr>
    <tr>
      <td></td>
      <td>Borge (utgått)</td>
      <td>0113</td>
    </tr>
    <tr>
      <td></td>
      <td>Varteig (utgått)</td>
      <td>0114</td>
    </tr>
    <tr>
      <td></td>
      <td>Skjeberg (utgått)</td>
      <td>0115</td>
    </tr>
    <tr>
      <td></td>
      <td>Aremark</td>
      <td>0118</td>
    </tr>
    <tr>
      <td></td>
      <td>Marker</td>
      <td>0119</td>
    </tr>
    <tr>
      <td></td>
      <td>Rømskog</td>
      <td>0121</td>
    </tr>
    <tr>
      <td></td>
      <td>Trøgstad</td>
      <td>0122</td>
    </tr>
    <tr>
      <td></td>
      <td>Spydeberg</td>
      <td>0123</td>
    </tr>
    <tr>
      <td></td>
      <td>Askim</td>
      <td>0124</td>
    </tr>
    <tr>
      <td></td>
      <td>Eidsberg</td>
      <td>0125</td>
    </tr>
    <tr>
      <td></td>
      <td>Skiptvet</td>
      <td>0127</td>
    </tr>
    <tr>
      <td></td>
      <td>Rakkestad</td>
      <td>0128</td>
    </tr>
    <tr>
      <td></td>
      <td>Tune (utgått)</td>
      <td>0130</td>
    </tr>
    <tr>
      <td></td>
      <td>Rolvsøy (utgått)</td>
      <td>0131</td>
    </tr>
    <tr>
      <td></td>
      <td>Kråkerøy (utgått)</td>
      <td>0133</td>
    </tr>
    <tr>
      <td></td>
      <td>Onsøy (utgått)</td>
      <td>0134</td>
    </tr>
    <tr>
      <td></td>
      <td>Råde</td>
      <td>0135</td>
    </tr>
    <tr>
      <td></td>
      <td>Rygge</td>
      <td>0136</td>
    </tr>
    <tr>
      <td></td>
      <td>Våler i Østfold</td>
      <td>0137</td>
    </tr>
    <tr>
      <td></td>
      <td>Hobøl</td>
      <td>0138</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestby</td>
      <td>0211</td>
    </tr>
    <tr>
      <td></td>
      <td>Ski</td>
      <td>0213</td>
    </tr>
    <tr>
      <td></td>
      <td>Ås</td>
      <td>0214</td>
    </tr>
    <tr>
      <td></td>
      <td>Frogn</td>
      <td>0215</td>
    </tr>
    <tr>
      <td></td>
      <td>Nesodden</td>
      <td>0216</td>
    </tr>
    <tr>
      <td></td>
      <td>Oppegård</td>
      <td>0217</td>
    </tr>
    <tr>
      <td></td>
      <td>Bærum</td>
      <td>0219</td>
    </tr>
    <tr>
      <td></td>
      <td>Asker</td>
      <td>0220</td>
    </tr>
    <tr>
      <td></td>
      <td>Aurskog-Høland</td>
      <td>0221</td>
    </tr>
    <tr>
      <td></td>
      <td>Sørum</td>
      <td>0226</td>
    </tr>
    <tr>
      <td></td>
      <td>Fet</td>
      <td>0227</td>
    </tr>
    <tr>
      <td></td>
      <td>Rælingen</td>
      <td>0228</td>
    </tr>
    <tr>
      <td></td>
      <td>Enebakk</td>
      <td>0229</td>
    </tr>
    <tr>
      <td></td>
      <td>Lørenskog</td>
      <td>0230</td>
    </tr>
    <tr>
      <td></td>
      <td>Skedsmo</td>
      <td>0231</td>
    </tr>
    <tr>
      <td></td>
      <td>Nittedal</td>
      <td>0233</td>
    </tr>
    <tr>
      <td></td>
      <td>Gjerdrum</td>
      <td>0234</td>
    </tr>
    <tr>
      <td></td>
      <td>Ullensaker</td>
      <td>0235</td>
    </tr>
    <tr>
      <td></td>
      <td>Nes i Akershus</td>
      <td>0236</td>
    </tr>
    <tr>
      <td></td>
      <td>Eidsvoll</td>
      <td>0237</td>
    </tr>
    <tr>
      <td></td>
      <td>Nannestad</td>
      <td>0238</td>
    </tr>
    <tr>
      <td></td>
      <td>Hurdal</td>
      <td>0239</td>
    </tr>
    <tr>
      <td></td>
      <td>Oslo</td>
      <td>0301</td>
    </tr>
    <tr>
      <td></td>
      <td>Hamar (utgått)</td>
      <td>0401</td>
    </tr>
    <tr>
      <td></td>
      <td>Kongsvinger</td>
      <td>0402</td>
    </tr>
    <tr>
      <td></td>
      <td>Hamar</td>
      <td>0403</td>
    </tr>
    <tr>
      <td></td>
      <td>Ringsaker</td>
      <td>0412</td>
    </tr>
    <tr>
      <td></td>
      <td>Vang (utgått)</td>
      <td>0414</td>
    </tr>
    <tr>
      <td></td>
      <td>Løten</td>
      <td>0415</td>
    </tr>
    <tr>
      <td></td>
      <td>Stange</td>
      <td>0417</td>
    </tr>
    <tr>
      <td></td>
      <td>Nord-Odal</td>
      <td>0418</td>
    </tr>
    <tr>
      <td></td>
      <td>Sør-Odal</td>
      <td>0419</td>
    </tr>
    <tr>
      <td></td>
      <td>Eidskog</td>
      <td>0420</td>
    </tr>
    <tr>
      <td></td>
      <td>Grue</td>
      <td>0423</td>
    </tr>
    <tr>
      <td></td>
      <td>Åsnes</td>
      <td>0425</td>
    </tr>
    <tr>
      <td></td>
      <td>Våler i Hedmark</td>
      <td>0426</td>
    </tr>
    <tr>
      <td></td>
      <td>Elverum</td>
      <td>0427</td>
    </tr>
    <tr>
      <td></td>
      <td>Trysil</td>
      <td>0428</td>
    </tr>
    <tr>
      <td></td>
      <td>Åmot</td>
      <td>0429</td>
    </tr>
    <tr>
      <td></td>
      <td>Stor-Elvdal</td>
      <td>0430</td>
    </tr>
    <tr>
      <td></td>
      <td>Rendalen</td>
      <td>0432</td>
    </tr>
    <tr>
      <td></td>
      <td>Engerdal</td>
      <td>0434</td>
    </tr>
    <tr>
      <td></td>
      <td>Tolga</td>
      <td>0436</td>
    </tr>
    <tr>
      <td></td>
      <td>Tynset</td>
      <td>0437</td>
    </tr>
    <tr>
      <td></td>
      <td>Alvdal</td>
      <td>0438</td>
    </tr>
    <tr>
      <td></td>
      <td>Folldal</td>
      <td>0439</td>
    </tr>
    <tr>
      <td></td>
      <td>Os i Hedmark</td>
      <td>0441</td>
    </tr>
    <tr>
      <td></td>
      <td>Lillehammer</td>
      <td>0501</td>
    </tr>
    <tr>
      <td></td>
      <td>Gjøvik</td>
      <td>0502</td>
    </tr>
    <tr>
      <td></td>
      <td>Dovre</td>
      <td>0511</td>
    </tr>
    <tr>
      <td></td>
      <td>Lesja</td>
      <td>0512</td>
    </tr>
    <tr>
      <td></td>
      <td>Skjåk</td>
      <td>0513</td>
    </tr>
    <tr>
      <td></td>
      <td>Lom</td>
      <td>0514</td>
    </tr>
    <tr>
      <td></td>
      <td>Vågå</td>
      <td>0515</td>
    </tr>
    <tr>
      <td></td>
      <td>Nord-Fron</td>
      <td>0516</td>
    </tr>
    <tr>
      <td></td>
      <td>Sel</td>
      <td>0517</td>
    </tr>
    <tr>
      <td></td>
      <td>Sør-Fron</td>
      <td>0519</td>
    </tr>
    <tr>
      <td></td>
      <td>Ringebu</td>
      <td>0520</td>
    </tr>
    <tr>
      <td></td>
      <td>Øyer</td>
      <td>0521</td>
    </tr>
    <tr>
      <td></td>
      <td>Gausdal</td>
      <td>0522</td>
    </tr>
    <tr>
      <td></td>
      <td>Østre Toten</td>
      <td>0528</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestre Toten</td>
      <td>0529</td>
    </tr>
    <tr>
      <td></td>
      <td>Jevnaker</td>
      <td>0532</td>
    </tr>
    <tr>
      <td></td>
      <td>Lunner</td>
      <td>0533</td>
    </tr>
    <tr>
      <td></td>
      <td>Gran</td>
      <td>0534</td>
    </tr>
    <tr>
      <td></td>
      <td>Søndre Land</td>
      <td>0536</td>
    </tr>
    <tr>
      <td></td>
      <td>Nordre Land</td>
      <td>0538</td>
    </tr>
    <tr>
      <td></td>
      <td>Sør-Aurdal</td>
      <td>0540</td>
    </tr>
    <tr>
      <td></td>
      <td>Etnedal</td>
      <td>0541</td>
    </tr>
    <tr>
      <td></td>
      <td>Nord-Aurdal</td>
      <td>0542</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestre Slidre</td>
      <td>0543</td>
    </tr>
    <tr>
      <td></td>
      <td>Øystre Slidre</td>
      <td>0544</td>
    </tr>
    <tr>
      <td></td>
      <td>Vang</td>
      <td>0545</td>
    </tr>
    <tr>
      <td></td>
      <td>Drammen</td>
      <td>0602</td>
    </tr>
    <tr>
      <td></td>
      <td>Kongsberg</td>
      <td>0604</td>
    </tr>
    <tr>
      <td></td>
      <td>Ringerike</td>
      <td>0605</td>
    </tr>
    <tr>
      <td></td>
      <td>Hole</td>
      <td>0612</td>
    </tr>
    <tr>
      <td></td>
      <td>Flå</td>
      <td>0615</td>
    </tr>
    <tr>
      <td></td>
      <td>Nes i Buskerud</td>
      <td>0616</td>
    </tr>
    <tr>
      <td></td>
      <td>Gol</td>
      <td>0617</td>
    </tr>
    <tr>
      <td></td>
      <td>Hemsedal</td>
      <td>0618</td>
    </tr>
    <tr>
      <td></td>
      <td>Ål</td>
      <td>0619</td>
    </tr>
    <tr>
      <td></td>
      <td>Hol</td>
      <td>0620</td>
    </tr>
    <tr>
      <td></td>
      <td>Sigdal</td>
      <td>0621</td>
    </tr>
    <tr>
      <td></td>
      <td>Krødsherad</td>
      <td>0622</td>
    </tr>
    <tr>
      <td></td>
      <td>Modum</td>
      <td>0623</td>
    </tr>
    <tr>
      <td></td>
      <td>Øvre Eiker</td>
      <td>0624</td>
    </tr>
    <tr>
      <td></td>
      <td>Nedre Eiker</td>
      <td>0625</td>
    </tr>
    <tr>
      <td></td>
      <td>Lier</td>
      <td>0626</td>
    </tr>
    <tr>
      <td></td>
      <td>Røyken</td>
      <td>0627</td>
    </tr>
    <tr>
      <td></td>
      <td>Hurum</td>
      <td>0628</td>
    </tr>
    <tr>
      <td></td>
      <td>Flesberg</td>
      <td>0631</td>
    </tr>
    <tr>
      <td></td>
      <td>Rollag</td>
      <td>0632</td>
    </tr>
    <tr>
      <td></td>
      <td>Nore og Uvdal</td>
      <td>0633</td>
    </tr>
    <tr>
      <td></td>
      <td>Horten</td>
      <td>0701</td>
    </tr>
    <tr>
      <td></td>
      <td>Holmestrand (utgått)</td>
      <td>0702</td>
    </tr>
    <tr>
      <td></td>
      <td>Horten (utgått)</td>
      <td>0703</td>
    </tr>
    <tr>
      <td></td>
      <td>Tønsberg</td>
      <td>0704</td>
    </tr>
    <tr>
      <td></td>
      <td>Tønsberg (utgått)</td>
      <td>0705</td>
    </tr>
    <tr>
      <td></td>
      <td>Sandefjord (utgått)</td>
      <td>0706</td>
    </tr>
    <tr>
      <td></td>
      <td>Larvik (utgått)</td>
      <td>0707</td>
    </tr>
    <tr>
      <td></td>
      <td>Stavern (utgått)</td>
      <td>0708</td>
    </tr>
    <tr>
      <td></td>
      <td>Larvik (utgått)</td>
      <td>0709</td>
    </tr>
    <tr>
      <td></td>
      <td>Sandefjord</td>
      <td>0710</td>
    </tr>
    <tr>
      <td></td>
      <td>Svelvik</td>
      <td>0711</td>
    </tr>
    <tr>
      <td></td>
      <td>Larvik</td>
      <td>0712</td>
    </tr>
    <tr>
      <td></td>
      <td>Sande i Vestfold</td>
      <td>0713</td>
    </tr>
    <tr>
      <td></td>
      <td>Hof (utgått)</td>
      <td>0714</td>
    </tr>
    <tr>
      <td></td>
      <td>Holmestrand</td>
      <td>0715</td>
    </tr>
    <tr>
      <td></td>
      <td>Re</td>
      <td>0716</td>
    </tr>
    <tr>
      <td></td>
      <td>Borre (utgått)</td>
      <td>0717</td>
    </tr>
    <tr>
      <td></td>
      <td>Ramnes (utgått)</td>
      <td>0718</td>
    </tr>
    <tr>
      <td></td>
      <td>Andebu (utgått)</td>
      <td>0719</td>
    </tr>
    <tr>
      <td></td>
      <td>Stokke (utgått)</td>
      <td>0720</td>
    </tr>
    <tr>
      <td></td>
      <td>Sem (utgått)</td>
      <td>0721</td>
    </tr>
    <tr>
      <td></td>
      <td>Nøtterøy (utgått)</td>
      <td>0722</td>
    </tr>
    <tr>
      <td></td>
      <td>Tjøme (utgått)</td>
      <td>0723</td>
    </tr>
    <tr>
      <td></td>
      <td>Tjølling (utgått)</td>
      <td>0725</td>
    </tr>
    <tr>
      <td></td>
      <td>Brunlanes (utgått)</td>
      <td>0726</td>
    </tr>
    <tr>
      <td></td>
      <td>Hedrum (utgått)</td>
      <td>0727</td>
    </tr>
    <tr>
      <td></td>
      <td>Lardal (utgått)</td>
      <td>0728</td>
    </tr>
    <tr>
      <td></td>
      <td>Færder</td>
      <td>0729</td>
    </tr>
    <tr>
      <td></td>
      <td>Porsgrunn</td>
      <td>0805</td>
    </tr>
    <tr>
      <td></td>
      <td>Skien</td>
      <td>0806</td>
    </tr>
    <tr>
      <td></td>
      <td>Notodden</td>
      <td>0807</td>
    </tr>
    <tr>
      <td></td>
      <td>Siljan</td>
      <td>0811</td>
    </tr>
    <tr>
      <td></td>
      <td>Bamble</td>
      <td>0814</td>
    </tr>
    <tr>
      <td></td>
      <td>Kragerø</td>
      <td>0815</td>
    </tr>
    <tr>
      <td></td>
      <td>Drangedal</td>
      <td>0817</td>
    </tr>
    <tr>
      <td></td>
      <td>Nome</td>
      <td>0819</td>
    </tr>
    <tr>
      <td></td>
      <td>Bø i Telemark</td>
      <td>0821</td>
    </tr>
    <tr>
      <td></td>
      <td>Sauherad</td>
      <td>0822</td>
    </tr>
    <tr>
      <td></td>
      <td>Tinn</td>
      <td>0826</td>
    </tr>
    <tr>
      <td></td>
      <td>Hjartdal</td>
      <td>0827</td>
    </tr>
    <tr>
      <td></td>
      <td>Seljord</td>
      <td>0828</td>
    </tr>
    <tr>
      <td></td>
      <td>Kviteseid</td>
      <td>0829</td>
    </tr>
    <tr>
      <td></td>
      <td>Nissedal</td>
      <td>0830</td>
    </tr>
    <tr>
      <td></td>
      <td>Fyresdal</td>
      <td>0831</td>
    </tr>
    <tr>
      <td></td>
      <td>Tokke</td>
      <td>0833</td>
    </tr>
    <tr>
      <td></td>
      <td>Vinje</td>
      <td>0834</td>
    </tr>
    <tr>
      <td></td>
      <td>Risør</td>
      <td>0901</td>
    </tr>
    <tr>
      <td></td>
      <td>Arendal (utgått)</td>
      <td>0903</td>
    </tr>
    <tr>
      <td></td>
      <td>Grimstad</td>
      <td>0904</td>
    </tr>
    <tr>
      <td></td>
      <td>Arendal</td>
      <td>0906</td>
    </tr>
    <tr>
      <td></td>
      <td>Gjerstad</td>
      <td>0911</td>
    </tr>
    <tr>
      <td></td>
      <td>Vegårshei</td>
      <td>0912</td>
    </tr>
    <tr>
      <td></td>
      <td>Tvedestrand</td>
      <td>0914</td>
    </tr>
    <tr>
      <td></td>
      <td>Moland (utgått)</td>
      <td>0918</td>
    </tr>
    <tr>
      <td></td>
      <td>Froland</td>
      <td>0919</td>
    </tr>
    <tr>
      <td></td>
      <td>Øyestad (utgått)</td>
      <td>0920</td>
    </tr>
    <tr>
      <td></td>
      <td>Tromøy (utgått)</td>
      <td>0921</td>
    </tr>
    <tr>
      <td></td>
      <td>Hisøy (utgått)</td>
      <td>0922</td>
    </tr>
    <tr>
      <td></td>
      <td>Lillesand</td>
      <td>0926</td>
    </tr>
    <tr>
      <td></td>
      <td>Birkenes</td>
      <td>0928</td>
    </tr>
    <tr>
      <td></td>
      <td>Åmli</td>
      <td>0929</td>
    </tr>
    <tr>
      <td></td>
      <td>Iveland</td>
      <td>0935</td>
    </tr>
    <tr>
      <td></td>
      <td>Evje og Hornnes</td>
      <td>0937</td>
    </tr>
    <tr>
      <td></td>
      <td>Bygland</td>
      <td>0938</td>
    </tr>
    <tr>
      <td></td>
      <td>Valle</td>
      <td>0940</td>
    </tr>
    <tr>
      <td></td>
      <td>Bykle</td>
      <td>0941</td>
    </tr>
    <tr>
      <td></td>
      <td>Kristiansand</td>
      <td>1001</td>
    </tr>
    <tr>
      <td></td>
      <td>Mandal</td>
      <td>1002</td>
    </tr>
    <tr>
      <td></td>
      <td>Farsund</td>
      <td>1003</td>
    </tr>
    <tr>
      <td></td>
      <td>Flekkefjord</td>
      <td>1004</td>
    </tr>
    <tr>
      <td></td>
      <td>Vennesla</td>
      <td>1014</td>
    </tr>
    <tr>
      <td></td>
      <td>Songdalen</td>
      <td>1017</td>
    </tr>
    <tr>
      <td></td>
      <td>Søgne</td>
      <td>1018</td>
    </tr>
    <tr>
      <td></td>
      <td>Marnardal</td>
      <td>1021</td>
    </tr>
    <tr>
      <td></td>
      <td>Åseral</td>
      <td>1026</td>
    </tr>
    <tr>
      <td></td>
      <td>Audnedal</td>
      <td>1027</td>
    </tr>
    <tr>
      <td></td>
      <td>Lindesnes</td>
      <td>1029</td>
    </tr>
    <tr>
      <td></td>
      <td>Lyngdal</td>
      <td>1032</td>
    </tr>
    <tr>
      <td></td>
      <td>Hægebostad</td>
      <td>1034</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvinesdal</td>
      <td>1037</td>
    </tr>
    <tr>
      <td></td>
      <td>Sirdal</td>
      <td>1046</td>
    </tr>
    <tr>
      <td></td>
      <td>Eigersund</td>
      <td>1101</td>
    </tr>
    <tr>
      <td></td>
      <td>Sandnes</td>
      <td>1102</td>
    </tr>
    <tr>
      <td></td>
      <td>Stavanger</td>
      <td>1103</td>
    </tr>
    <tr>
      <td></td>
      <td>Haugesund</td>
      <td>1106</td>
    </tr>
    <tr>
      <td></td>
      <td>Sokndal</td>
      <td>1111</td>
    </tr>
    <tr>
      <td></td>
      <td>Lund</td>
      <td>1112</td>
    </tr>
    <tr>
      <td></td>
      <td>Bjerkreim</td>
      <td>1114</td>
    </tr>
    <tr>
      <td></td>
      <td>Hå</td>
      <td>1119</td>
    </tr>
    <tr>
      <td></td>
      <td>Klepp</td>
      <td>1120</td>
    </tr>
    <tr>
      <td></td>
      <td>Time</td>
      <td>1121</td>
    </tr>
    <tr>
      <td></td>
      <td>Gjesdal</td>
      <td>1122</td>
    </tr>
    <tr>
      <td></td>
      <td>Sola</td>
      <td>1124</td>
    </tr>
    <tr>
      <td></td>
      <td>Randaberg</td>
      <td>1127</td>
    </tr>
    <tr>
      <td></td>
      <td>Forsand</td>
      <td>1129</td>
    </tr>
    <tr>
      <td></td>
      <td>Strand</td>
      <td>1130</td>
    </tr>
    <tr>
      <td></td>
      <td>Hjelmeland</td>
      <td>1133</td>
    </tr>
    <tr>
      <td></td>
      <td>Suldal</td>
      <td>1134</td>
    </tr>
    <tr>
      <td></td>
      <td>Sauda</td>
      <td>1135</td>
    </tr>
    <tr>
      <td></td>
      <td>Finnøy</td>
      <td>1141</td>
    </tr>
    <tr>
      <td></td>
      <td>Rennesøy</td>
      <td>1142</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvitsøy</td>
      <td>1144</td>
    </tr>
    <tr>
      <td></td>
      <td>Bokn</td>
      <td>1145</td>
    </tr>
    <tr>
      <td></td>
      <td>Tysvær</td>
      <td>1146</td>
    </tr>
    <tr>
      <td></td>
      <td>Karmøy</td>
      <td>1149</td>
    </tr>
    <tr>
      <td></td>
      <td>Utsira</td>
      <td>1151</td>
    </tr>
    <tr>
      <td></td>
      <td>Vindafjord ((utgått)</td>
      <td>1154</td>
    </tr>
    <tr>
      <td></td>
      <td>Ølen (utgått)</td>
      <td>1159</td>
    </tr>
    <tr>
      <td></td>
      <td>Vindafjord</td>
      <td>1160</td>
    </tr>
    <tr>
      <td></td>
      <td>Bergen</td>
      <td>1201</td>
    </tr>
    <tr>
      <td></td>
      <td>Etne</td>
      <td>1211</td>
    </tr>
    <tr>
      <td></td>
      <td>Ølen (utgått)</td>
      <td>1214</td>
    </tr>
    <tr>
      <td></td>
      <td>Sveio</td>
      <td>1216</td>
    </tr>
    <tr>
      <td></td>
      <td>Bømlo</td>
      <td>1219</td>
    </tr>
    <tr>
      <td></td>
      <td>Stord</td>
      <td>1221</td>
    </tr>
    <tr>
      <td></td>
      <td>Fitjar</td>
      <td>1222</td>
    </tr>
    <tr>
      <td></td>
      <td>Tysnes</td>
      <td>1223</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvinnherad</td>
      <td>1224</td>
    </tr>
    <tr>
      <td></td>
      <td>Jondal</td>
      <td>1227</td>
    </tr>
    <tr>
      <td></td>
      <td>Odda</td>
      <td>1228</td>
    </tr>
    <tr>
      <td></td>
      <td>Ullensvang</td>
      <td>1231</td>
    </tr>
    <tr>
      <td></td>
      <td>Eidfjord</td>
      <td>1232</td>
    </tr>
    <tr>
      <td></td>
      <td>Ulvik</td>
      <td>1233</td>
    </tr>
    <tr>
      <td></td>
      <td>Granvin</td>
      <td>1234</td>
    </tr>
    <tr>
      <td></td>
      <td>Voss</td>
      <td>1235</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvam</td>
      <td>1238</td>
    </tr>
    <tr>
      <td></td>
      <td>Fusa</td>
      <td>1241</td>
    </tr>
    <tr>
      <td></td>
      <td>Samnanger</td>
      <td>1242</td>
    </tr>
    <tr>
      <td></td>
      <td>Os i Hordaland</td>
      <td>1243</td>
    </tr>
    <tr>
      <td></td>
      <td>Austevoll</td>
      <td>1244</td>
    </tr>
    <tr>
      <td></td>
      <td>Sund</td>
      <td>1245</td>
    </tr>
    <tr>
      <td></td>
      <td>Fjell</td>
      <td>1246</td>
    </tr>
    <tr>
      <td></td>
      <td>Askøy</td>
      <td>1247</td>
    </tr>
    <tr>
      <td></td>
      <td>Vaksdal</td>
      <td>1251</td>
    </tr>
    <tr>
      <td></td>
      <td>Modalen</td>
      <td>1252</td>
    </tr>
    <tr>
      <td></td>
      <td>Osterøy</td>
      <td>1253</td>
    </tr>
    <tr>
      <td></td>
      <td>Meland</td>
      <td>1256</td>
    </tr>
    <tr>
      <td></td>
      <td>Øygarden</td>
      <td>1259</td>
    </tr>
    <tr>
      <td></td>
      <td>Radøy</td>
      <td>1260</td>
    </tr>
    <tr>
      <td></td>
      <td>Lindås</td>
      <td>1263</td>
    </tr>
    <tr>
      <td></td>
      <td>Austrheim</td>
      <td>1264</td>
    </tr>
    <tr>
      <td></td>
      <td>Fedje</td>
      <td>1265</td>
    </tr>
    <tr>
      <td></td>
      <td>Masfjorden</td>
      <td>1266</td>
    </tr>
    <tr>
      <td></td>
      <td>Flora</td>
      <td>1401</td>
    </tr>
    <tr>
      <td></td>
      <td>Gulen</td>
      <td>1411</td>
    </tr>
    <tr>
      <td></td>
      <td>Solund</td>
      <td>1412</td>
    </tr>
    <tr>
      <td></td>
      <td>Hyllestad</td>
      <td>1413</td>
    </tr>
    <tr>
      <td></td>
      <td>Høyanger</td>
      <td>1416</td>
    </tr>
    <tr>
      <td></td>
      <td>Vik</td>
      <td>1417</td>
    </tr>
    <tr>
      <td></td>
      <td>Balestrand</td>
      <td>1418</td>
    </tr>
    <tr>
      <td></td>
      <td>Leikanger</td>
      <td>1419</td>
    </tr>
    <tr>
      <td></td>
      <td>Sogndal</td>
      <td>1420</td>
    </tr>
    <tr>
      <td></td>
      <td>Aurland</td>
      <td>1421</td>
    </tr>
    <tr>
      <td></td>
      <td>Lærdal</td>
      <td>1422</td>
    </tr>
    <tr>
      <td></td>
      <td>Årdal</td>
      <td>1424</td>
    </tr>
    <tr>
      <td></td>
      <td>Luster</td>
      <td>1426</td>
    </tr>
    <tr>
      <td></td>
      <td>Askvoll</td>
      <td>1428</td>
    </tr>
    <tr>
      <td></td>
      <td>Fjaler</td>
      <td>1429</td>
    </tr>
    <tr>
      <td></td>
      <td>Gaular</td>
      <td>1430</td>
    </tr>
    <tr>
      <td></td>
      <td>Jølster</td>
      <td>1431</td>
    </tr>
    <tr>
      <td></td>
      <td>Førde</td>
      <td>1432</td>
    </tr>
    <tr>
      <td></td>
      <td>Naustdal</td>
      <td>1433</td>
    </tr>
    <tr>
      <td></td>
      <td>Bremanger</td>
      <td>1438</td>
    </tr>
    <tr>
      <td></td>
      <td>Vågsøy</td>
      <td>1439</td>
    </tr>
    <tr>
      <td></td>
      <td>Selje</td>
      <td>1441</td>
    </tr>
    <tr>
      <td></td>
      <td>Eid</td>
      <td>1443</td>
    </tr>
    <tr>
      <td></td>
      <td>Hornindal</td>
      <td>1444</td>
    </tr>
    <tr>
      <td></td>
      <td>Gloppen</td>
      <td>1445</td>
    </tr>
    <tr>
      <td></td>
      <td>Stryn</td>
      <td>1449</td>
    </tr>
    <tr>
      <td></td>
      <td>Molde</td>
      <td>1502</td>
    </tr>
    <tr>
      <td></td>
      <td>Ålesund</td>
      <td>1504</td>
    </tr>
    <tr>
      <td></td>
      <td>Kristiansund</td>
      <td>1505</td>
    </tr>
    <tr>
      <td></td>
      <td>Vanylven</td>
      <td>1511</td>
    </tr>
    <tr>
      <td></td>
      <td>Sande i Møre og Romsdal</td>
      <td>1514</td>
    </tr>
    <tr>
      <td></td>
      <td>Herøy i Møre og Romsdal</td>
      <td>1515</td>
    </tr>
    <tr>
      <td></td>
      <td>Ulstein</td>
      <td>1516</td>
    </tr>
    <tr>
      <td></td>
      <td>Hareid</td>
      <td>1517</td>
    </tr>
    <tr>
      <td></td>
      <td>Volda</td>
      <td>1519</td>
    </tr>
    <tr>
      <td></td>
      <td>Ørsta</td>
      <td>1520</td>
    </tr>
    <tr>
      <td></td>
      <td>Ørskog</td>
      <td>1523</td>
    </tr>
    <tr>
      <td></td>
      <td>Norddal</td>
      <td>1524</td>
    </tr>
    <tr>
      <td></td>
      <td>Stranda</td>
      <td>1525</td>
    </tr>
    <tr>
      <td></td>
      <td>Stordal</td>
      <td>1526</td>
    </tr>
    <tr>
      <td></td>
      <td>Sykkylven</td>
      <td>1528</td>
    </tr>
    <tr>
      <td></td>
      <td>Skodje</td>
      <td>1529</td>
    </tr>
    <tr>
      <td></td>
      <td>Sula</td>
      <td>1531</td>
    </tr>
    <tr>
      <td></td>
      <td>Giske</td>
      <td>1532</td>
    </tr>
    <tr>
      <td></td>
      <td>Haram</td>
      <td>1534</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestnes</td>
      <td>1535</td>
    </tr>
    <tr>
      <td></td>
      <td>Rauma</td>
      <td>1539</td>
    </tr>
    <tr>
      <td></td>
      <td>Nesset</td>
      <td>1543</td>
    </tr>
    <tr>
      <td></td>
      <td>Midsund</td>
      <td>1545</td>
    </tr>
    <tr>
      <td></td>
      <td>Sandøy</td>
      <td>1546</td>
    </tr>
    <tr>
      <td></td>
      <td>Aukra</td>
      <td>1547</td>
    </tr>
    <tr>
      <td></td>
      <td>Fræna</td>
      <td>1548</td>
    </tr>
    <tr>
      <td></td>
      <td>Eide</td>
      <td>1551</td>
    </tr>
    <tr>
      <td></td>
      <td>Averøy</td>
      <td>1554</td>
    </tr>
    <tr>
      <td></td>
      <td>Gjemnes</td>
      <td>1557</td>
    </tr>
    <tr>
      <td></td>
      <td>Tingvoll</td>
      <td>1560</td>
    </tr>
    <tr>
      <td></td>
      <td>Sunndal</td>
      <td>1563</td>
    </tr>
    <tr>
      <td></td>
      <td>Surnadal</td>
      <td>1566</td>
    </tr>
    <tr>
      <td></td>
      <td>Rindal (utgått)</td>
      <td>1567</td>
    </tr>
    <tr>
      <td></td>
      <td>Aure (utgått)</td>
      <td>1569</td>
    </tr>
    <tr>
      <td></td>
      <td>Halsa</td>
      <td>1571</td>
    </tr>
    <tr>
      <td></td>
      <td>Tustna (utgått)</td>
      <td>1572</td>
    </tr>
    <tr>
      <td></td>
      <td>Smøla</td>
      <td>1573</td>
    </tr>
    <tr>
      <td></td>
      <td>Aure</td>
      <td>1576</td>
    </tr>
    <tr>
      <td></td>
      <td>Trondheim (utgått)</td>
      <td>1601</td>
    </tr>
    <tr>
      <td></td>
      <td>Hemne (utgått)</td>
      <td>1612</td>
    </tr>
    <tr>
      <td></td>
      <td>Snillfjord (utgått)</td>
      <td>1613</td>
    </tr>
    <tr>
      <td></td>
      <td>Hitra (utgått)</td>
      <td>1617</td>
    </tr>
    <tr>
      <td></td>
      <td>Frøya (utgått)</td>
      <td>1620</td>
    </tr>
    <tr>
      <td></td>
      <td>Ørland (utgått)</td>
      <td>1621</td>
    </tr>
    <tr>
      <td></td>
      <td>Agdenes (utgått)</td>
      <td>1622</td>
    </tr>
    <tr>
      <td></td>
      <td>Rissa (utgått)</td>
      <td>1624</td>
    </tr>
    <tr>
      <td></td>
      <td>Bjugn (utgått)</td>
      <td>1627</td>
    </tr>
    <tr>
      <td></td>
      <td>Åfjord (utgått)</td>
      <td>1630</td>
    </tr>
    <tr>
      <td></td>
      <td>Roan (utgått)</td>
      <td>1632</td>
    </tr>
    <tr>
      <td></td>
      <td>Osen (utgått)</td>
      <td>1633</td>
    </tr>
    <tr>
      <td></td>
      <td>Oppdal (utgått)</td>
      <td>1634</td>
    </tr>
    <tr>
      <td></td>
      <td>Rennebu (utgått)</td>
      <td>1635</td>
    </tr>
    <tr>
      <td></td>
      <td>Meldal (utgått)</td>
      <td>1636</td>
    </tr>
    <tr>
      <td></td>
      <td>Orkdal (utgått)</td>
      <td>1638</td>
    </tr>
    <tr>
      <td></td>
      <td>Røros (utgått)</td>
      <td>1640</td>
    </tr>
    <tr>
      <td></td>
      <td>Holtålen (utgått)</td>
      <td>1644</td>
    </tr>
    <tr>
      <td></td>
      <td>Midtre Gauldal (utgått)</td>
      <td>1648</td>
    </tr>
    <tr>
      <td></td>
      <td>Melhus (utgått)</td>
      <td>1653</td>
    </tr>
    <tr>
      <td></td>
      <td>Skaun (utgått)</td>
      <td>1657</td>
    </tr>
    <tr>
      <td></td>
      <td>Klæbu (utgått)</td>
      <td>1662</td>
    </tr>
    <tr>
      <td></td>
      <td>Malvik (utgått)</td>
      <td>1663</td>
    </tr>
    <tr>
      <td></td>
      <td>Selbu (utgått)</td>
      <td>1664</td>
    </tr>
    <tr>
      <td></td>
      <td>Tydal (utgått)</td>
      <td>1665</td>
    </tr>
    <tr>
      <td></td>
      <td>Steinkjer (utgått)</td>
      <td>1702</td>
    </tr>
    <tr>
      <td></td>
      <td>Namsos (utgått)</td>
      <td>1703</td>
    </tr>
    <tr>
      <td></td>
      <td>Meråker (utgått)</td>
      <td>1711</td>
    </tr>
    <tr>
      <td></td>
      <td>Stjørdal (utgått)</td>
      <td>1714</td>
    </tr>
    <tr>
      <td></td>
      <td>Frosta (utgått)</td>
      <td>1717</td>
    </tr>
    <tr>
      <td></td>
      <td>Leksvik (utgått)</td>
      <td>1718</td>
    </tr>
    <tr>
      <td></td>
      <td>Levanger (utgått)</td>
      <td>1719</td>
    </tr>
    <tr>
      <td></td>
      <td>Verdal (utgått)</td>
      <td>1721</td>
    </tr>
    <tr>
      <td></td>
      <td>Mosvik (utgått)</td>
      <td>1723</td>
    </tr>
    <tr>
      <td></td>
      <td>Verran (utgått)</td>
      <td>1724</td>
    </tr>
    <tr>
      <td></td>
      <td>Namdalseid (utgått)</td>
      <td>1725</td>
    </tr>
    <tr>
      <td></td>
      <td>Inderøy (utgått)</td>
      <td>1729</td>
    </tr>
    <tr>
      <td></td>
      <td>Snåase – Snåsa (utgått)</td>
      <td>1736</td>
    </tr>
    <tr>
      <td></td>
      <td>Lierne (utgått)</td>
      <td>1738</td>
    </tr>
    <tr>
      <td></td>
      <td>Raarvihke – Røyrvik (utgått)</td>
      <td>1739</td>
    </tr>
    <tr>
      <td></td>
      <td>Namsskogan (utgått)</td>
      <td>1740</td>
    </tr>
    <tr>
      <td></td>
      <td>Grong (utgått)</td>
      <td>1742</td>
    </tr>
    <tr>
      <td></td>
      <td>Høylandet (utgått)</td>
      <td>1743</td>
    </tr>
    <tr>
      <td></td>
      <td>Overhalla (utgått)</td>
      <td>1744</td>
    </tr>
    <tr>
      <td></td>
      <td>Fosnes (utgått)</td>
      <td>1748</td>
    </tr>
    <tr>
      <td></td>
      <td>Flatanger (utgått)</td>
      <td>1749</td>
    </tr>
    <tr>
      <td></td>
      <td>Vikna (utgått)</td>
      <td>1750</td>
    </tr>
    <tr>
      <td></td>
      <td>Nærøy (utgått)</td>
      <td>1751</td>
    </tr>
    <tr>
      <td></td>
      <td>Leka (utgått)</td>
      <td>1755</td>
    </tr>
    <tr>
      <td></td>
      <td>Inderøy (utgått)</td>
      <td>1756</td>
    </tr>
    <tr>
      <td></td>
      <td>Bodø</td>
      <td>1804</td>
    </tr>
    <tr>
      <td></td>
      <td>Narvik</td>
      <td>1805</td>
    </tr>
    <tr>
      <td></td>
      <td>Bindal</td>
      <td>1811</td>
    </tr>
    <tr>
      <td></td>
      <td>Sømna</td>
      <td>1812</td>
    </tr>
    <tr>
      <td></td>
      <td>Brønnøy</td>
      <td>1813</td>
    </tr>
    <tr>
      <td></td>
      <td>Vega</td>
      <td>1815</td>
    </tr>
    <tr>
      <td></td>
      <td>Vevelstad</td>
      <td>1816</td>
    </tr>
    <tr>
      <td></td>
      <td>Herøy i Nordland</td>
      <td>1818</td>
    </tr>
    <tr>
      <td></td>
      <td>Alstahaug</td>
      <td>1820</td>
    </tr>
    <tr>
      <td></td>
      <td>Leirfjord</td>
      <td>1822</td>
    </tr>
    <tr>
      <td></td>
      <td>Vefsn</td>
      <td>1824</td>
    </tr>
    <tr>
      <td></td>
      <td>Grane</td>
      <td>1825</td>
    </tr>
    <tr>
      <td></td>
      <td>Hattfjelldal</td>
      <td>1826</td>
    </tr>
    <tr>
      <td></td>
      <td>Dønna</td>
      <td>1827</td>
    </tr>
    <tr>
      <td></td>
      <td>Nesna</td>
      <td>1828</td>
    </tr>
    <tr>
      <td></td>
      <td>Hemnes</td>
      <td>1832</td>
    </tr>
    <tr>
      <td></td>
      <td>Rana</td>
      <td>1833</td>
    </tr>
    <tr>
      <td></td>
      <td>Lurøy</td>
      <td>1834</td>
    </tr>
    <tr>
      <td></td>
      <td>Træna</td>
      <td>1835</td>
    </tr>
    <tr>
      <td></td>
      <td>Rødøy</td>
      <td>1836</td>
    </tr>
    <tr>
      <td></td>
      <td>Meløy</td>
      <td>1837</td>
    </tr>
    <tr>
      <td></td>
      <td>Gildeskål</td>
      <td>1838</td>
    </tr>
    <tr>
      <td></td>
      <td>Beiarn</td>
      <td>1839</td>
    </tr>
    <tr>
      <td></td>
      <td>Saltdal</td>
      <td>1840</td>
    </tr>
    <tr>
      <td></td>
      <td>Fauske – Fuossko</td>
      <td>1841</td>
    </tr>
    <tr>
      <td></td>
      <td>Skjerstad (utgått)</td>
      <td>1842</td>
    </tr>
    <tr>
      <td></td>
      <td>Sørfold</td>
      <td>1845</td>
    </tr>
    <tr>
      <td></td>
      <td>Steigen</td>
      <td>1848</td>
    </tr>
    <tr>
      <td></td>
      <td>Hamarøy – Hábmer</td>
      <td>1849</td>
    </tr>
    <tr>
      <td></td>
      <td>Divtasvuodna – Tysfjord</td>
      <td>1850</td>
    </tr>
    <tr>
      <td></td>
      <td>Lødingen</td>
      <td>1851</td>
    </tr>
    <tr>
      <td></td>
      <td>Tjeldsund</td>
      <td>1852</td>
    </tr>
    <tr>
      <td></td>
      <td>Evenes</td>
      <td>1853</td>
    </tr>
    <tr>
      <td></td>
      <td>Ballangen</td>
      <td>1854</td>
    </tr>
    <tr>
      <td></td>
      <td>Røst</td>
      <td>1856</td>
    </tr>
    <tr>
      <td></td>
      <td>Værøy</td>
      <td>1857</td>
    </tr>
    <tr>
      <td></td>
      <td>Flakstad</td>
      <td>1859</td>
    </tr>
    <tr>
      <td></td>
      <td>Vestvågøy</td>
      <td>1860</td>
    </tr>
    <tr>
      <td></td>
      <td>Vågan</td>
      <td>1865</td>
    </tr>
    <tr>
      <td></td>
      <td>Hadsel</td>
      <td>1866</td>
    </tr>
    <tr>
      <td></td>
      <td>Bø i Nordland</td>
      <td>1867</td>
    </tr>
    <tr>
      <td></td>
      <td>Øksnes</td>
      <td>1868</td>
    </tr>
    <tr>
      <td></td>
      <td>Sortland – Suortá</td>
      <td>1870</td>
    </tr>
    <tr>
      <td></td>
      <td>Andøy</td>
      <td>1871</td>
    </tr>
    <tr>
      <td></td>
      <td>Moskenes</td>
      <td>1874</td>
    </tr>
    <tr>
      <td></td>
      <td>Harstad (utgått)</td>
      <td>1901</td>
    </tr>
    <tr>
      <td></td>
      <td>Tromsø</td>
      <td>1902</td>
    </tr>
    <tr>
      <td></td>
      <td>Harstad – Hárstták</td>
      <td>1903</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvæfjord</td>
      <td>1911</td>
    </tr>
    <tr>
      <td></td>
      <td>Skånland</td>
      <td>1913</td>
    </tr>
    <tr>
      <td></td>
      <td>Bjarkøy (utgått)</td>
      <td>1915</td>
    </tr>
    <tr>
      <td></td>
      <td>Ibestad</td>
      <td>1917</td>
    </tr>
    <tr>
      <td></td>
      <td>Gratangen</td>
      <td>1919</td>
    </tr>
    <tr>
      <td></td>
      <td>Loabák – Lavangen</td>
      <td>1920</td>
    </tr>
    <tr>
      <td></td>
      <td>Bardu</td>
      <td>1922</td>
    </tr>
    <tr>
      <td></td>
      <td>Salangen</td>
      <td>1923</td>
    </tr>
    <tr>
      <td></td>
      <td>Målselv</td>
      <td>1924</td>
    </tr>
    <tr>
      <td></td>
      <td>Sørreisa</td>
      <td>1925</td>
    </tr>
    <tr>
      <td></td>
      <td>Dyrøy</td>
      <td>1926</td>
    </tr>
    <tr>
      <td></td>
      <td>Tranøy</td>
      <td>1927</td>
    </tr>
    <tr>
      <td></td>
      <td>Torsken</td>
      <td>1928</td>
    </tr>
    <tr>
      <td></td>
      <td>Berg</td>
      <td>1929</td>
    </tr>
    <tr>
      <td></td>
      <td>Lenvik</td>
      <td>1931</td>
    </tr>
    <tr>
      <td></td>
      <td>Balsfjord</td>
      <td>1933</td>
    </tr>
    <tr>
      <td></td>
      <td>Karlsøy</td>
      <td>1936</td>
    </tr>
    <tr>
      <td></td>
      <td>Lyngen</td>
      <td>1938</td>
    </tr>
    <tr>
      <td></td>
      <td>Storfjord – Omasvuotna – Omasvuono</td>
      <td>1939</td>
    </tr>
    <tr>
      <td></td>
      <td>Gáivuotna – Kåfjord – Kaivuono</td>
      <td>1940</td>
    </tr>
    <tr>
      <td></td>
      <td>Skjervøy</td>
      <td>1941</td>
    </tr>
    <tr>
      <td></td>
      <td>Nordreisa – Ráisa – Raisi</td>
      <td>1942</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvænangen</td>
      <td>1943</td>
    </tr>
    <tr>
      <td></td>
      <td>Hammerfest (utgått)</td>
      <td>2001</td>
    </tr>
    <tr>
      <td></td>
      <td>Vardø</td>
      <td>2002</td>
    </tr>
    <tr>
      <td></td>
      <td>Vadsø</td>
      <td>2003</td>
    </tr>
    <tr>
      <td></td>
      <td>Hammerfest</td>
      <td>2004</td>
    </tr>
    <tr>
      <td></td>
      <td>Guovdageaidnu – Kautokeino</td>
      <td>2011</td>
    </tr>
    <tr>
      <td></td>
      <td>Alta</td>
      <td>2012</td>
    </tr>
    <tr>
      <td></td>
      <td>Loppa</td>
      <td>2014</td>
    </tr>
    <tr>
      <td></td>
      <td>Hasvik</td>
      <td>2015</td>
    </tr>
    <tr>
      <td></td>
      <td>Sørøysund (utgått)</td>
      <td>2016</td>
    </tr>
    <tr>
      <td></td>
      <td>Kvalsund</td>
      <td>2017</td>
    </tr>
    <tr>
      <td></td>
      <td>Måsøy</td>
      <td>2018</td>
    </tr>
    <tr>
      <td></td>
      <td>Nordkapp</td>
      <td>2019</td>
    </tr>
    <tr>
      <td></td>
      <td>Porsanger – Porsáŋgu – Porsanki</td>
      <td>2020</td>
    </tr>
    <tr>
      <td></td>
      <td>Kárášjohka – Karasjok</td>
      <td>2021</td>
    </tr>
    <tr>
      <td></td>
      <td>Lebesby</td>
      <td>2022</td>
    </tr>
    <tr>
      <td></td>
      <td>Gamvik</td>
      <td>2023</td>
    </tr>
    <tr>
      <td></td>
      <td>Berlevåg</td>
      <td>2024</td>
    </tr>
    <tr>
      <td></td>
      <td>Deatnu – Tana</td>
      <td>2025</td>
    </tr>
    <tr>
      <td></td>
      <td>Unjárga – Nesseby</td>
      <td>2027</td>
    </tr>
    <tr>
      <td></td>
      <td>Båtsfjord</td>
      <td>2028</td>
    </tr>
    <tr>
      <td></td>
      <td>Sør-Varanger</td>
      <td>2030</td>
    </tr>
    <tr>
      <td></td>
      <td>Svalbard</td>
      <td>2100</td>
    </tr>
    <tr>
      <td></td>
      <td>Spitsbergen (utgått)</td>
      <td>2111</td>
    </tr>
    <tr>
      <td></td>
      <td>Bjørnøya (utgått)</td>
      <td>2121</td>
    </tr>
    <tr>
      <td></td>
      <td>Hopen (utgått)</td>
      <td>2131</td>
    </tr>
    <tr>
      <td></td>
      <td>Jan Mayen</td>
      <td>2211</td>
    </tr>
    <tr>
      <td></td>
      <td>Sokkelen sør for 62 grader Nord</td>
      <td>2311</td>
    </tr>
    <tr>
      <td></td>
      <td>Sokkelen nord for 62 grader Nord</td>
      <td>2321</td>
    </tr>
    <tr>
      <td></td>
      <td>Trondheim</td>
      <td>5001</td>
    </tr>
    <tr>
      <td></td>
      <td>Steinkjer</td>
      <td>5004</td>
    </tr>
    <tr>
      <td></td>
      <td>Namsos</td>
      <td>5005</td>
    </tr>
    <tr>
      <td></td>
      <td>Hemne</td>
      <td>5011</td>
    </tr>
    <tr>
      <td></td>
      <td>Snillfjord</td>
      <td>5012</td>
    </tr>
    <tr>
      <td></td>
      <td>Hitra</td>
      <td>5013</td>
    </tr>
    <tr>
      <td></td>
      <td>Frøya</td>
      <td>5014</td>
    </tr>
    <tr>
      <td></td>
      <td>Ørland</td>
      <td>5015</td>
    </tr>
    <tr>
      <td></td>
      <td>Agdenes</td>
      <td>5016</td>
    </tr>
    <tr>
      <td></td>
      <td>Bjugn</td>
      <td>5017</td>
    </tr>
    <tr>
      <td></td>
      <td>Åfjord</td>
      <td>5018</td>
    </tr>
    <tr>
      <td></td>
      <td>Roan</td>
      <td>5019</td>
    </tr>
    <tr>
      <td></td>
      <td>Osen</td>
      <td>5020</td>
    </tr>
    <tr>
      <td></td>
      <td>Oppdal</td>
      <td>5021</td>
    </tr>
    <tr>
      <td></td>
      <td>Rennebu</td>
      <td>5022</td>
    </tr>
    <tr>
      <td></td>
      <td>Meldal</td>
      <td>5023</td>
    </tr>
    <tr>
      <td></td>
      <td>Orkdal</td>
      <td>5024</td>
    </tr>
    <tr>
      <td></td>
      <td>Røros</td>
      <td>5025</td>
    </tr>
    <tr>
      <td></td>
      <td>Holtålen</td>
      <td>5026</td>
    </tr>
    <tr>
      <td></td>
      <td>Midtre Gauldal</td>
      <td>5027</td>
    </tr>
    <tr>
      <td></td>
      <td>Melhus</td>
      <td>5028</td>
    </tr>
    <tr>
      <td></td>
      <td>Skaun</td>
      <td>5029</td>
    </tr>
    <tr>
      <td></td>
      <td>Klæbu</td>
      <td>5030</td>
    </tr>
    <tr>
      <td></td>
      <td>Malvik</td>
      <td>5031</td>
    </tr>
    <tr>
      <td></td>
      <td>Selbu</td>
      <td>5032</td>
    </tr>
    <tr>
      <td></td>
      <td>Tydal</td>
      <td>5033</td>
    </tr>
    <tr>
      <td></td>
      <td>Meråker</td>
      <td>5034</td>
    </tr>
    <tr>
      <td></td>
      <td>Stjørdal</td>
      <td>5035</td>
    </tr>
    <tr>
      <td></td>
      <td>Frosta</td>
      <td>5036</td>
    </tr>
    <tr>
      <td></td>
      <td>Levanger</td>
      <td>5037</td>
    </tr>
    <tr>
      <td></td>
      <td>Verdal</td>
      <td>5038</td>
    </tr>
    <tr>
      <td></td>
      <td>Verran</td>
      <td>5039</td>
    </tr>
    <tr>
      <td></td>
      <td>Namdalseid</td>
      <td>5040</td>
    </tr>
    <tr>
      <td></td>
      <td>Snåase – Snåsa</td>
      <td>5041</td>
    </tr>
    <tr>
      <td></td>
      <td>Lierne</td>
      <td>5042</td>
    </tr>
    <tr>
      <td></td>
      <td>Raarvihke – Røyrvik</td>
      <td>5043</td>
    </tr>
    <tr>
      <td></td>
      <td>Namsskogan</td>
      <td>5044</td>
    </tr>
    <tr>
      <td></td>
      <td>Grong</td>
      <td>5045</td>
    </tr>
    <tr>
      <td></td>
      <td>Høylandet</td>
      <td>5046</td>
    </tr>
    <tr>
      <td></td>
      <td>Overhalla</td>
      <td>5047</td>
    </tr>
    <tr>
      <td></td>
      <td>Frosnes</td>
      <td>5048</td>
    </tr>
    <tr>
      <td></td>
      <td>Flatanger</td>
      <td>5049</td>
    </tr>
    <tr>
      <td></td>
      <td>Vikna</td>
      <td>5050</td>
    </tr>
    <tr>
      <td></td>
      <td>Nærøy</td>
      <td>5051</td>
    </tr>
    <tr>
      <td></td>
      <td>Leka</td>
      <td>5052</td>
    </tr>
    <tr>
      <td></td>
      <td>Inderøy</td>
      <td>5053</td>
    </tr>
    <tr>
      <td></td>
      <td>Indre Fosen</td>
      <td>5054</td>
    </tr>
    <tr>
      <td></td>
      <td>Rindal</td>
      <td>5061</td>
    </tr>
  </tbody>
</table>
