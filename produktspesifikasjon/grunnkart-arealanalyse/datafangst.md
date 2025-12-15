Arbeidet med Nasjonalt grunnkart for arealanalyse startet i 2023 som et samarbeid mellom NIBIO, SSB, Kartverket og Miljødirektoratet. Arbeidet med å etablere Grunnkartet tok utgangspunkt i metoder og datagrunnlag som allerede benyttes i arbeidet med den offentlige arealbruks- og arealressursstatistikken. Dette grunnlaget er ytterligere beriket ved å tilføre data fra andre offentlige kartdatabaser og registre, samt tilføre datasettet en økosystemkoding.
#### Testversjon 1:
Testversjon 1 av Grunnkartet ble publisert i februar 2024. Våren 2024 ble det gjennomført brukerdialog gjennom møter med utvalgte brukere og spørreskjemaer. Tilbakemeldingene pekte på behov for retting av topologifeil, tematiske avklaringer og bedre brukerveiledning.
Testversjon 1 inneholdt følgende egenskaper: Arealdekke, Arealbruk, Økosystemklasse, Grøntandel, Areal og Kommunenummer.
#### Testversjon 2:
I arbeidet med Testversjon 2 har fokuset vært å lage et mer ryddig, enklere og mer intuitivt kart. Det er blant annet arbeidet med tematiske problemstillinger rundt nomenklaturen for arealdekke og arealbruk, og det er foretatt en mer systematisk topologi- og geometrirydding. I tillegg er det inkludert arealbruk i hav. Testversjon 2 ble publisert 1. april 2025, og inkluderer forbedringer basert på tilbakemeldingene etter Testversjon 1.
Ny periode med brukerinvolvering ble gjennomført våren 2025. Innspillene vurderes og eventuelle endringer implementeres frem mot en standardisert årsversjon, som er planlagt publisert i desember 2025. Målet er at Grunnkartet skal oppdateres årlig, og videreutvikles og forvaltes innenfor rammene av det nasjonale geodatasamarbeidet.
Testversjon 2 inneholder følgende egenskaper: Arealdekke, Arealbruk, Økosystemklasse, Areal, Kommunenummer, Kilde, Treslag, Grunnforhold og Arealbruk i hav (stedfast og ikke-stedfast).

#### Tematiske detaljer
Arealdekke baseres på klassifikasjonen av arealressurs i FKB-AR5, med tilleggsinformasjon om skog og snaumark. I Testversjon 2 er dette temaet oppdelt i fire temalag; arealdekke, treslag, skogbonitet og grunnforhold. Kodingen skal være gjenkjennbar for brukere som kjenner AR5-typologien, men med noen avvik og endringer.

Arealbruksklassifikasjonen baseres på SSB-arealbruk, slik den er tilgjengelig på Geonorge. En grov inndeling av arealbruken på land er gitt i arealbruk_hovedklasse, mens en mer fininndelt klassifisering finnes i arealbruk_underklasse. Nytt i testversjon 2 er at kildedata for hvert polygon er inkludert, noe som kan gi bedre innsikt i datakvalitet og gjør det enklere å spore og rette feil. Arealbruk er gitt for bebygde og opparbeida arealer, men for ubebygde områder vil disse kolonnene være blanke.

Arealbruk i hav er nytt i Testversjon 2, og vises i to kolonner. HavArealbrukStedbundet viser installasjoner, og annen klart stedbundet aktivitet, mens HavFiskeriBruk viser områder der det foregår fiske. De to kolonnene kan ansees som en smakebit på hvordan arealbruk i hav kan framstilles, og det vil være viktig å få brukernes tilbakemeldinger på disse.

Økosystemklassifikasjonen følger, så langt det er mulig, Eurostats anbefalte klassifikasjon (3 nivåer). I bebygde områder følges den til nivå 3 så langt det har latt seg gjøre. Miljødirektoratet, med bistand fra NINA, har tilordnet Eurostat-klasser til kombinasjoner av arealdekke, arealbruk, treslag, grunnforhold, bonitet og kysttilhørighet. Som hovedregel overstyrer arealbruk arealdekke ved konflikt.

Eurostats økosystemklassifikasjon er beskrevet i NIBIO rapport 9 (143) 2023 «Hovedøkosystemkart for Norge" https://hdl.handle.net/11250/3106442
