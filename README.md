Repository for å lage produktspesifikasjoner i henhold til forenklet produksjonsløype.
Produktspesifikasjonen vil ikke tilfredsstille standarden "SOSI produktspesifikasjoner – Krav og godkjenning" men vil være i henhold til den nyeste internasjonale standard for produktspesifikasjoner (ISO19131:2022).
Produktspesifikasjonen vil også tilfredsstille krav fra "Det offentlige kartgrunnlaget".
Merk at andre DOK-krav, som valideringsfiler ikke 

Forutsetninger for etablering av produktspesifikasjon i denne produksjonsløya:
1. Det må finnes gode metadata i Geonorge
2. Det må finnes en beskrivelse av datamodellen fra et api (OGC API - Features) eller en datamodell i SOSI modellregister.
3. Datamodellen skal inneholder gode definisjoner på objekttyper, egenskaper og kodelister der det er påkrevd
4. Det må lages en konfig-fil på rotkatalogen i dette repositoriet i henhold til oppsett under

Eksempel på config.yaml:
--------------------------
metadataId: 041f1e6e-bdbc-4091-b48f-8a5990f3cc5b
ogc_feature_api: https://kos-pygeoapi.atkv3-dev.kartverket.cloud/collections
output_directory: produktspesifikasjon
product_slug: admenheter
updated: 2025-01-01
xmi_url: https://sosi.geonorge.no/svn/SOSI/SOSI Del 3/Statens kartverk/AdministrativeEnheter_FylkerOgKommuner-20240101.xml
--------------------------
   
Datamodeller fra SOSI modellregistr finnes under SOSI Del 3:
https://sosi.geonorge.no/!/#SOSI/view/head/SOSI%20Del%203

Metadata finnes på Geonorge:
https://kartkatalog.geonorge.no


