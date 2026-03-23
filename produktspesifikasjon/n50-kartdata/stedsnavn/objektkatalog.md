### Datamodell

<a href="stedsnavn_feature_catalogue.png" title="Klikk for stor visning"><img src="stedsnavn_feature_catalogue.png" alt="Datamodell Stedsnavn" style="max-width: 100%; height: auto;" /></a>

#### Skrivemåte

ulike skrivemåter av navneenheten, ikke forskjellige navn

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
      <td>sted som objektet eksisterer på<br /><br />merknad 1: Posisjon .PUNKT må mappes til .TEKST i henhold til SOSI 4.5<br />merknad 2: .TEKST angis med 3 koordinater. Første er objektkoordinat, andre er plasseringskoordinat og tredje er retningskoordinat</td>
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
      <td><strong>ssrId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>koblingsnøkkel til navneenheten i SSR (Sentralt StedsnavnsRegister)</td>
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
      <td><strong>navnetype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver hvilke type terrengdetalj stedsnavnet representerer</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Navnetype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Adm. by – Alle steder hvor kommunen har vedtatt bystatus<br />- Adm. bydel – (Offisielt navn på bydelsforvaltningen). Se også Bydel  132.<br />- Adm. tettsted – Statistisk sentralbyrås spesifikasjon.<br />- Adressenavn – Omfatter et område, ev. som supplement til gate-/veiadresse. (Kommunalt adresseområde)<br />- Allmenning – Område hvor rettighetene er regulert. (Alle typer. Noter i merknadsfelt)<br />- Ankringsplass – F.eks. opplagsplass for store båter/skip<br />- Annen adm. Inndeling – Landsdel, havnedistrikt, politidistrikt bispedømme, prestegjeld, skolekrets, valgkrets, postområde, etc. (Noter type i merknadsfelt)<br />- Annen bygning for religiøse aktiviteter – Synagoge, moske,  frikirke, menighetshus, kloster, gravkapell,    bårehus, krematorium. Noter i merknadsfelt hvilken type + dato for merknaden.<br />- Annen kulturdetalj – Alle typer kulturdetaljer f.eks. lekeplass, tårn, fiskeplass, etc. Noter forklaring med dato i merknadsfeltet<br />- Badeplass – Offentlige og private badeplasser<br />- Bakke – Skråning<br />- Bakke i sjø – Skrånende sjøbunn<br />- Banke – Flatt, større undervannsområde<br />- Banke i sjø – Flatt, større undervannsområde<br />- Barnehage – Offentlig eller privat barnehage<br />- Bekk – Rennende vann i naturlig vannvei. Generelt smalere enn 3 meter<br />- Bergverk (underjord./dagbrudd) – Gruve, skjerp<br />- Boligblokk – Stort boligbygg med 2 eller flere etasjer hvor det er 5 eller flere boligenheter<br />- Boligfelt – Regulert boligområde<br />- Bomstasjon – Større bomanlegg på offentlig veg<br />- Borettslag – Bofellesskap, vanligvis blokkbebyggelse<br />- Botn – Dalende<br />- Bru – Både for veg og jernbane. Angi ett punkt i hver ende for store bruer og ett midt på for små bruer.<br />- Bruk (gardsbruk) – Landbruksbebyggelse som er eller har vært knyttet til jord- og/eller skogbruksdrift. Bruksnamn, namn på eigedom med eitt eller fleire bruksnummer eller festenummer under eit gardsnummer. Punktet ligger normalt på våningshuset (hvis dette finnes).<br />- Brygge – Mindre, fast bryggeanlegg<br />- Busstopp – Stoppested for rutegående vegtrafikk<br />- By – Tettsted med handels- og servicefunksjoner. Bymessig med mer eller mindre sammenhengende, kvartalsbebyggelse (bykjerne). Bygninger med 2 eller flere etasjer. (Se også Adm. by 268).<br />- Bydel – Kulturmessig del av by. F.eks. Gamlebyen, Vålerenga, Posebyen, Nordnes, Lade, Tromsdalen, Fagernes. (Se også Adm. bydel  269)<br />- Bygdelag (bygd) – Stort uregulert gårdsbruk- og boligområde<br />- Bygg for jordbruk, fiske og fangst – Bu, naust, uthus, fjøs, gamme<br />- Båe – Stein under vannflaten<br />- Båe i sjø – Stein under  vannflaten.<br />- Båke – Offisiell og privat båke langs kysten og i innlandet, fast.<br />- Campingplass – Alle typer både for campinghytter, campingvogner og telt<br />- Dal – Mellomstor eller liten dal<br />- Dalføre – Stor dal: Gudbrandsdalen, Namdalen, Setesdal, Valdres<br />- Dam – Store reguleringsdammer og små fløtningsdammer<br />- Del av innsjø – Mindre deler av store innsjøer. F.eks. Steinsfjorden i Tyrifjorden<br />- Dyp (havdyp) – Område mer enn 200-300 meter under havflaten<br />- Egg – Undersjøisk kant mot havdyp<br />- Eid – Lavt/smalt parti mellom to vannkanter, elver eller vann<br />- Eid i sjø – Lavt parti i terrenget mellom to sjøkanter<br />- Eiendommer – Matrikulert eiendom<br />- Elv – Rennende vann i naturlig vannvei. Generelt bredere enn 3 meter<br />- Elvemel – Bratt sand- eller grus- skråning langs en elv (eller et vann)<br />- Enebolig/mindre boligbygg (villa) – Enebolig eller tomannsbolig  Hus for fast bosetting, utenom våningshus, jf. 108. (Vanligvis dss. bruks­navn.)<br />- Eng – Kultivert slåtte/gressmark<br />- Fabrikk – Større industrivirksomhet<br />- Farled/Skipslei – Normal strekning for skip f.eks. Trondheimsleia<br />- Fengsel – Fengsel, arbeidskoloni<br />- Ferjekai – Punktet legges på ferjelemmen på kaia for vegtrafikken<br />- Ferjestrekning – Eksisterende ferjesamband som inngår i områdets samferdselsnett<br />- Fiskeoppdrettsanlegg – På land, i sjø og i ferskvann<br />- Fiskeplass – Fiskested, fiskemed i sjø.<br />- Fjell – Stort fjell<br />- Fjellheis – Gondolbane.<br />- Fjellkant (aksel) – Skulder, nese, bryn<br />- Fjellområde – Stort  fjellområde: Rondane, Saltfjellet, Lyseheiane<br />- Fjellside – Vanligvis åpent skrånende terreng i fjellet<br />- Fjord – Arm av havet inn i fastlandet<br />- Fjordmunning – Område ytterst i en fjord<br />- Flyplass – Landingsplass for rutegående flytrafikk og regulert privat flygning<br />- Fløtningsannlegg – Kunstig fløtningsanlegg<br />- Fonn – Liten snø- eller isflate<br />- Fornøyelsespark – (Store, regulerte anlegg)<br />- Forretningsbygg – Hus for kontor- og servicevirksomhet<br />- Forsamlingshus/Kulturhus – Teater, kino, samf.hus, grendehus, etc.<br />- Foss – Vann i tilnærmet fritt fall<br />- Fritidsbolig (hytte, sommerhus) – Hus som ikke er ment for fast bosetting. (Vanligvis dass. bruks­navn.)<br />- Fylke – (Offisielt navn)<br />- Fyllplass – Plass for deponering av masse<br />- Fyr(Fyrstasjon) – Offisielt fyr og fyrstasjon langs kysten.<br />- Gammel bosettingsplass – Nedlagt bruk, seter, boplass, gamme. MRK !! Hus borte eller kun ruin.<br />- Garasje/hangarbygg – Parkeringshus/ trikkestall/ bussgarasje/flyhangar/ lokomotivstall<br />- Gard – Landbruksbebyggelse som er eller har vært knyttet til jord- og/eller skogbruksdrift. Gardsnamn, namnet på heile det gardsområdet som eitt eller fleire gardsnummer er knytte til. Punktet ligger normalt på våningshuset (hvis dette finnes) på et sentralt pla<br />- Gjerde – Steingjerde, tregjerde etc.<br />- Gravplass – Alle typer gravlunder, gravplasser.<br />- Grend – Mindre uregulert gårdsbruk-, seterfelt- og boligområde<br />- Grensemerke – Off. godkjent grensemerke (generelt): Varde, tre, stein, bolt, kors etc.<br />- Grind – Port i gjerde<br />- Grotte – Naturlig fjellgrotte f.eks. Grønnligrotta (Rana)<br />- Grunne – Lite område under vann<br />- Grunne i sjø – Forhøyning på bunnen som skiller seg vesentlig fra høyden på bunnen omkring<br />- Grunnkrets – Se også 253 annen adm. inndeling<br />- Gruppe av tjern – Flere små vann<br />- Gruppe av vann – Flere middels store vann<br />- Grustak/Steinbrudd – Uttaksplass, område, drevet i dagen for  sand, grus, pukk, skifer eller stein<br />- Grøft – Rennende vann der forløpet er menneskeskapt  f.eks. dreneringsgrøfter i myr<br />- Halvøy – Større nes i ferskvann med smalt eide mot fastland<br />- Halvøy i sjø – Større nes med smalt eid mot fastland<br />- Haug – Liten markant terrengform<br />- Havn – Sted der fartøy  kan laste, losse eller søke ly for vær og sjø.<br />- Havnehage – Inngjerdet beitemark<br />- Havområde – Store områder: Barentshavet Nordsjøen, Atlanterhavet<br />- Hei – Berglendt, høyere beliggende område med beitemark<br />- Heller – Steinhule, steinsatt overnattingssted<br />- Helseinstitusjon – Aldershjem, rekreasjonshjem og lignende<br />- Holdeplass – Ubetjent stoppested for jernbane og trikk<br />- Holme – Liten øy i ferskvann<br />- Holme i sjø – Liten øy/skjær i sjø<br />- Holmegruppe i sjø – Flere små skjær i sjø<br />- Hotell – Offentlig godkjent overnattingssted<br />- Hylle (hjell) – Flatt område i fjellside<br />- Hyttefelt – Offentlig eller privat  hyttefelt. Område som har høy utnyttelsesgrad med tanke på hytter.<br />- Høl – Dyp elvebunn under foss eller ved ende av stryk<br />- Høyde – Mindre terrengform som ikke vurderes som fjell<br />- Idrettsanlegg – (Alle typer utendørsanl. Noter type i merknadsfelt, f.eks. ridebane, fotballbane)<br />- Idrettshall – Alle typer innendørsanlegg Ishall/svømmehall idrettshall.<br />- Industriområde – Større sammenhengende område benyttet for industriformål<br />- Innsjø – Stort vann: Altevatnet, Femunden, Mjøsa, Nisser<br />- Isbre – Større sammenhengende snø- eller is område som ikke smelter i løpet av sommeren. F.eks. Svartisen eller Folgefonna<br />- Jernbanestrekning – Lang  jernbanestrekning. F.eks.  Ofotbanen, Bergensbanen<br />- Jorde – Kultivert dyrknings- mark<br />- Juv – Kløftlignende dal, canyon<br />- Kabel – Alle typer kabler i både sjø og ferskvann.<br />- Kai – Større, fast bryggeanlegg<br />- Kanal – Utgravd vannveg  i sjø og ferskvann<br />- Kilde – Oppkomme, olle, vannkilde. Kildeutspring. Benyttes for å angi stedet hvor grunnvannet kommer i dagen<br />- Kirke – Kirke / Kapell / Arbeidskirke knyttet til Den norske kirke<br />- Klakk – Spiss grunne. (Trøndersk/Nordnorsk uttrykk)<br />- Klopp – Gangbru over sjø og ferskvann<br />- Kommune – (Offisielt navn)<br />- Kraftgate (Rørgate) – Store tilførselsrør for kraftanlegg<br />- Kraftledning – Vanligvis store overføringsledninger<br />- Kraftstasjon – Alle størrelser for energi produksjon, (el. og varme)<br />- Kryss (Veg/Gate) – (For alle type veger)<br />- Landingsstripe – Landingsplass for privat flygning<br />- Landskapsområde – Stort landskapsområde:  Dalane, Jæren, Romerike, Grenland, Salten, Varanger<br />- Lanterne – Offisiell og privat lanterne langs kysten og i innlandet, fast<br />- Li – Vanligvis skogkledd skrånende terreng<br />- Lone – Nesten stillestående vik i elv eller bekk<br />- Lykt (Fyrlykt) – Offisiell og privat lykt/fyrlykt langs kysten og i innlandet.<br />- Lysbøye – Offisiell og privat lysbøye langs kysten og i innlandet, flytende<br />- Melkeplass – Seterplass uten hus. Vanligvis i bratte områder på Vestlandet<br />- Militært bygg/Anlegg – Militærleir, militært bygg<br />- Mo – Flatt område, vanligvis skogkledd<br />- Molo – Fast byggverk, utstikkende voll i sjøen<br />- Museum/ Galleri/Bibliotek – Alle typer museum,  galleri og bibliotek<br />- Myr – Alle typer fra gressmyr til våt moldjord<br />- Nasjon – Selvstendig land (Offisielt navn)<br />- Nes – Landområde stikkende ut i ferskvann<br />- Nes i sjø – Landområde stikkende ut i saltvann<br />- Nes ved elver – Landet mellom to møtende elver. Vanligvis kun brukt i samiske områder. Stedsnavnets skrivemåte skal IKKE avgjøre om navnet skal gis denne koden, men KUN lokalitetens størrelse eller fasong.<br />- Offersted – Samisk, norsk eller finsk offersted<br />- Oljeinstallasjon (Sjø) – Stasjonære oljeinstallasjoner (faste og flytende)<br />- Os – Innløp eller utløp av elv eller bekk i innsjø/vann/tjern eller sjø (saltvann)<br />- Overett – Offisiell og privat. To stenger med/uten lys overett langs kysten og i innlandet, faste.<br />- Park – Kultivert område med eller uten trær. Kolonihage (i by eller tettbygd strøk)<br />- Parkeringsplass – Offentlig og privat<br />- Pensjonat – Offentlig godkjent overnattingssted<br />- Plass/torg – (I tettsted eller by)<br />- Poststed (Postkontor) – Offisielt poststed<br />- Pytt – Liten dam, myrpytt<br />- Rasteplass – Rasteplass med ansvarlig Statens vegvesen eller annen offentlig myndighet<br />- Renne – Undersjøisk dal<br />- Rygg – Langstrakt terrengform<br />- Rygg i sjø – Undersjøisk ås<br />- Rørledning – Alle typer rørledninger: Olje, gass, vann, etc.<br />- Rådhus (komm, fylke, stat) – Adm. senteret (-huset) i adm. enheten.<br />- Sand – Sand-grusområde over vannkontur/kystkontur. Morenemateriale<br />- Senkning – Flat forsenkning, dalsenkning<br />- Serveringssted – Serveringssted utenfor tettbygd område<br />- Seter (sel, støl) – Enklere landbruksbe­byggelse. Kan ha periodisk fast bosetting, vanligvis sommerstid.<br />- Setervoll – Ryddet, gressbevokst område på ei seter, med   eller uten hus<br />- Severdighet – Noter forklaring i merknadsfeltet, f.eks. minnesmerke<br />- Sjøstykke – Del av sjøen, vanligvis innaskjærs eller i kystnære farvann. F.eks. Folda, Hustadvika<br />- Skar – Markant senkning i fjell<br />- Skiheis – Skitrekk og stolheis i skianlegg.<br />- Skjær – Stein i vannflaten<br />- Skjær i sjø – Stein i vannflaten.<br />- Skog – Alle typer fra stor barskog til vierkratt i Finnmark<br />- Skogområde – Stort skogområde: Nordmarka, Bymarka, Finnskogen<br />- Skole – Offentlig og privat skole<br />- Skred – Rasområde: Alle typer materiale  (f.eks. stein, jord, sand, leire, o.l.)<br />- Skytebane – Pistol- eller geværbane (o.l. våpen)<br />- Skytefelt – Militære skytefelt.<br />- Slalåm- og utforbakke – Alle typer regulerte alpinanlegg.<br />- Slette – Åpent, flatt, ikke skogbevokst område<br />- Sluse – Kunstig løfteanretning for båter i vassdrag<br />- Småbåthavn – Regulerte havneanlegg for småbåter<br />- Sogn – Kirkesogn Knyttet til Den norske kirke<br />- Soneinndeling til havs – Fiskerisone, havrettssone, etc. (Noter type i merknadsfelt)<br />- Stake – Offisiell og privat stake langs kysten og i innlandet, flytende<br />- Stang – Offisiell og privat jernstang langs kysten og i innlandet, fast<br />- Stasjon – Betjent stoppested for jernbane og trikk<br />- Stein – F.eks. flyttstein i fjellet<br />- Sti – Stistrekning, sleper (gamle drifteveger), reindriftsveger<br />- Strand – Sand-, grus- eller steindekket område i vannkanten<br />- Strand i sjø – Sand-, grus- eller steindekket område i sjøkanten<br />- Stryk – Parti der vannet går i stryk og skiller seg tydelig fra resten av elv eller bekk<br />- Stup – Loddrett eller svært bratt, fallende terreng<br />- Stø – Båtstø, båtplass i  vannkanten uten naust<br />- Sund – Innsnevret område i vann eller vassdrag<br />- Sund i sjø – Innsnevret område mellom øyer eller fastland<br />- Sva – Bart fjell-/steinparti<br />- Sykehus – Offentlig og privat sykehus<br />- Søkk – Mindre markant, begrenset fordypning<br />- Søkk i sjø – Stor eller liten grop på sjøbunnen<br />- Taubane – Uten persontrafikk. Se også 193<br />- Terrengdetalj – Alle typer små naturdetaljer. f.eks. sprekker, hulveier, sand-/stein-/grusflater, etc.<br />- Tettbebyggelse – Mindre bebygd område uten sentrumskarakter f.eks. boligområde<br />- Tettsted – Mindre bymessig bebygd område av sentrumskarakter<br />- Tettsteddel – Kulturmessig del av tettsted. Se også navnetype 101.<br />- Tjern – Lite vann<br />- Topp (fjelltopp/tind) – Øverste fjelltopp<br />- Torvtak – Sted for uttak av myrtorv / brenntorv / veksttorv.<br />- Traktorveg – Driftsveger for kjøretøyer hvor vegen ikke kan kjøres med vanlig bil.<br />- Tunnel – Vanlig tunnel, rasoverbygg, undergang. Både gangveg, veg og jernbane. Angi ett punkt i hver ende for lange og ett punkt midt på for korte tunneler<br />- Turisthytte – Overnattingssted<br />- TV/Radio-mast – TV/Radio ?tårn. Alle typer bakkebasert telekommunikasjon<br />- Tømmerrenne – Kunstig tømmeranlegg<br />- Tømmervelte – Midlertidig lagringsplass for tømmer<br />- Universitet/høgskole – Offentlig og privat høyskole og universitet<br />- Ur – Steinområde, steinrøys<br />- Utmark – Ikke inngjerdet beitemark<br />- Utsiktspunkt – Både i tårn og på bakken f.eks. Kongens utsikt<br />- Utstikker – Flytende bryggeanlegg<br />- Vad – Vassested i elv, bekk vann eller sjø.<br />- Vaktstasjon/Beredsskapsbygning – Bygning for Politi/Brann/Los/Toll/Ambulanse/Fly- og skipsovervåkning<br />- Vann – Middels stort vann<br />- Vanndetalj – Alle typer : Noter forklaring i merknadsfeltet<br />- Varde – F.eks. merkerøys, steinrøys. Langs kysten og i innlandet<br />- Veg (Gate) – Formelle veg/gatenavn ellers kode 240<br />- Vegbom – Mindre bomanlegg på privat veg<br />- Verksted – Mindre industrivirksomhet<br />- Verneområder – (Alle typer både sjø og land. Noter type f.eks. Nasjonalpark i merknadsfelt)<br />- Vidde – Høyere liggende større område uten skog med lave terrengvariasjoner innenfor området. F.eks. Valdresflyi, Hardangervidda, Finnmarksvidda, Laksefjordvidda<br />- Vik – Kil, bukt i vann eller vassdrag.<br />- Vik i sjø – Kil, bukt<br />- Våg – Fjordarm, større vik<br />- Øy – Tørt landområde i ferskvann atskilt fra fastlandet<br />- Øy i sjø – Tørt landområde i saltvann atskilt fra fastlandet<br />- Øygruppe – To eller flere øyer i ferskvann<br />- Øygruppe i sjø – To eller flere øyer i saltvann f.eks. Hvaler og Lofoten<br />- Øyr – Sand-grusområde i elvemunning, elvedelta både mot innsjø/vann og saltvann<br />- Ås – Langstrakt, vanligvis skogkledd høydedrag.</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>presentasjonskode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>koplingsnøkkel mot presentasjonsinformasjon.<br />Merknad: Kan brukes for både tekst og symbol</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Presentasjonskode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>stedsnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navneenhetens skrivemåte uten forkortninger</td>
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
      <td><strong>tekstReferansepunkt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Tekstens referansepunkt er det stedet på teksten  hvor en tekstplassering refererer seg til. Hvis teksten består av flere linjer er det fremdeles referert ut fra første del av strengen (dvs i første linje).<br />Merknad: Hvis ikke andre verdier er oppgitt, er default plassering av TREF som følger:<br />TRNORD = 1, TRØST = 0, dvs nedre venstre punkt til første bokstav.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>tekstReferansepunkt.tekstReferansePunktNord</strong></td>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Bunnlinje<br />- Midtlinje<br />- Øvre kant<br />- Grunnlinje</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>tekstReferansepunkt.tekstReferansePunktØst</strong></td>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Venstre kant<br />- Midt i<br />- Høyre kant</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>generellTekststreng</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navneenhetens skrivemåte</td>
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
      <td><strong>sperring</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sperring regulerer avstanden mellom bokstavene i teksten. Dette gjøres ved forholdstall relatert til størrelsen på største bokstavblokk</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Sperring</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Liten sperring – Liten sperring = 1 drittel, dvs 1/3 av "største bokstavblokk" mellom hver bokstav.<br />- Middels sperring – Middels sperring = halvgefirt, dvs 1/2 av "største bokstavblokk" mellom hver bokstav.<br />- Stor sperring – Stor sperring = 1 gefirt, dvs 1 (største) "bokstavblokk" mellom hver bokstav.</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>frisperring</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>skriftlengden i mm på presentasjonsmedium</td>
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

### Kodelister

#### «Enumeration» Navnetype

**Definisjon:** navnetype er en underinndeling av TEMA-koden, brukt for mer detaljert koding. Denne forteller hva slags begrep navneheten står til
Merknad: Kun typer som er beskrevet i tabellen kan benyttes. Listen er delt inn i hovedgrupper og undergrupper.

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
      <td>Adm. by</td>
      <td>Alle steder hvor kommunen har vedtatt bystatus</td>
      <td></td>
    </tr>
    <tr>
      <td>Adm. bydel</td>
      <td>(Offisielt navn på bydelsforvaltningen). Se også Bydel  132.</td>
      <td></td>
    </tr>
    <tr>
      <td>Adm. tettsted</td>
      <td>Statistisk sentralbyrås spesifikasjon.</td>
      <td></td>
    </tr>
    <tr>
      <td>Adressenavn</td>
      <td>Omfatter et område, ev. som supplement til gate-/veiadresse. (Kommunalt adresseområde)</td>
      <td></td>
    </tr>
    <tr>
      <td>Allmenning</td>
      <td>Område hvor rettighetene er regulert. (Alle typer. Noter i merknadsfelt)</td>
      <td></td>
    </tr>
    <tr>
      <td>Ankringsplass</td>
      <td>F.eks. opplagsplass for store båter/skip</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen adm. Inndeling</td>
      <td>Landsdel, havnedistrikt, politidistrikt bispedømme, prestegjeld, skolekrets, valgkrets, postområde, etc. (Noter type i merknadsfelt)</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen bygning for religiøse aktiviteter</td>
      <td>Synagoge, moske,  frikirke, menighetshus, kloster, gravkapell,    bårehus, krematorium. Noter i merknadsfelt hvilken type + dato for merknaden.</td>
      <td></td>
    </tr>
    <tr>
      <td>Annen kulturdetalj</td>
      <td>Alle typer kulturdetaljer f.eks. lekeplass, tårn, fiskeplass, etc. Noter forklaring med dato i merknadsfeltet</td>
      <td></td>
    </tr>
    <tr>
      <td>Badeplass</td>
      <td>Offentlige og private badeplasser</td>
      <td></td>
    </tr>
    <tr>
      <td>Bakke</td>
      <td>Skråning</td>
      <td></td>
    </tr>
    <tr>
      <td>Bakke i sjø</td>
      <td>Skrånende sjøbunn</td>
      <td></td>
    </tr>
    <tr>
      <td>Banke</td>
      <td>Flatt, større undervannsområde</td>
      <td></td>
    </tr>
    <tr>
      <td>Banke i sjø</td>
      <td>Flatt, større undervannsområde</td>
      <td></td>
    </tr>
    <tr>
      <td>Barnehage</td>
      <td>Offentlig eller privat barnehage</td>
      <td></td>
    </tr>
    <tr>
      <td>Bekk</td>
      <td>Rennende vann i naturlig vannvei. Generelt smalere enn 3 meter</td>
      <td></td>
    </tr>
    <tr>
      <td>Bergverk (underjord./dagbrudd)</td>
      <td>Gruve, skjerp</td>
      <td></td>
    </tr>
    <tr>
      <td>Boligblokk</td>
      <td>Stort boligbygg med 2 eller flere etasjer hvor det er 5 eller flere boligenheter</td>
      <td></td>
    </tr>
    <tr>
      <td>Boligfelt</td>
      <td>Regulert boligområde</td>
      <td></td>
    </tr>
    <tr>
      <td>Bomstasjon</td>
      <td>Større bomanlegg på offentlig veg</td>
      <td></td>
    </tr>
    <tr>
      <td>Borettslag</td>
      <td>Bofellesskap, vanligvis blokkbebyggelse</td>
      <td></td>
    </tr>
    <tr>
      <td>Botn</td>
      <td>Dalende</td>
      <td></td>
    </tr>
    <tr>
      <td>Bru</td>
      <td>Både for veg og jernbane. Angi ett punkt i hver ende for store bruer og ett midt på for små bruer.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bruk (gardsbruk)</td>
      <td>Landbruksbebyggelse som er eller har vært knyttet til jord- og/eller skogbruksdrift. Bruksnamn, namn på eigedom med eitt eller fleire bruksnummer eller festenummer under eit gardsnummer. Punktet ligger normalt på våningshuset (hvis dette finnes).</td>
      <td></td>
    </tr>
    <tr>
      <td>Brygge</td>
      <td>Mindre, fast bryggeanlegg</td>
      <td></td>
    </tr>
    <tr>
      <td>Busstopp</td>
      <td>Stoppested for rutegående vegtrafikk</td>
      <td></td>
    </tr>
    <tr>
      <td>By</td>
      <td>Tettsted med handels- og servicefunksjoner. Bymessig med mer eller mindre sammenhengende, kvartalsbebyggelse (bykjerne). Bygninger med 2 eller flere etasjer. (Se også Adm. by 268).</td>
      <td></td>
    </tr>
    <tr>
      <td>Bydel</td>
      <td>Kulturmessig del av by. F.eks. Gamlebyen, Vålerenga, Posebyen, Nordnes, Lade, Tromsdalen, Fagernes. (Se også Adm. bydel  269)</td>
      <td></td>
    </tr>
    <tr>
      <td>Bygdelag (bygd)</td>
      <td>Stort uregulert gårdsbruk- og boligområde</td>
      <td></td>
    </tr>
    <tr>
      <td>Bygg for jordbruk, fiske og fangst</td>
      <td>Bu, naust, uthus, fjøs, gamme</td>
      <td></td>
    </tr>
    <tr>
      <td>Båe</td>
      <td>Stein under vannflaten</td>
      <td></td>
    </tr>
    <tr>
      <td>Båe i sjø</td>
      <td>Stein under  vannflaten.</td>
      <td></td>
    </tr>
    <tr>
      <td>Båke</td>
      <td>Offisiell og privat båke langs kysten og i innlandet, fast.</td>
      <td></td>
    </tr>
    <tr>
      <td>Campingplass</td>
      <td>Alle typer både for campinghytter, campingvogner og telt</td>
      <td></td>
    </tr>
    <tr>
      <td>Dal</td>
      <td>Mellomstor eller liten dal</td>
      <td></td>
    </tr>
    <tr>
      <td>Dalføre</td>
      <td>Stor dal: Gudbrandsdalen, Namdalen, Setesdal, Valdres</td>
      <td></td>
    </tr>
    <tr>
      <td>Dam</td>
      <td>Store reguleringsdammer og små fløtningsdammer</td>
      <td></td>
    </tr>
    <tr>
      <td>Del av innsjø</td>
      <td>Mindre deler av store innsjøer. F.eks. Steinsfjorden i Tyrifjorden</td>
      <td></td>
    </tr>
    <tr>
      <td>Dyp (havdyp)</td>
      <td>Område mer enn 200-300 meter under havflaten</td>
      <td></td>
    </tr>
    <tr>
      <td>Egg</td>
      <td>Undersjøisk kant mot havdyp</td>
      <td></td>
    </tr>
    <tr>
      <td>Eid</td>
      <td>Lavt/smalt parti mellom to vannkanter, elver eller vann</td>
      <td></td>
    </tr>
    <tr>
      <td>Eid i sjø</td>
      <td>Lavt parti i terrenget mellom to sjøkanter</td>
      <td></td>
    </tr>
    <tr>
      <td>Eiendommer</td>
      <td>Matrikulert eiendom</td>
      <td></td>
    </tr>
    <tr>
      <td>Elv</td>
      <td>Rennende vann i naturlig vannvei. Generelt bredere enn 3 meter</td>
      <td></td>
    </tr>
    <tr>
      <td>Elvemel</td>
      <td>Bratt sand- eller grus- skråning langs en elv (eller et vann)</td>
      <td></td>
    </tr>
    <tr>
      <td>Enebolig/mindre boligbygg (villa)</td>
      <td>Enebolig eller tomannsbolig  Hus for fast bosetting, utenom våningshus, jf. 108. (Vanligvis dss. bruks­navn.)</td>
      <td></td>
    </tr>
    <tr>
      <td>Eng</td>
      <td>Kultivert slåtte/gressmark</td>
      <td></td>
    </tr>
    <tr>
      <td>Fabrikk</td>
      <td>Større industrivirksomhet</td>
      <td></td>
    </tr>
    <tr>
      <td>Farled/Skipslei</td>
      <td>Normal strekning for skip f.eks. Trondheimsleia</td>
      <td></td>
    </tr>
    <tr>
      <td>Fengsel</td>
      <td>Fengsel, arbeidskoloni</td>
      <td></td>
    </tr>
    <tr>
      <td>Ferjekai</td>
      <td>Punktet legges på ferjelemmen på kaia for vegtrafikken</td>
      <td></td>
    </tr>
    <tr>
      <td>Ferjestrekning</td>
      <td>Eksisterende ferjesamband som inngår i områdets samferdselsnett</td>
      <td></td>
    </tr>
    <tr>
      <td>Fiskeoppdrettsanlegg</td>
      <td>På land, i sjø og i ferskvann</td>
      <td></td>
    </tr>
    <tr>
      <td>Fiskeplass</td>
      <td>Fiskested, fiskemed i sjø.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjell</td>
      <td>Stort fjell</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjellheis</td>
      <td>Gondolbane.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjellkant (aksel)</td>
      <td>Skulder, nese, bryn</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjellområde</td>
      <td>Stort  fjellområde: Rondane, Saltfjellet, Lyseheiane</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjellside</td>
      <td>Vanligvis åpent skrånende terreng i fjellet</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjord</td>
      <td>Arm av havet inn i fastlandet</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjordmunning</td>
      <td>Område ytterst i en fjord</td>
      <td></td>
    </tr>
    <tr>
      <td>Flyplass</td>
      <td>Landingsplass for rutegående flytrafikk og regulert privat flygning</td>
      <td></td>
    </tr>
    <tr>
      <td>Fløtningsannlegg</td>
      <td>Kunstig fløtningsanlegg</td>
      <td></td>
    </tr>
    <tr>
      <td>Fonn</td>
      <td>Liten snø- eller isflate</td>
      <td></td>
    </tr>
    <tr>
      <td>Fornøyelsespark</td>
      <td>(Store, regulerte anlegg)</td>
      <td></td>
    </tr>
    <tr>
      <td>Forretningsbygg</td>
      <td>Hus for kontor- og servicevirksomhet</td>
      <td></td>
    </tr>
    <tr>
      <td>Forsamlingshus/Kulturhus</td>
      <td>Teater, kino, samf.hus, grendehus, etc.</td>
      <td></td>
    </tr>
    <tr>
      <td>Foss</td>
      <td>Vann i tilnærmet fritt fall</td>
      <td></td>
    </tr>
    <tr>
      <td>Fritidsbolig (hytte, sommerhus)</td>
      <td>Hus som ikke er ment for fast bosetting. (Vanligvis dass. bruks­navn.)</td>
      <td></td>
    </tr>
    <tr>
      <td>Fylke</td>
      <td>(Offisielt navn)</td>
      <td></td>
    </tr>
    <tr>
      <td>Fyllplass</td>
      <td>Plass for deponering av masse</td>
      <td></td>
    </tr>
    <tr>
      <td>Fyr(Fyrstasjon)</td>
      <td>Offisielt fyr og fyrstasjon langs kysten.</td>
      <td></td>
    </tr>
    <tr>
      <td>Gammel bosettingsplass</td>
      <td>Nedlagt bruk, seter, boplass, gamme. MRK !! Hus borte eller kun ruin.</td>
      <td></td>
    </tr>
    <tr>
      <td>Garasje/hangarbygg</td>
      <td>Parkeringshus/ trikkestall/ bussgarasje/flyhangar/ lokomotivstall</td>
      <td></td>
    </tr>
    <tr>
      <td>Gard</td>
      <td>Landbruksbebyggelse som er eller har vært knyttet til jord- og/eller skogbruksdrift. Gardsnamn, namnet på heile det gardsområdet som eitt eller fleire gardsnummer er knytte til. Punktet ligger normalt på våningshuset (hvis dette finnes) på et sentralt pla</td>
      <td></td>
    </tr>
    <tr>
      <td>Gjerde</td>
      <td>Steingjerde, tregjerde etc.</td>
      <td></td>
    </tr>
    <tr>
      <td>Gravplass</td>
      <td>Alle typer gravlunder, gravplasser.</td>
      <td></td>
    </tr>
    <tr>
      <td>Grend</td>
      <td>Mindre uregulert gårdsbruk-, seterfelt- og boligområde</td>
      <td></td>
    </tr>
    <tr>
      <td>Grensemerke</td>
      <td>Off. godkjent grensemerke (generelt): Varde, tre, stein, bolt, kors etc.</td>
      <td></td>
    </tr>
    <tr>
      <td>Grind</td>
      <td>Port i gjerde</td>
      <td></td>
    </tr>
    <tr>
      <td>Grotte</td>
      <td>Naturlig fjellgrotte f.eks. Grønnligrotta (Rana)</td>
      <td></td>
    </tr>
    <tr>
      <td>Grunne</td>
      <td>Lite område under vann</td>
      <td></td>
    </tr>
    <tr>
      <td>Grunne i sjø</td>
      <td>Forhøyning på bunnen som skiller seg vesentlig fra høyden på bunnen omkring</td>
      <td></td>
    </tr>
    <tr>
      <td>Grunnkrets</td>
      <td>Se også 253 annen adm. inndeling</td>
      <td></td>
    </tr>
    <tr>
      <td>Gruppe av tjern</td>
      <td>Flere små vann</td>
      <td></td>
    </tr>
    <tr>
      <td>Gruppe av vann</td>
      <td>Flere middels store vann</td>
      <td></td>
    </tr>
    <tr>
      <td>Grustak/Steinbrudd</td>
      <td>Uttaksplass, område, drevet i dagen for  sand, grus, pukk, skifer eller stein</td>
      <td></td>
    </tr>
    <tr>
      <td>Grøft</td>
      <td>Rennende vann der forløpet er menneskeskapt  f.eks. dreneringsgrøfter i myr</td>
      <td></td>
    </tr>
    <tr>
      <td>Halvøy</td>
      <td>Større nes i ferskvann med smalt eide mot fastland</td>
      <td></td>
    </tr>
    <tr>
      <td>Halvøy i sjø</td>
      <td>Større nes med smalt eid mot fastland</td>
      <td></td>
    </tr>
    <tr>
      <td>Haug</td>
      <td>Liten markant terrengform</td>
      <td></td>
    </tr>
    <tr>
      <td>Havn</td>
      <td>Sted der fartøy  kan laste, losse eller søke ly for vær og sjø.</td>
      <td></td>
    </tr>
    <tr>
      <td>Havnehage</td>
      <td>Inngjerdet beitemark</td>
      <td></td>
    </tr>
    <tr>
      <td>Havområde</td>
      <td>Store områder: Barentshavet Nordsjøen, Atlanterhavet</td>
      <td></td>
    </tr>
    <tr>
      <td>Hei</td>
      <td>Berglendt, høyere beliggende område med beitemark</td>
      <td></td>
    </tr>
    <tr>
      <td>Heller</td>
      <td>Steinhule, steinsatt overnattingssted</td>
      <td></td>
    </tr>
    <tr>
      <td>Helseinstitusjon</td>
      <td>Aldershjem, rekreasjonshjem og lignende</td>
      <td></td>
    </tr>
    <tr>
      <td>Holdeplass</td>
      <td>Ubetjent stoppested for jernbane og trikk</td>
      <td></td>
    </tr>
    <tr>
      <td>Holme</td>
      <td>Liten øy i ferskvann</td>
      <td></td>
    </tr>
    <tr>
      <td>Holme i sjø</td>
      <td>Liten øy/skjær i sjø</td>
      <td></td>
    </tr>
    <tr>
      <td>Holmegruppe i sjø</td>
      <td>Flere små skjær i sjø</td>
      <td></td>
    </tr>
    <tr>
      <td>Hotell</td>
      <td>Offentlig godkjent overnattingssted</td>
      <td></td>
    </tr>
    <tr>
      <td>Hylle (hjell)</td>
      <td>Flatt område i fjellside</td>
      <td></td>
    </tr>
    <tr>
      <td>Hyttefelt</td>
      <td>Offentlig eller privat  hyttefelt. Område som har høy utnyttelsesgrad med tanke på hytter.</td>
      <td></td>
    </tr>
    <tr>
      <td>Høl</td>
      <td>Dyp elvebunn under foss eller ved ende av stryk</td>
      <td></td>
    </tr>
    <tr>
      <td>Høyde</td>
      <td>Mindre terrengform som ikke vurderes som fjell</td>
      <td></td>
    </tr>
    <tr>
      <td>Idrettsanlegg</td>
      <td>(Alle typer utendørsanl. Noter type i merknadsfelt, f.eks. ridebane, fotballbane)</td>
      <td></td>
    </tr>
    <tr>
      <td>Idrettshall</td>
      <td>Alle typer innendørsanlegg Ishall/svømmehall idrettshall.</td>
      <td></td>
    </tr>
    <tr>
      <td>Industriområde</td>
      <td>Større sammenhengende område benyttet for industriformål</td>
      <td></td>
    </tr>
    <tr>
      <td>Innsjø</td>
      <td>Stort vann: Altevatnet, Femunden, Mjøsa, Nisser</td>
      <td></td>
    </tr>
    <tr>
      <td>Isbre</td>
      <td>Større sammenhengende snø- eller is område som ikke smelter i løpet av sommeren. F.eks. Svartisen eller Folgefonna</td>
      <td></td>
    </tr>
    <tr>
      <td>Jernbanestrekning</td>
      <td>Lang  jernbanestrekning. F.eks.  Ofotbanen, Bergensbanen</td>
      <td></td>
    </tr>
    <tr>
      <td>Jorde</td>
      <td>Kultivert dyrknings- mark</td>
      <td></td>
    </tr>
    <tr>
      <td>Juv</td>
      <td>Kløftlignende dal, canyon</td>
      <td></td>
    </tr>
    <tr>
      <td>Kabel</td>
      <td>Alle typer kabler i både sjø og ferskvann.</td>
      <td></td>
    </tr>
    <tr>
      <td>Kai</td>
      <td>Større, fast bryggeanlegg</td>
      <td></td>
    </tr>
    <tr>
      <td>Kanal</td>
      <td>Utgravd vannveg  i sjø og ferskvann</td>
      <td></td>
    </tr>
    <tr>
      <td>Kilde</td>
      <td>Oppkomme, olle, vannkilde. Kildeutspring. Benyttes for å angi stedet hvor grunnvannet kommer i dagen</td>
      <td></td>
    </tr>
    <tr>
      <td>Kirke</td>
      <td>Kirke / Kapell / Arbeidskirke knyttet til Den norske kirke</td>
      <td></td>
    </tr>
    <tr>
      <td>Klakk</td>
      <td>Spiss grunne. (Trøndersk/Nordnorsk uttrykk)</td>
      <td></td>
    </tr>
    <tr>
      <td>Klopp</td>
      <td>Gangbru over sjø og ferskvann</td>
      <td></td>
    </tr>
    <tr>
      <td>Kommune</td>
      <td>(Offisielt navn)</td>
      <td></td>
    </tr>
    <tr>
      <td>Kraftgate (Rørgate)</td>
      <td>Store tilførselsrør for kraftanlegg</td>
      <td></td>
    </tr>
    <tr>
      <td>Kraftledning</td>
      <td>Vanligvis store overføringsledninger</td>
      <td></td>
    </tr>
    <tr>
      <td>Kraftstasjon</td>
      <td>Alle størrelser for energi produksjon, (el. og varme)</td>
      <td></td>
    </tr>
    <tr>
      <td>Kryss (Veg/Gate)</td>
      <td>(For alle type veger)</td>
      <td></td>
    </tr>
    <tr>
      <td>Landingsstripe</td>
      <td>Landingsplass for privat flygning</td>
      <td></td>
    </tr>
    <tr>
      <td>Landskapsområde</td>
      <td>Stort landskapsområde:  Dalane, Jæren, Romerike, Grenland, Salten, Varanger</td>
      <td></td>
    </tr>
    <tr>
      <td>Lanterne</td>
      <td>Offisiell og privat lanterne langs kysten og i innlandet, fast</td>
      <td></td>
    </tr>
    <tr>
      <td>Li</td>
      <td>Vanligvis skogkledd skrånende terreng</td>
      <td></td>
    </tr>
    <tr>
      <td>Lone</td>
      <td>Nesten stillestående vik i elv eller bekk</td>
      <td></td>
    </tr>
    <tr>
      <td>Lykt (Fyrlykt)</td>
      <td>Offisiell og privat lykt/fyrlykt langs kysten og i innlandet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Lysbøye</td>
      <td>Offisiell og privat lysbøye langs kysten og i innlandet, flytende</td>
      <td></td>
    </tr>
    <tr>
      <td>Melkeplass</td>
      <td>Seterplass uten hus. Vanligvis i bratte områder på Vestlandet</td>
      <td></td>
    </tr>
    <tr>
      <td>Militært bygg/Anlegg</td>
      <td>Militærleir, militært bygg</td>
      <td></td>
    </tr>
    <tr>
      <td>Mo</td>
      <td>Flatt område, vanligvis skogkledd</td>
      <td></td>
    </tr>
    <tr>
      <td>Molo</td>
      <td>Fast byggverk, utstikkende voll i sjøen</td>
      <td></td>
    </tr>
    <tr>
      <td>Museum/ Galleri/Bibliotek</td>
      <td>Alle typer museum,  galleri og bibliotek</td>
      <td></td>
    </tr>
    <tr>
      <td>Myr</td>
      <td>Alle typer fra gressmyr til våt moldjord</td>
      <td></td>
    </tr>
    <tr>
      <td>Nasjon</td>
      <td>Selvstendig land (Offisielt navn)</td>
      <td></td>
    </tr>
    <tr>
      <td>Nes</td>
      <td>Landområde stikkende ut i ferskvann</td>
      <td></td>
    </tr>
    <tr>
      <td>Nes i sjø</td>
      <td>Landområde stikkende ut i saltvann</td>
      <td></td>
    </tr>
    <tr>
      <td>Nes ved elver</td>
      <td>Landet mellom to møtende elver. Vanligvis kun brukt i samiske områder. Stedsnavnets skrivemåte skal IKKE avgjøre om navnet skal gis denne koden, men KUN lokalitetens størrelse eller fasong.</td>
      <td></td>
    </tr>
    <tr>
      <td>Offersted</td>
      <td>Samisk, norsk eller finsk offersted</td>
      <td></td>
    </tr>
    <tr>
      <td>Oljeinstallasjon (Sjø)</td>
      <td>Stasjonære oljeinstallasjoner (faste og flytende)</td>
      <td></td>
    </tr>
    <tr>
      <td>Os</td>
      <td>Innløp eller utløp av elv eller bekk i innsjø/vann/tjern eller sjø (saltvann)</td>
      <td></td>
    </tr>
    <tr>
      <td>Overett</td>
      <td>Offisiell og privat. To stenger med/uten lys overett langs kysten og i innlandet, faste.</td>
      <td></td>
    </tr>
    <tr>
      <td>Park</td>
      <td>Kultivert område med eller uten trær. Kolonihage (i by eller tettbygd strøk)</td>
      <td></td>
    </tr>
    <tr>
      <td>Parkeringsplass</td>
      <td>Offentlig og privat</td>
      <td></td>
    </tr>
    <tr>
      <td>Pensjonat</td>
      <td>Offentlig godkjent overnattingssted</td>
      <td></td>
    </tr>
    <tr>
      <td>Plass/torg</td>
      <td>(I tettsted eller by)</td>
      <td></td>
    </tr>
    <tr>
      <td>Poststed (Postkontor)</td>
      <td>Offisielt poststed</td>
      <td></td>
    </tr>
    <tr>
      <td>Pytt</td>
      <td>Liten dam, myrpytt</td>
      <td></td>
    </tr>
    <tr>
      <td>Rasteplass</td>
      <td>Rasteplass med ansvarlig Statens vegvesen eller annen offentlig myndighet</td>
      <td></td>
    </tr>
    <tr>
      <td>Renne</td>
      <td>Undersjøisk dal</td>
      <td></td>
    </tr>
    <tr>
      <td>Rygg</td>
      <td>Langstrakt terrengform</td>
      <td></td>
    </tr>
    <tr>
      <td>Rygg i sjø</td>
      <td>Undersjøisk ås</td>
      <td></td>
    </tr>
    <tr>
      <td>Rørledning</td>
      <td>Alle typer rørledninger: Olje, gass, vann, etc.</td>
      <td></td>
    </tr>
    <tr>
      <td>Rådhus (komm, fylke, stat)</td>
      <td>Adm. senteret (-huset) i adm. enheten.</td>
      <td></td>
    </tr>
    <tr>
      <td>Sand</td>
      <td>Sand-grusområde over vannkontur/kystkontur. Morenemateriale</td>
      <td></td>
    </tr>
    <tr>
      <td>Senkning</td>
      <td>Flat forsenkning, dalsenkning</td>
      <td></td>
    </tr>
    <tr>
      <td>Serveringssted</td>
      <td>Serveringssted utenfor tettbygd område</td>
      <td></td>
    </tr>
    <tr>
      <td>Seter (sel, støl)</td>
      <td>Enklere landbruksbe­byggelse. Kan ha periodisk fast bosetting, vanligvis sommerstid.</td>
      <td></td>
    </tr>
    <tr>
      <td>Setervoll</td>
      <td>Ryddet, gressbevokst område på ei seter, med   eller uten hus</td>
      <td></td>
    </tr>
    <tr>
      <td>Severdighet</td>
      <td>Noter forklaring i merknadsfeltet, f.eks. minnesmerke</td>
      <td></td>
    </tr>
    <tr>
      <td>Sjøstykke</td>
      <td>Del av sjøen, vanligvis innaskjærs eller i kystnære farvann. F.eks. Folda, Hustadvika</td>
      <td></td>
    </tr>
    <tr>
      <td>Skar</td>
      <td>Markant senkning i fjell</td>
      <td></td>
    </tr>
    <tr>
      <td>Skiheis</td>
      <td>Skitrekk og stolheis i skianlegg.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skjær</td>
      <td>Stein i vannflaten</td>
      <td></td>
    </tr>
    <tr>
      <td>Skjær i sjø</td>
      <td>Stein i vannflaten.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skog</td>
      <td>Alle typer fra stor barskog til vierkratt i Finnmark</td>
      <td></td>
    </tr>
    <tr>
      <td>Skogområde</td>
      <td>Stort skogområde: Nordmarka, Bymarka, Finnskogen</td>
      <td></td>
    </tr>
    <tr>
      <td>Skole</td>
      <td>Offentlig og privat skole</td>
      <td></td>
    </tr>
    <tr>
      <td>Skred</td>
      <td>Rasområde: Alle typer materiale  (f.eks. stein, jord, sand, leire, o.l.)</td>
      <td></td>
    </tr>
    <tr>
      <td>Skytebane</td>
      <td>Pistol- eller geværbane (o.l. våpen)</td>
      <td></td>
    </tr>
    <tr>
      <td>Skytefelt</td>
      <td>Militære skytefelt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Slalåm- og utforbakke</td>
      <td>Alle typer regulerte alpinanlegg.</td>
      <td></td>
    </tr>
    <tr>
      <td>Slette</td>
      <td>Åpent, flatt, ikke skogbevokst område</td>
      <td></td>
    </tr>
    <tr>
      <td>Sluse</td>
      <td>Kunstig løfteanretning for båter i vassdrag</td>
      <td></td>
    </tr>
    <tr>
      <td>Småbåthavn</td>
      <td>Regulerte havneanlegg for småbåter</td>
      <td></td>
    </tr>
    <tr>
      <td>Sogn</td>
      <td>Kirkesogn Knyttet til Den norske kirke</td>
      <td></td>
    </tr>
    <tr>
      <td>Soneinndeling til havs</td>
      <td>Fiskerisone, havrettssone, etc. (Noter type i merknadsfelt)</td>
      <td></td>
    </tr>
    <tr>
      <td>Stake</td>
      <td>Offisiell og privat stake langs kysten og i innlandet, flytende</td>
      <td></td>
    </tr>
    <tr>
      <td>Stang</td>
      <td>Offisiell og privat jernstang langs kysten og i innlandet, fast</td>
      <td></td>
    </tr>
    <tr>
      <td>Stasjon</td>
      <td>Betjent stoppested for jernbane og trikk</td>
      <td></td>
    </tr>
    <tr>
      <td>Stein</td>
      <td>F.eks. flyttstein i fjellet</td>
      <td></td>
    </tr>
    <tr>
      <td>Sti</td>
      <td>Stistrekning, sleper (gamle drifteveger), reindriftsveger</td>
      <td></td>
    </tr>
    <tr>
      <td>Strand</td>
      <td>Sand-, grus- eller steindekket område i vannkanten</td>
      <td></td>
    </tr>
    <tr>
      <td>Strand i sjø</td>
      <td>Sand-, grus- eller steindekket område i sjøkanten</td>
      <td></td>
    </tr>
    <tr>
      <td>Stryk</td>
      <td>Parti der vannet går i stryk og skiller seg tydelig fra resten av elv eller bekk</td>
      <td></td>
    </tr>
    <tr>
      <td>Stup</td>
      <td>Loddrett eller svært bratt, fallende terreng</td>
      <td></td>
    </tr>
    <tr>
      <td>Stø</td>
      <td>Båtstø, båtplass i  vannkanten uten naust</td>
      <td></td>
    </tr>
    <tr>
      <td>Sund</td>
      <td>Innsnevret område i vann eller vassdrag</td>
      <td></td>
    </tr>
    <tr>
      <td>Sund i sjø</td>
      <td>Innsnevret område mellom øyer eller fastland</td>
      <td></td>
    </tr>
    <tr>
      <td>Sva</td>
      <td>Bart fjell-/steinparti</td>
      <td></td>
    </tr>
    <tr>
      <td>Sykehus</td>
      <td>Offentlig og privat sykehus</td>
      <td></td>
    </tr>
    <tr>
      <td>Søkk</td>
      <td>Mindre markant, begrenset fordypning</td>
      <td></td>
    </tr>
    <tr>
      <td>Søkk i sjø</td>
      <td>Stor eller liten grop på sjøbunnen</td>
      <td></td>
    </tr>
    <tr>
      <td>Taubane</td>
      <td>Uten persontrafikk. Se også 193</td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengdetalj</td>
      <td>Alle typer små naturdetaljer. f.eks. sprekker, hulveier, sand-/stein-/grusflater, etc.</td>
      <td></td>
    </tr>
    <tr>
      <td>Tettbebyggelse</td>
      <td>Mindre bebygd område uten sentrumskarakter f.eks. boligområde</td>
      <td></td>
    </tr>
    <tr>
      <td>Tettsted</td>
      <td>Mindre bymessig bebygd område av sentrumskarakter</td>
      <td></td>
    </tr>
    <tr>
      <td>Tettsteddel</td>
      <td>Kulturmessig del av tettsted. Se også navnetype 101.</td>
      <td></td>
    </tr>
    <tr>
      <td>Tjern</td>
      <td>Lite vann</td>
      <td></td>
    </tr>
    <tr>
      <td>Topp (fjelltopp/tind)</td>
      <td>Øverste fjelltopp</td>
      <td></td>
    </tr>
    <tr>
      <td>Torvtak</td>
      <td>Sted for uttak av myrtorv / brenntorv / veksttorv.</td>
      <td></td>
    </tr>
    <tr>
      <td>Traktorveg</td>
      <td>Driftsveger for kjøretøyer hvor vegen ikke kan kjøres med vanlig bil.</td>
      <td></td>
    </tr>
    <tr>
      <td>Tunnel</td>
      <td>Vanlig tunnel, rasoverbygg, undergang. Både gangveg, veg og jernbane. Angi ett punkt i hver ende for lange og ett punkt midt på for korte tunneler</td>
      <td></td>
    </tr>
    <tr>
      <td>Turisthytte</td>
      <td>Overnattingssted</td>
      <td></td>
    </tr>
    <tr>
      <td>TV/Radio-mast</td>
      <td>TV/Radio ?tårn. Alle typer bakkebasert telekommunikasjon</td>
      <td></td>
    </tr>
    <tr>
      <td>Tømmerrenne</td>
      <td>Kunstig tømmeranlegg</td>
      <td></td>
    </tr>
    <tr>
      <td>Tømmervelte</td>
      <td>Midlertidig lagringsplass for tømmer</td>
      <td></td>
    </tr>
    <tr>
      <td>Universitet/høgskole</td>
      <td>Offentlig og privat høyskole og universitet</td>
      <td></td>
    </tr>
    <tr>
      <td>Ur</td>
      <td>Steinområde, steinrøys</td>
      <td></td>
    </tr>
    <tr>
      <td>Utmark</td>
      <td>Ikke inngjerdet beitemark</td>
      <td></td>
    </tr>
    <tr>
      <td>Utsiktspunkt</td>
      <td>Både i tårn og på bakken f.eks. Kongens utsikt</td>
      <td></td>
    </tr>
    <tr>
      <td>Utstikker</td>
      <td>Flytende bryggeanlegg</td>
      <td></td>
    </tr>
    <tr>
      <td>Vad</td>
      <td>Vassested i elv, bekk vann eller sjø.</td>
      <td></td>
    </tr>
    <tr>
      <td>Vaktstasjon/Beredsskapsbygning</td>
      <td>Bygning for Politi/Brann/Los/Toll/Ambulanse/Fly- og skipsovervåkning</td>
      <td></td>
    </tr>
    <tr>
      <td>Vann</td>
      <td>Middels stort vann</td>
      <td></td>
    </tr>
    <tr>
      <td>Vanndetalj</td>
      <td>Alle typer : Noter forklaring i merknadsfeltet</td>
      <td></td>
    </tr>
    <tr>
      <td>Varde</td>
      <td>F.eks. merkerøys, steinrøys. Langs kysten og i innlandet</td>
      <td></td>
    </tr>
    <tr>
      <td>Veg (Gate)</td>
      <td>Formelle veg/gatenavn ellers kode 240</td>
      <td></td>
    </tr>
    <tr>
      <td>Vegbom</td>
      <td>Mindre bomanlegg på privat veg</td>
      <td></td>
    </tr>
    <tr>
      <td>Verksted</td>
      <td>Mindre industrivirksomhet</td>
      <td></td>
    </tr>
    <tr>
      <td>Verneområder</td>
      <td>(Alle typer både sjø og land. Noter type f.eks. Nasjonalpark i merknadsfelt)</td>
      <td></td>
    </tr>
    <tr>
      <td>Vidde</td>
      <td>Høyere liggende større område uten skog med lave terrengvariasjoner innenfor området. F.eks. Valdresflyi, Hardangervidda, Finnmarksvidda, Laksefjordvidda</td>
      <td></td>
    </tr>
    <tr>
      <td>Vik</td>
      <td>Kil, bukt i vann eller vassdrag.</td>
      <td></td>
    </tr>
    <tr>
      <td>Vik i sjø</td>
      <td>Kil, bukt</td>
      <td></td>
    </tr>
    <tr>
      <td>Våg</td>
      <td>Fjordarm, større vik</td>
      <td></td>
    </tr>
    <tr>
      <td>Øy</td>
      <td>Tørt landområde i ferskvann atskilt fra fastlandet</td>
      <td></td>
    </tr>
    <tr>
      <td>Øy i sjø</td>
      <td>Tørt landområde i saltvann atskilt fra fastlandet</td>
      <td></td>
    </tr>
    <tr>
      <td>Øygruppe</td>
      <td>To eller flere øyer i ferskvann</td>
      <td></td>
    </tr>
    <tr>
      <td>Øygruppe i sjø</td>
      <td>To eller flere øyer i saltvann f.eks. Hvaler og Lofoten</td>
      <td></td>
    </tr>
    <tr>
      <td>Øyr</td>
      <td>Sand-grusområde i elvemunning, elvedelta både mot innsjø/vann og saltvann</td>
      <td></td>
    </tr>
    <tr>
      <td>Ås</td>
      <td>Langstrakt, vanligvis skogkledd høydedrag.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Presentasjonskode

**Definisjon:** koplingsnøkkel mot presentasjonsinformasjon.
Merknad: Kan brukes for både tekst og symbol

NB: Dette er en tom kodeliste, innholdet følger med
dokumentversjonen av produktspesifikasjonen for N50 Kartdata

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

#### «Enumeration» TekstReferansePunktNord

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
      <td>Bunnlinje</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Midtlinje</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Øvre kant</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Grunnlinje</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» TekstReferansePunktØst

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
      <td>Venstre kant</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Midt i</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Høyre kant</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Sperring

**Definisjon:** sperring regulerer avstanden mellom bokstavene i teksten. Dette gjøres ved forhåndstall regulert til størrelsen på største bokstavblokk

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
      <td>Liten sperring</td>
      <td>Liten sperring = 1 drittel, dvs 1/3 av "største bokstavblokk" mellom hver bokstav.</td>
      <td></td>
    </tr>
    <tr>
      <td>Middels sperring</td>
      <td>Middels sperring = halvgefirt, dvs 1/2 av "største bokstavblokk" mellom hver bokstav.</td>
      <td></td>
    </tr>
    <tr>
      <td>Stor sperring</td>
      <td>Stor sperring = 1 gefirt, dvs 1 (største) "bokstavblokk" mellom hver bokstav.</td>
      <td></td>
    </tr>
  </tbody>
</table>
