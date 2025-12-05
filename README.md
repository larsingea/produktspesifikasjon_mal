
# Produksjon av "forenklet produktspesifikasjon" versjon 0.1

Repository for å lage produktspesifikasjoner i henhold til forenklet produksjonsløype.  
Produktspesifikasjonen vil ikke tilfredsstille standarden "SOSI produktspesifikasjoner – Krav og godkjenning" men vil være i henhold til den nyeste internasjonale standard for produktspesifikasjoner (ISO19131:2022).  
Produktspesifikasjonen vil også tilfredsstille krav fra "Det offentlige kartgrunnlaget".  
Merk at andre DOK-krav, som valideringsfiler ikke produseres ved hjelp av denne metoden.

Forutsetninger for etablering av produktspesifikasjon i denne produksjonsløya:
1. Det må finnes gode metadata i Geonorge
2. Det må finnes en beskrivelse av datamodellen fra et api (OGC API - Features) eller en datamodell i SOSI modellregister.
3. Datamodellen skal inneholder gode definisjoner på objekttyper, egenskaper og kodelister der det er påkrevd
4. Det må lages en konfig-fil på rotkatalogen i dette repositoriet i henhold til oppsett under

Eksempel på config.yaml:

> metadataId: (uuid til metadata)  
> ogc_feature_api: (URL til endepunkt for OGC API Fetures Collection)  
> output_directory: (katalog hvor du ønsker at produktspesifikasjonen(e) dine skal skrives til)  
> product_slug: (underkatalog hvor du ønsker gjeldende produktspesifikasjon skal skrives til)  
> updated: (Datao produktspesifikasjonen er gyldig fra - "YYYY-MM-DD")  
> xmi_url: (URL til UML-modell i SOSI modellergister - https://sosi.geonorge.no/!/#SOSI/view/head/SOSI%20Del%203/)  

**NB!** "ogc_feature_api" og "xmi_url" er ikke påkrevd, men da etableres det ingen beskrivelse av datamodellen i produktspesifikasjonen
  
Datamodeller fra SOSI modellregistr finnes under SOSI Del 3:
https://sosi.geonorge.no/svn/SOSI/SOSI Del 3

Metadata-uuid finnes på Geonorge:
https://kartkatalog.geonorge.no


