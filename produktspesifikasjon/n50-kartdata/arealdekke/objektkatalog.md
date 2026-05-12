### Datamodell

**Kilde:** [SOSI UML XMI-fil](https://sosi.geonorge.no/svn/SOSI/SOSI Del 3/Statens kartverk/N50_Arealdekke.xml)

<a href="arealdekke_feature_catalogue.png" title="Klikk for stor visning"><img src="arealdekke_feature_catalogue.png" alt="Datamodell Arealdekke" style="max-width: 100%; height: auto;" /></a>

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
      <td>Flate</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*

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
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*

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
      <td>sted som objektet eksisterer på</td>
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
      <td>- Fly – Kode hentet fra AIXM 4.5 (L=Landplane)<br />- Helikopter – Kode hentet fra AIXM 4.5 (H=Helicopter)</td>
    </tr>
  </tbody>
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
      <td>- Internasjonal<br />- Nasjonal<br />- Annen trafikk</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>IATAKode</strong></td>
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
      <td>- Alta<br />- Andenes/Andøya<br />- Bardufoss<br />- Bergen/Flesland<br />- Berlevåg<br />- Bodø<br />- Brønnøysund/Brønnøy<br />- Båtsfjord<br />- Fagernes/Leirin<br />- Farsund/Lista<br />- Florø<br />- Førde/Bringeland<br />- Gol/Klanten<br />- Hamar/Stafsberg<br />- Hammerfest<br />- Harstad/Narvik/Evenes<br />- Hasvik<br />- Haugesund/Karmøy<br />- Honningsvåg/Valan<br />- Kautokeino<br />- Kirkenes/Høybuktmoen<br />- Kristiansand/Kjevik<br />- Kristiansund/Kvernberget<br />- Lakselv/Banak<br />- Leknes<br />- Mehamn<br />- Molde/Årø<br />- Mosjøen/Kjærstad<br />- Moss/Rygge<br />- Namsos<br />- Narvik/Framnes<br />- Notodden<br />- Ny Ålesund/Hamnerabben<br />- Oslo/Gardermoen<br />- Røros<br />- Rørvik/Ryum<br />- Røst<br />- Sandane/Anda<br />- Sandefjord/Torp<br />- Sandnessjøen/Stokka<br />- Skien/Geiteryggen<br />- Sogndal/Haukåsen<br />- Stavanger/Sola<br />- Stokmarknes/Skagen<br />- Stord/Sørstokken<br />- Svalbard/Longyear<br />- Svolvær/Helle<br />- Sørkjosen<br />- Tromsø/Langnes<br />- Trondheim/Værnes<br />- Vadsø<br />- Vardø/Svartnes<br />- Værøy<br />- Ørland<br />- Ørsta-Volda/Hovden<br />- Ålesund/Vigra</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>ICAOKode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av lufthavn ved kode på fire alfanumeriske tegn.<br /><br />Merknad: Den første bokstaven tilordnes etter kontinent og angir et land eller en gruppe land på det samme kontinentet. Den andre bokstaven angir landet og de to siste angir lufthavn.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>ICAOKode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Albuskjell A<br />- Albuskjell F<br />- Alta<br />- Alvheim FPSO<br />- Andenes/Andøya<br />- Arendal/Sørlandet Sykehus HF<br />- Balder A<br />- Bardufoss<br />- Barentsburg<br />- Bergen/Flesland<br />- Bergen/Grønneviksøren<br />- Berlevåg<br />- Bjørnøya<br />- Bodø<br />- Brage A<br />- Brønnøysund/Brønnøy<br />- Bømoen<br />- Båtsfjord<br />- Cod<br />- Dokka/Thomlevold<br />- Dombås/Brunshagen<br />- Drammen/Sykehuset Buskerud HF<br />- Draugen<br />- Draugen FLP<br />- Draupner<br />- Edda<br />- Eggemoen<br />- Ekofisk A<br />- Ekofisk D<br />- Ekofisk K<br />- Eldfisk A<br />- Eldfisk B<br />- Elverum/Starmoen<br />- Elverum/Sykehuset Innlandet HF<br />- Embla<br />- Engeløy/Grådussan<br />- Fagernes/Leirin<br />- Farsund/Lista<br />- Fedje Heliport<br />- Florø<br />- Fritzøe<br />- Frøya/Flatval<br />- Fyresdal<br />- Førde/Bringeland<br />- Førde/Sentralsjukehuset<br />- Geilo/Dagali<br />- Gjoa<br />- Gol/Klanten<br />- Grane<br />- Grimsmoen<br />- Gullfaks A<br />- Gullfaks A SPM1<br />- Gullfaks A SPM2<br />- Gullfaks B<br />- Gullfaks C<br />- Gullknapp<br />- Gyda<br />- Hamar/Stafsberg<br />- Hammerfest<br />- Harstad/Narvik/Evenes<br />- Hasvik<br />- Hattfjelldal/Vollen<br />- Haugesund/Haugesund Sjukehus HF<br />- Haugesund/Karmøy<br />- Heidrun A<br />- Heimdal<br />- Hod<br />- Hokksund<br />- Honningsvåg/Valan<br />- Hopen<br />- Hornmoen<br />- Huldra<br />- Hønefoss, Ringerike Sykehus<br />- Isfjord<br />- Jan Mayen<br />- Jarlsberg<br />- Jotun A<br />- Jotun B<br />- Kautokeino<br />- Kirkenes/Høybuktmoen<br />- Kjeller<br />- Kristiansand/Kjevik<br />- Kristiansund/Kvernberget<br />- Kristin Semi<br />- Kvitebjørn<br />- Lakselv/Banak<br />- Leknes<br />- Lesja/Bjorli<br />- Lillehammer/Sykehuset Innlandet HF<br />- Lunde<br />- Lørenskog/Akershus Universitetssykehus<br />- Mehamn<br />- Molde/Årø<br />- Mosjøen/Kjærstad<br />- Moss/Rygge<br />- Namsos<br />- Namsos, Sykehuset<br />- Narvik/Framnes<br />- Njord A<br />- Njord B<br />- Norne A<br />- Notodden<br />- Ny Ålesund/Hamnerabben<br />- Oppdal/Fagerhaug<br />- Oseberg A<br />- Oseberg C<br />- Oseberg Sør<br />- Oseberg Øst<br />- Oslo, Rikshospitalet<br />- Oslo/Gardermoen<br />- Oslo/Ullevål Universitetssykehus<br />- Os/Vaksinen<br />- Petrojarl Varg<br />- Petrojarl 1<br />- Pyramiden<br />- Rakkestad<br />- Reinsvoll<br />- Ringebu/Frya<br />- Ringhorne<br />- Rognan<br />- Røros<br />- Rørvik/Ryum<br />- Røst<br />- Salangen/Elvenes<br />- Sandane/Anda<br />- Sandefjord/Torp<br />- Sandnessjøen/Stokka<br />- Skarv<br />- Skien/Geiteryggen<br />- Ski/Søndre Ski gård<br />- Sleipner A<br />- Sleipner B<br />- Snorre A<br />- Snorre B<br />- Snåsa/Gronora<br />- Sogndal/Haukåsen<br />- Statfjord A<br />- Statfjord B<br />- Statfjord C<br />- Statfjord C/SPM<br />- Stavanger/Sola<br />- Stavanger/Stavanger Universitetssykehus<br />- Stokmarknes/Skagen<br />- Stord/Sørstokken<br />- Sunndalsøra<br />- Svalbard/Longyear<br />- Svea<br />- Svolvær/Helle<br />- Sørkjosen<br />- Tambar<br />- Tor<br />- Troll A<br />- Troll B<br />- Troll C<br />- Tromsø/Langnes<br />- Trondheim/Rosten<br />- Trondheim/St. Olavs Hospital<br />- Trondheim/Værnes<br />- Trysil/Sæteråsen<br />- Tynset<br />- Ula<br />- Vadsø<br />- Valhall A<br />- Valhall Flank North<br />- Valhall Flank South<br />- Valle/Åraksøyene<br />- Vardø/Svartnes<br />- Varg<br />- Veslefrikk A<br />- Veslefrikk B<br />- Visund A<br />- Værøy<br />- Yme<br />- Ørland<br />- Ørsta-Volda/Hovden<br />- Østre Æra<br />- Ålesund/Vigra<br />- Ål/Hallingdal Sjukestugu<br />- Åsgård B<br />- Åsgård C<br />- Åsgård A</td>
    </tr>
  </tbody>
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
      <td>- Gon (400 graders deling) – 400 graders deling med positiv retning med sola<br />- Grader (360 graders deling) – 360 graders deling med positiv retning med sola<br />- Radianer – Radianer med positiv retning med sola</td>
    </tr>
  </tbody>
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
      <td>- Lokal<br />- Magnetisk nord<br />- Sant nord – (default)</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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
      <td>registrert høyde for vannspeilet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høyde</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
HavInnsjøSperre – rolle: havInnsjøSperre – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
InnsjøElvSperre – rolle: innsjøElvSperre – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
InnsjøInnsjøSperre – rolle: innsjøInnsjøSperre – kardinalitet: 0..*

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*

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
      <td>Flate</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*

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
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*

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
      <td>Kurve</td>
    </tr>
  </tbody>
</table>

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*

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
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
HavElvSperre – rolle: havElvSperre – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
HavInnsjøSperre – rolle: havInnsjøSperre – kardinalitet: 0..*

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
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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
      <td>Kurve</td>
    </tr>
  </tbody>
</table>

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
      <td>Flate</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*

#### ElveElvSperre

hjelpelinje for avgrensning av en elveflate der den renner ut i en annen elv-/kanalflate<br /><br /><br />-- Definition --<br />Construction line for delimitation of river surface where it confluences with another river or canal surface.

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
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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

#### Gravplass

område for gravstøtter, begravelsesplass og kirkegård<br /><br /><br />-- Definition --<br />area for tombstones, graveyard and cemetery

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*

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
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*

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
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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

#### Hyttefelt

område som har høy utnyttelsesgrad med tanke på hytter<br /><br />Merknad:<br />Avgrenser blant annet markslagsregistreringer.<br /><br /><br />-- Definition --<br />area with a high exploitation ratio in terms of cottages. Note: Delimits soil type registrations, etc.

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*

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
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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
      <td>forløp som følger objektets sentrale del<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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

#### ElvBekkKant

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
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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
      <td>forløp som følger objektets sentrale del<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
FerskvannTørrfallkant – rolle: ferskvannTørrfallkant – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*

#### ElvBekk

vannvei for rennende vann<br /><br /><br />-- Definition --<br />Water course for running water.

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del<br /><br />-- Definition --<br />cource follwed by the central part of the object</td>
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
      <td><strong>vannBredde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>grov klassifikasjon av vassdrag etter gjennomsnittelig bredde over lengre strekninge<br /><br />-- Definition --<br />rough classification of watercourses according to average width over longer expanses</td>
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
      <td>- Bredde &lt;&gt; 1-3m<br />- Bredde &lt;&gt; 3-15m<br />- Bredde &lt;&gt; 15-40m</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Assosiasjoner**
HavElvSperre – rolle: havElvSperre – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
ElveElvSperre – rolle: elveElvSperre – kardinalitet: 0..*
InnsjøElvSperre – rolle: innsjøElvSperre – kardinalitet: 0..*
FerskvannTørrfallkant – rolle: ferskvannTørrfallkant – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*

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
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
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

Relasjoner

**Assosiasjoner**
Innsjøkant – rolle: innsjøkant – kardinalitet: 0..*
Dataavgrensning – rolle: dataavgrensning – kardinalitet: 0..*
Kystkontur – rolle: kystkontur – kardinalitet: 0..*
FiktivDelelinje – rolle: fiktivDelelinje – kardinalitet: 0..*
InnsjøkantRegulert – rolle: innsjøkantRegulert – kardinalitet: 0..*
ElvBekkKant – rolle: elvBekkKant – kardinalitet: 0..*
Arealbrukgrense – rolle: arealbrukgrense – kardinalitet: 0..*

### Kodelister

#### «Enumeration» Lufthavntype

**Definisjon:** angivelse av type lufthavn

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
      <td>Fly</td>
      <td>Kode hentet fra AIXM 4.5 (L=Landplane)</td>
      <td></td>
    </tr>
    <tr>
      <td>Helikopter</td>
      <td>Kode hentet fra AIXM 4.5 (H=Helicopter)</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Trafikktype

**Definisjon:** angivelse av type rutetrafikk

Merknad: Benyttes i N50 Kartdata i forhold til luftfart

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
      <td>Internasjonal</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nasjonal</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Annen trafikk</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» IATAKode

**Definisjon:** unik kode for lufthavner.

Merknad1: Ikke alle lufthavner har IATA kode.
Merknad 2: Bare norske lufthavner er tatt med her.

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
      <td>Alta</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Andenes/Andøya</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bardufoss</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bergen/Flesland</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Berlevåg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bodø</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Brønnøysund/Brønnøy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Båtsfjord</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fagernes/Leirin</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Farsund/Lista</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Florø</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Førde/Bringeland</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gol/Klanten</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hamar/Stafsberg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hammerfest</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Harstad/Narvik/Evenes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hasvik</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Haugesund/Karmøy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Honningsvåg/Valan</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kautokeino</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kirkenes/Høybuktmoen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kristiansand/Kjevik</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kristiansund/Kvernberget</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lakselv/Banak</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Leknes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mehamn</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Molde/Årø</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mosjøen/Kjærstad</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Moss/Rygge</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Namsos</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Narvik/Framnes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Notodden</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ny Ålesund/Hamnerabben</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oslo/Gardermoen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Røros</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rørvik/Ryum</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Røst</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sandane/Anda</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sandefjord/Torp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sandnessjøen/Stokka</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skien/Geiteryggen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sogndal/Haukåsen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stavanger/Sola</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stokmarknes/Skagen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stord/Sørstokken</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Svalbard/Longyear</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Svolvær/Helle</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sørkjosen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tromsø/Langnes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Trondheim/Værnes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vadsø</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vardø/Svartnes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Værøy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ørland</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ørsta-Volda/Hovden</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ålesund/Vigra</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» ICAOKode

**Definisjon:** angivelse av lufthavn ved &lt;a href="C:\\wiki\\Kode"&gt;&lt;font color="#0000ff"&gt;&lt;u&gt;kode&lt;/u&gt;&lt;/font&gt;&lt;/a&gt; på fire &lt;a href="C:\\w\\index.php?title=Alfanumerisk&amp;action=edit&amp;redlink=1"&gt;&lt;font color="#0000ff"&gt;&lt;u&gt;alfanumeriske&lt;/u&gt;&lt;/font&gt;&lt;/a&gt; &lt;a href="C:\\wiki\\Tegn"&gt;&lt;font color="#0000ff"&gt;&lt;u&gt;tegn&lt;/u&gt;&lt;/font&gt;&lt;/a&gt;.

Merknad: Den første bokstaven tilordnes etter kontinent og angir et land eller en gruppe land på det samme kontinentet. Den andre bokstaven angir landet og de to siste angir lufthavn.

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
      <td>Albuskjell A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Albuskjell F</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Alta</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Alvheim FPSO</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Andenes/Andøya</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Arendal/Sørlandet Sykehus HF</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Balder A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bardufoss</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Barentsburg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bergen/Flesland</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bergen/Grønneviksøren</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Berlevåg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bjørnøya</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bodø</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Brage A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Brønnøysund/Brønnøy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bømoen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Båtsfjord</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cod</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dokka/Thomlevold</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dombås/Brunshagen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Drammen/Sykehuset Buskerud HF</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Draugen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Draugen FLP</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Draupner</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Edda</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Eggemoen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ekofisk A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ekofisk D</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ekofisk K</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Eldfisk A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Eldfisk B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Elverum/Starmoen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Elverum/Sykehuset Innlandet HF</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Embla</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Engeløy/Grådussan</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fagernes/Leirin</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Farsund/Lista</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fedje Heliport</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Florø</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fritzøe</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Frøya/Flatval</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fyresdal</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Førde/Bringeland</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Førde/Sentralsjukehuset</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Geilo/Dagali</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gjoa</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gol/Klanten</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Grane</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Grimsmoen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gullfaks A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gullfaks A SPM1</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gullfaks A SPM2</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gullfaks B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gullfaks C</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gullknapp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gyda</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hamar/Stafsberg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hammerfest</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Harstad/Narvik/Evenes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hasvik</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hattfjelldal/Vollen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Haugesund/Haugesund Sjukehus HF</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Haugesund/Karmøy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Heidrun A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Heimdal</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hod</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hokksund</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Honningsvåg/Valan</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hopen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hornmoen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Huldra</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hønefoss, Ringerike Sykehus</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Isfjord</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Jan Mayen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Jarlsberg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Jotun A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Jotun B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kautokeino</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kirkenes/Høybuktmoen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kjeller</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kristiansand/Kjevik</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kristiansund/Kvernberget</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kristin Semi</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kvitebjørn</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lakselv/Banak</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Leknes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lesja/Bjorli</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lillehammer/Sykehuset Innlandet HF</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lunde</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lørenskog/Akershus Universitetssykehus</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mehamn</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Molde/Årø</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mosjøen/Kjærstad</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Moss/Rygge</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Namsos</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Namsos, Sykehuset</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Narvik/Framnes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Njord A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Njord B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Norne A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Notodden</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ny Ålesund/Hamnerabben</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oppdal/Fagerhaug</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oseberg A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oseberg C</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oseberg Sør</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oseberg Øst</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oslo, Rikshospitalet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oslo/Gardermoen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oslo/Ullevål Universitetssykehus</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Os/Vaksinen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Petrojarl Varg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Petrojarl 1</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Pyramiden</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rakkestad</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Reinsvoll</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ringebu/Frya</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ringhorne</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rognan</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Røros</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rørvik/Ryum</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Røst</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Salangen/Elvenes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sandane/Anda</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sandefjord/Torp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sandnessjøen/Stokka</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skarv</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skien/Geiteryggen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ski/Søndre Ski gård</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sleipner A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sleipner B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Snorre A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Snorre B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Snåsa/Gronora</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sogndal/Haukåsen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Statfjord A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Statfjord B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Statfjord C</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Statfjord C/SPM</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stavanger/Sola</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stavanger/Stavanger Universitetssykehus</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stokmarknes/Skagen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stord/Sørstokken</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sunndalsøra</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Svalbard/Longyear</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Svea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Svolvær/Helle</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sørkjosen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tambar</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Troll A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Troll B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Troll C</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tromsø/Langnes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Trondheim/Rosten</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Trondheim/St. Olavs Hospital</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Trondheim/Værnes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Trysil/Sæteråsen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tynset</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ula</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vadsø</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Valhall A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Valhall Flank North</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Valhall Flank South</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Valle/Åraksøyene</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vardø/Svartnes</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Varg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Veslefrikk A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Veslefrikk B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Visund A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Værøy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Yme</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ørland</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ørsta-Volda/Hovden</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Østre Æra</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ålesund/Vigra</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ål/Hallingdal Sjukestugu</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Åsgård B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Åsgård C</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Åsgård A</td>
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
      <td>Gon (400 graders deling)</td>
      <td>400 graders deling med positiv retning med sola</td>
      <td></td>
    </tr>
    <tr>
      <td>Grader (360 graders deling)</td>
      <td>360 graders deling med positiv retning med sola</td>
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
      <td>Lokal</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Magnetisk nord</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sant nord</td>
      <td>(default)</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» VannBredde

**Definisjon:** grov klassifikasjon av vassdrag etter gjennomsnittelig bredde over lengre strekninger


-- Definition - -
Rough classification of river system according to average width over longer sections.

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
      <td>Bredde &lt;&gt; 1-3m</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bredde &lt;&gt; 3-15m</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bredde &lt;&gt; 15-40m</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
