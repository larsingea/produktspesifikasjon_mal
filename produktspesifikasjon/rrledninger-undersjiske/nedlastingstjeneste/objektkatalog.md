### Datamodell

<a href="nedlastingstjeneste_feature_catalogue.png" title="Klikk for stor visning"><img src="nedlastingstjeneste_feature_catalogue.png" alt="Datamodell nedlastingstjeneste" style="max-width: 100%; height: auto;" /></a>

#### CablesPipelines

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>cablePipelineFunction</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CableAndPipelineFunction</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- CO2<br />- Communication<br />- Condensate<br />- DEH<br />- Gas<br />- Power<br />- Glycol<br />- Seismic<br />- Hydraulic<br />- Methanol<br />- Oil<br />- Oil/Gas<br />- Umbilical<br />- Water<br />- Water/Gas<br />- Miscellaneous<br />- Unknown<br />- Serviceline<br />- Flowline<br />- Spool<br />- Riser</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>dimension</strong></td>
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
      <td><strong>dimensionUnit</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CablePipelineDimensionUnits</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- mm<br />- Feet<br />- Inches<br />- Unknown</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>length</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>length in meters</td>
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
CommonProperties

#### InstallationPoint

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>position</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Location where the object exists.</td>
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
      <td><strong>type</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>InstallationPointEquipmentTypes</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Anchor<br />- Compressor<br />- Facility<br />- Buoy (general)<br />- Crossing Position<br />- Distribution Unit<br />- Static Platform<br />- Structure<br />- Buoy (midline)<br />- Dynamic Platform<br />- Equipment<br />- Hang-off Position<br />- Junction/Branch<br />- Concrete Block<br />- Living Quarter<br />- Manifold<br />- Start/End/Tie-in Position<br />- Counteract<br />- Hub Position<br />- Cover<br />- On-shore Facility/Plant<br />- PLEM/PLET<br />- Touch Down Position<br />- Floating Unit - Ship<br />- Mattress<br />- Riser Base<br />- Other/Undefined<br />- Template<br />- Pile<br />- Valve/Valve Station<br />- Transponder<br />- Well/Wellpad<br />- Big Bag/Gravel Bag<br />- Cable Connection Module<br />- El-substation/Power supply<br />- Filter Unit Bag<br />- Marker Bag<br />- Support Plate<br />- Storage Tank/Unit<br />- Loading Buoy<br />- Wave Buoy Floater<br />- Submerged Loading Buoy<br />- Subsea Current Buoy<br />- Clamp<br />- Substructure/Base<br />- Flange<br />- Wind Turbine<br />- J-tube<br />- Anode Bed<br />- CP Cabinet<br />- Clump Weight/Dead Man Anchor</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>refSys</strong></td>
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
      <td><strong>utmEast</strong></td>
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
      <td><strong>utmNorth</strong></td>
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

Relasjoner

**Arv**
CommonProperties

#### SafetyRestrictionPolygon

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>area</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>area over which an object extends</td>
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
      <td><strong>type</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>SafetyRestrictionTypes</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- airApproachZone<br />- buoyMovement<br />- drillCuttingsDisposalArea<br />- militaryZone<br />- noLoadingDischarging<br />- prohibitedArea<br />- rigHandlingZone<br />- targetBox<br />- wetStoreArea<br />- otherUndefined<br />- safetyZone<br />- anchoringAndFishingProhibited<br />- loadingZone<br />- exclusionZone-Red<br />- exclusionZone-Yellow<br />- subseaCautionArea<br />- contaminatedArea<br />- plantArea<br />- windfarmArea<br />- onshoreRestrictedArea<br />- pipelineMovementArea<br />- rigArea<br />- seabedCautionArea<br />- surfaceCautionArea<br />- temporarySurveillanceZone<br />- anchorZone</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
CommonProperties

#### InstallationLine

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>line</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>geometritype som representerer en sekvens av posisjoner</td>
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
      <td><strong>type</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>InstallationLineEquipmentTypes</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Anchor<br />- Compressor<br />- Facility<br />- Wire<br />- Anchor Line<br />- Clump Weight<br />- Distribution Unit<br />- Static Platform<br />- Structure<br />- Counteract<br />- Dynamic Platform<br />- Equipment<br />- Junction/Branch<br />- Living Quarter<br />- Manifold<br />- Other/Undefined<br />- Clamp<br />- Drilling Rig<br />- Flange<br />- PLEM/PLET<br />- Floating Unit - Ship<br />- Riser Base<br />- Template<br />- Valve/Valve Station<br />- Well/Wellpad<br />- Cable Connection Module<br />- Platform/Rig bridge<br />- Submerged Loading Buoy<br />- Substructure/Base<br />- Wind Turbine<br />- Deck</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
CommonProperties

#### InstallationPolygon

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>area</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>area over which an object extends</td>
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
      <td><strong>type</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>InstallationPolyEqipmentTypes</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Bag Area<br />- Distribution Unit<br />- Facility<br />- Cover<br />- Structure<br />- Equipment<br />- Mattress<br />- Support Plate<br />- Template<br />- Other/Undefined<br />- Tunnel<br />- Borehole<br />- Substructure/Base</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
CommonProperties

#### CommonProperties (abstrakt)

Abstract object used as a container for properties that the object-types have in common.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>crsOriginal</strong></td>
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
      <td><strong>coordinateStatus</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CoordinateStatusExisting</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- As built<br />- As found<br />- Authorized<br />- Designed<br />- Digitized<br />- Unknown<br />- As laid/installed</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>field</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>OilField</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Gina Krog<br />- Glitne<br />- Kristin<br />- Lavrans<br />- Loke<br />- Maria<br />- Morvin<br />- Norne<br />- Sigyn<br />- Skarv<br />- Sleipner<br />- Sleipner øst<br />- Smørbukk<br />- Snøhvit<br />- Trestakk<br />- Tyrihans<br />- Volve<br />- Åsgard<br />- Askeladd<br />- Gudrun<br />- Johan Castberg<br />- Midgard<br />- Mikkel</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>crsTransformationMethod</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CRS_TransformationMethod</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- ST_ED50_WGS84_N62_T1612<br />- ST_ED50_WGS84_S62_T1613<br />- ST_ED50_WGS84_OnShore_Europe_T1133<br />- ST_ED50_WGS84_OffShore_GB_T1311</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>fromDate</strong></td>
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
      <td><strong>name</strong></td>
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
      <td><strong>objectId</strong></td>
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
      <td><strong>operator</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Operator</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Amerada<br />- Apache<br />- Apollo<br />- Arco<br />- Asn_Telecom – Asn Telecom<br />- Atp<br />- Bbl<br />- Bhp<br />- Bkk_Nett_As – Bkk Nett As<br />- Bord_Gais – Bord Gais<br />- Bp_Exploration – Bp Exploration<br />- Britannia<br />- British_Gas – British Gas<br />- British_Telecom_International – British Telecom International<br />- Burlington<br />- C_W_Telecom – C&amp;W Telecom<br />- Cable_Wireless – Cable &amp; Wireless<br />- Cableco<br />- Caledonia<br />- Centrica<br />- Ch4_Energy – Ch4 Energy<br />- Channel_Islands_Electricity_Grid – Channel Islands Electricity Grid<br />- Chevrontexaco<br />- Cnr_International – Cnr International<br />- Conocophillips<br />- Cvc<br />- Dana_Pet – Dana Pet<br />- Dangas_Rlk – Dangas/Rlk<br />- Dea<br />- Det_Norske – Det Norske<br />- Deutsche_Bundes_Post_Telecom – Deutsche Bundes Post Telecom<br />- Deutsche_Telekom_Ag – Deutsche Telekom Ag<br />- Dong<br />- Encana<br />- Eni<br />- Esat_Telecom – Esat Telecom<br />- Exxonmobil<br />- Farice_Ltd – Farice Ltd<br />- Flag_Ltd – Flag Ltd<br />- Gasnor<br />- Gassco<br />- Gdf_Suez – Gdf Suez<br />- Global_Crossing_Telecom – Global Crossing Telecom<br />- Global_Submarine_Telecom – Global Submarine Telecom<br />- Global_Telesystems – Global Telesystems<br />- Great_Northern_Telegraph – Great Northern Telegraph<br />- Hamilton<br />- Haugaland_Kraftlag – Haugaland Kraftlag<br />- Hrl<br />- Interconnector<br />- Interoute<br />- Kerr-Mcgee<br />- Kpn_Telecom_Bv – Kpn Telecom Bv<br />- Lundin<br />- Lyse<br />- Manx_Electricity_Authority – Manx Electricity Authority<br />- Marathon<br />- Mci_Telecom – Mci Telecom<br />- Mærsk<br />- Nederlandse_Aardolie_Maatschappij_Bv – Nederlandse Aardolie Maatschappij Bv<br />- Netherlands_Post_Telegraph_Telephone – Netherlands Post,Telegraph,Telephone<br />- Newfield<br />- Nexen<br />- Nordhordaland_Kraftlag – Nordhordaland Kraftlag<br />- Norsk_Hydro – Norsk Hydro<br />- Norske_Shell – Norske Shell<br />- Northern_Ireland_Electricity – Northern Ireland Electricity<br />- Ntl<br />- Paladin<br />- Perenco<br />- Petrocan<br />- Petroland<br />- Petroleum_Geo-Services – Petroleum Geo-Services<br />- Placid<br />- Repsol<br />- Ruhrgas<br />- Shefa<br />- Shell<br />- Shell_UK_E_P – Shell UK E&amp;P<br />- Smedvig_Petroservices – Smedvig Petroservices<br />- Sonatrach<br />- Statoil<br />- Sun_Oil – Sun Oil<br />- Tampnet<br />- Telecom_Danmark – Telecom Danmark<br />- Telecom_Fin_Swe_Nor_Den – Telecom Fin/Swe/Nor/Den<br />- Telenor<br />- Total<br />- Tullow<br />- Unknown<br />- Unocal<br />- Venture<br />- Vsnl_Telecoms – Vsnl Telecoms<br />- Vtl_UK_Ltd – Vtl UK Ltd<br />- Wintershall</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>revDate</strong></td>
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
      <td><strong>revNo</strong></td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>StatusDescription</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Decommissioned<br />- Installed<br />- Planned<br />- Under construction<br />- In service<br />- Not in service<br />- Temporary<br />- Unknown</td>
    </tr>
  </tbody>
</table>

### Kodelister

#### «Enumeration» CableAndPipelineFunction

**Definisjon:** Valid FUNCTION codes for pipelines

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
      <td>CO2</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Communication</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Condensate</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>DEH</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gas</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Power</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Glycol</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Seismic</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hydraulic</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Methanol</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oil</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Oil/Gas</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Umbilical</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Water</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Water/Gas</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Miscellaneous</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Unknown</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Serviceline</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flowline</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spool</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Riser</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» CablePipelineDimensionUnits

**Definisjon:** Valid DIMENSION codes for cables and pipeline (diameter)

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
      <td>mm</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Feet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Inches</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Unknown</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» InstallationPointEquipmentTypes

**Definisjon:** Valid TYPE codes for Equipment subtype (point)

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
      <td>Anchor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Compressor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Facility</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Buoy (general)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Crossing Position</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Distribution Unit</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Static Platform</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Structure</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Buoy (midline)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dynamic Platform</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Equipment</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hang-off Position</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Junction/Branch</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Concrete Block</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Living Quarter</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Manifold</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Start/End/Tie-in Position</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Counteract</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hub Position</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cover</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>On-shore Facility/Plant</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>PLEM/PLET</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Touch Down Position</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Floating Unit - Ship</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mattress</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Riser Base</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Other/Undefined</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Template</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Pile</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Valve/Valve Station</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Transponder</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Well/Wellpad</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Big Bag/Gravel Bag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cable Connection Module</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>El-substation/Power supply</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Filter Unit Bag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Marker Bag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Support Plate</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Storage Tank/Unit</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Loading Buoy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Wave Buoy Floater</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Submerged Loading Buoy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Subsea Current Buoy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Clamp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Substructure/Base</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flange</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Wind Turbine</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>J-tube</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Anode Bed</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>CP Cabinet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Clump Weight/Dead Man Anchor</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» SafetyRestrictionTypes

**Definisjon:** Valid TYPE codes for safety - and restricted/reserved areas

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
      <td>airApproachZone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>buoyMovement</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>drillCuttingsDisposalArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>militaryZone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>noLoadingDischarging</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>prohibitedArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>rigHandlingZone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>targetBox</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>wetStoreArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>otherUndefined</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>safetyZone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>anchoringAndFishingProhibited</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>loadingZone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>exclusionZone-Red</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>exclusionZone-Yellow</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>subseaCautionArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>contaminatedArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>plantArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>windfarmArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>onshoreRestrictedArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>pipelineMovementArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>rigArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>seabedCautionArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>surfaceCautionArea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>temporarySurveillanceZone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>anchorZone</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» InstallationLineEquipmentTypes

**Definisjon:** Valid TYPE codes for Equipment subtype (line)

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
      <td>Anchor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Compressor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Facility</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Wire</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Anchor Line</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Clump Weight</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Distribution Unit</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Static Platform</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Structure</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Counteract</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dynamic Platform</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Equipment</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Junction/Branch</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Living Quarter</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Manifold</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Other/Undefined</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Clamp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Drilling Rig</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flange</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>PLEM/PLET</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Floating Unit - Ship</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Riser Base</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Template</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Valve/Valve Station</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Well/Wellpad</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cable Connection Module</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Platform/Rig bridge</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Submerged Loading Buoy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Substructure/Base</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Wind Turbine</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Deck</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» InstallationPolyEqipmentTypes

**Definisjon:** Valid TYPE codes for installation equipment (polygon)

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
      <td>Bag Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Distribution Unit</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Facility</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cover</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Structure</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Equipment</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mattress</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Support Plate</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Template</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Other/Undefined</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tunnel</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Borehole</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Substructure/Base</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» CoordinateStatusExisting

**Definisjon:** Valid COORDINATE_STATUS code for existing features

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
      <td>As built</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>As found</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Authorized</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Designed</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitized</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Unknown</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>As laid/installed</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» OilField

**Definisjon:** oljefelt

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
      <td>Gina Krog</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Glitne</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kristin</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lavrans</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Loke</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Maria</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Morvin</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Norne</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sigyn</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skarv</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sleipner</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sleipner øst</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Smørbukk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Snøhvit</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Trestakk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tyrihans</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Volve</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Åsgard</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Askeladd</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gudrun</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Johan Castberg</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Midgard</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mikkel</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» CRS_TransformationMethod

**Definisjon:** Valid method used to transform from original CRS

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
      <td>ST_ED50_WGS84_N62_T1612</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>ST_ED50_WGS84_S62_T1613</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>ST_ED50_WGS84_OnShore_Europe_T1133</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>ST_ED50_WGS84_OffShore_GB_T1311</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Operator

**Definisjon:** operator

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
      <td>Amerada</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Apache</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Apollo</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Arco</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Asn_Telecom</td>
      <td>Asn Telecom</td>
      <td></td>
    </tr>
    <tr>
      <td>Atp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bbl</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bhp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bkk_Nett_As</td>
      <td>Bkk Nett As</td>
      <td></td>
    </tr>
    <tr>
      <td>Bord_Gais</td>
      <td>Bord Gais</td>
      <td></td>
    </tr>
    <tr>
      <td>Bp_Exploration</td>
      <td>Bp Exploration</td>
      <td></td>
    </tr>
    <tr>
      <td>Britannia</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>British_Gas</td>
      <td>British Gas</td>
      <td></td>
    </tr>
    <tr>
      <td>British_Telecom_International</td>
      <td>British Telecom International</td>
      <td></td>
    </tr>
    <tr>
      <td>Burlington</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>C_W_Telecom</td>
      <td>C&amp;W Telecom</td>
      <td></td>
    </tr>
    <tr>
      <td>Cable_Wireless</td>
      <td>Cable &amp; Wireless</td>
      <td></td>
    </tr>
    <tr>
      <td>Cableco</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Caledonia</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Centrica</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ch4_Energy</td>
      <td>Ch4 Energy</td>
      <td></td>
    </tr>
    <tr>
      <td>Channel_Islands_Electricity_Grid</td>
      <td>Channel Islands Electricity Grid</td>
      <td></td>
    </tr>
    <tr>
      <td>Chevrontexaco</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cnr_International</td>
      <td>Cnr International</td>
      <td></td>
    </tr>
    <tr>
      <td>Conocophillips</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cvc</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dana_Pet</td>
      <td>Dana Pet</td>
      <td></td>
    </tr>
    <tr>
      <td>Dangas_Rlk</td>
      <td>Dangas/Rlk</td>
      <td></td>
    </tr>
    <tr>
      <td>Dea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Det_Norske</td>
      <td>Det Norske</td>
      <td></td>
    </tr>
    <tr>
      <td>Deutsche_Bundes_Post_Telecom</td>
      <td>Deutsche Bundes Post Telecom</td>
      <td></td>
    </tr>
    <tr>
      <td>Deutsche_Telekom_Ag</td>
      <td>Deutsche Telekom Ag</td>
      <td></td>
    </tr>
    <tr>
      <td>Dong</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Encana</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Eni</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Esat_Telecom</td>
      <td>Esat Telecom</td>
      <td></td>
    </tr>
    <tr>
      <td>Exxonmobil</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Farice_Ltd</td>
      <td>Farice Ltd</td>
      <td></td>
    </tr>
    <tr>
      <td>Flag_Ltd</td>
      <td>Flag Ltd</td>
      <td></td>
    </tr>
    <tr>
      <td>Gasnor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gassco</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gdf_Suez</td>
      <td>Gdf Suez</td>
      <td></td>
    </tr>
    <tr>
      <td>Global_Crossing_Telecom</td>
      <td>Global Crossing Telecom</td>
      <td></td>
    </tr>
    <tr>
      <td>Global_Submarine_Telecom</td>
      <td>Global Submarine Telecom</td>
      <td></td>
    </tr>
    <tr>
      <td>Global_Telesystems</td>
      <td>Global Telesystems</td>
      <td></td>
    </tr>
    <tr>
      <td>Great_Northern_Telegraph</td>
      <td>Great Northern Telegraph</td>
      <td></td>
    </tr>
    <tr>
      <td>Hamilton</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Haugaland_Kraftlag</td>
      <td>Haugaland Kraftlag</td>
      <td></td>
    </tr>
    <tr>
      <td>Hrl</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Interconnector</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Interoute</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kerr-Mcgee</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kpn_Telecom_Bv</td>
      <td>Kpn Telecom Bv</td>
      <td></td>
    </tr>
    <tr>
      <td>Lundin</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lyse</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Manx_Electricity_Authority</td>
      <td>Manx Electricity Authority</td>
      <td></td>
    </tr>
    <tr>
      <td>Marathon</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mci_Telecom</td>
      <td>Mci Telecom</td>
      <td></td>
    </tr>
    <tr>
      <td>Mærsk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nederlandse_Aardolie_Maatschappij_Bv</td>
      <td>Nederlandse Aardolie Maatschappij Bv</td>
      <td></td>
    </tr>
    <tr>
      <td>Netherlands_Post_Telegraph_Telephone</td>
      <td>Netherlands Post,Telegraph,Telephone</td>
      <td></td>
    </tr>
    <tr>
      <td>Newfield</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nexen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nordhordaland_Kraftlag</td>
      <td>Nordhordaland Kraftlag</td>
      <td></td>
    </tr>
    <tr>
      <td>Norsk_Hydro</td>
      <td>Norsk Hydro</td>
      <td></td>
    </tr>
    <tr>
      <td>Norske_Shell</td>
      <td>Norske Shell</td>
      <td></td>
    </tr>
    <tr>
      <td>Northern_Ireland_Electricity</td>
      <td>Northern Ireland Electricity</td>
      <td></td>
    </tr>
    <tr>
      <td>Ntl</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Paladin</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Perenco</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Petrocan</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Petroland</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Petroleum_Geo-Services</td>
      <td>Petroleum Geo-Services</td>
      <td></td>
    </tr>
    <tr>
      <td>Placid</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Repsol</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ruhrgas</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Shefa</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Shell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Shell_UK_E_P</td>
      <td>Shell UK E&amp;P</td>
      <td></td>
    </tr>
    <tr>
      <td>Smedvig_Petroservices</td>
      <td>Smedvig Petroservices</td>
      <td></td>
    </tr>
    <tr>
      <td>Sonatrach</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Statoil</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sun_Oil</td>
      <td>Sun Oil</td>
      <td></td>
    </tr>
    <tr>
      <td>Tampnet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Telecom_Danmark</td>
      <td>Telecom Danmark</td>
      <td></td>
    </tr>
    <tr>
      <td>Telecom_Fin_Swe_Nor_Den</td>
      <td>Telecom Fin/Swe/Nor/Den</td>
      <td></td>
    </tr>
    <tr>
      <td>Telenor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Total</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tullow</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Unknown</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Unocal</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Venture</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vsnl_Telecoms</td>
      <td>Vsnl Telecoms</td>
      <td></td>
    </tr>
    <tr>
      <td>Vtl_UK_Ltd</td>
      <td>Vtl UK Ltd</td>
      <td></td>
    </tr>
    <tr>
      <td>Wintershall</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» StatusDescription

**Definisjon:** Valid STATUS description codes

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
      <td>Decommissioned</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Installed</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Planned</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Under construction</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>In service</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Not in service</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Temporary</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Unknown</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
