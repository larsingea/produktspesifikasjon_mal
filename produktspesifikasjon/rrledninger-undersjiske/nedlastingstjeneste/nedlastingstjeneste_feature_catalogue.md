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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Air Approach Zone<br />- Anchor Zone<br />- Anchoring and Fishing Prohibited<br />- Buoy Movement<br />- Contaminated Area<br />- Drill Cuttings/Disposal Area<br />- Exclusion Zone - Red<br />- Exclusion Zone - Yellow<br />- Loading Zone<br />- Military Zone<br />- No Loading/Discharging<br />- Onshore Restricted Area<br />- Other/Undefined<br />- Pipeline Movement Area<br />- Plant Area<br />- Prohibited Area<br />- Rig Area<br />- Rig Handling Zone<br />- Safety Zone<br />- Seabed Caution Area<br />- Subsea Caution Area<br />- Surface Caution Area<br />- Target Box<br />- Temporary Surveillance Zone<br />- Wet Store Area<br />- Windfarm Area</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
CommonProperties

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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- CO2<br />- Communication<br />- Condensate<br />- DEH<br />- Flowline<br />- Gas<br />- Glycol<br />- Hydraulic<br />- Methanol<br />- Miscellaneous<br />- Oil<br />- Oil/Gas<br />- Power<br />- Riser<br />- Seismic<br />- Serviceline<br />- Spool<br />- Umbilical<br />- Unknown<br />- Water<br />- Water/Gas</td>
    </tr>
  </tbody>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Feet<br />- Inches<br />- mm<br />- Unknown</td>
    </tr>
  </tbody>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Bag Area<br />- Borehole<br />- Cover<br />- Distribution Unit<br />- Equipment<br />- Facility<br />- Mattress<br />- Other/Undefined<br />- Structure<br />- Substructure/Base<br />- Support Plate<br />- Template<br />- Tunnel</td>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- As built<br />- As found<br />- As laid/installed<br />- Authorized<br />- Designed<br />- Digitized<br />- Unknown</td>
    </tr>
  </tbody>
</table>

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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- ST_ED50_WGS84_N62_T1612<br />- ST_ED50_WGS84_OffShore_GB_T1311<br />- ST_ED50_WGS84_OnShore_Europe_T1133<br />- ST_ED50_WGS84_S62_T1613</td>
    </tr>
  </tbody>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Askeladd<br />- Gina Krog<br />- Glitne<br />- Gudrun<br />- Johan Castberg<br />- Kristin<br />- Lavrans<br />- Loke<br />- Maria<br />- Midgard<br />- Mikkel<br />- Morvin<br />- Norne<br />- Sigyn<br />- Skarv<br />- Sleipner<br />- Sleipner øst<br />- Smørbukk<br />- Snøhvit<br />- Trestakk<br />- Tyrihans<br />- Volve<br />- Åsgard</td>
    </tr>
  </tbody>
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
      <td><strong>fromLocation</strong></td>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Amerada<br />- Apache<br />- Apollo<br />- Arco<br />- Asn Telecom<br />- Atp<br />- Bbl<br />- Bhp<br />- Bkk Nett As<br />- Bord Gais<br />- Bp Exploration<br />- Britannia<br />- British Gas<br />- British Telecom International<br />- Burlington<br />- C&amp;W Telecom<br />- Cable &amp; Wireless<br />- Cableco<br />- Caledonia<br />- Centrica<br />- Ch4 Energy<br />- Channel Islands Electricity Grid<br />- Chevrontexaco<br />- Cnr International<br />- Conocophillips<br />- Cvc<br />- Dana Pet<br />- Dangas/Rlk<br />- Dea<br />- Det Norske<br />- Deutsche Bundes Post Telecom<br />- Deutsche Telekom Ag<br />- Dong<br />- Encana<br />- Eni<br />- Esat Telecom<br />- Exxonmobil<br />- Farice Ltd<br />- Flag Ltd<br />- Gasnor<br />- Gassco<br />- Gdf Suez<br />- Global Crossing Telecom<br />- Global Submarine Telecom<br />- Global Telesystems<br />- Great Northern Telegraph<br />- Hamilton<br />- Haugaland Kraftlag<br />- Hrl<br />- Interconnector<br />- Interoute<br />- Kerr-Mcgee<br />- Kpn Telecom Bv<br />- Lundin<br />- Lyse<br />- Manx Electricity Authority<br />- Marathon<br />- Mci Telecom<br />- Mærsk<br />- Nederlandse Aardolie Maatschappij Bv<br />- Netherlands Post,Telegraph,Telephone<br />- Newfield<br />- Nexen<br />- Nordhordaland Kraftlag<br />- Norsk Hydro<br />- Norske Shell<br />- Northern Ireland Electricity<br />- Ntl<br />- Paladin<br />- Perenco<br />- Petrocan<br />- Petroland<br />- Petroleum Geo-Services<br />- Placid<br />- Repsol<br />- Ruhrgas<br />- Shefa<br />- Shell<br />- Shell UK E&amp;P<br />- Smedvig Petroservices<br />- Sonatrach<br />- Statoil<br />- Sun Oil<br />- Tampnet<br />- Telecom Danmark<br />- Telecom Fin/Swe/Nor/Den<br />- Telenor<br />- Total<br />- Tullow<br />- Unknown<br />- Unocal<br />- Venture<br />- Vsnl Telecoms<br />- Vtl UK Ltd<br />- Wintershall</td>
    </tr>
  </tbody>
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
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>StatusDescription</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Decommissioned<br />- In service<br />- Installed<br />- Not in service<br />- Planned<br />- Temporary<br />- Under construction<br />- Unknown</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>toLocation</strong></td>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Anchor<br />- Anode Bed<br />- Big Bag/Gravel Bag<br />- Buoy (general)<br />- Buoy (midline)<br />- Cable Connection Module<br />- Clamp<br />- Clump Weight/Dead Man Anchor<br />- Compressor<br />- Concrete Block<br />- Counteract<br />- Cover<br />- CP Cabinet<br />- Crossing Position<br />- Distribution Unit<br />- Dynamic Platform<br />- El-substation/Power supply<br />- Equipment<br />- Facility<br />- Filter Unit Bag<br />- Flange<br />- Floating Unit - Ship<br />- Hang-off Position<br />- Hub Position<br />- J-tube<br />- Junction/Branch<br />- Living Quarter<br />- Loading Buoy<br />- Manifold<br />- Marker Bag<br />- Mattress<br />- On-shore Facility/Plant<br />- Other/Undefined<br />- Pile<br />- PLEM/PLET<br />- Riser Base<br />- Start/End/Tie-in Position<br />- Static Platform<br />- Storage Tank/Unit<br />- Structure<br />- Submerged Loading Buoy<br />- Subsea Current Buoy<br />- Substructure/Base<br />- Support Plate<br />- Template<br />- Touch Down Position<br />- Transponder<br />- Valve/Valve Station<br />- Wave Buoy Floater<br />- Well/Wellpad<br />- Wind Turbine</td>
    </tr>
  </tbody>
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
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Anchor<br />- Anchor Line<br />- Cable Connection Module<br />- Clamp<br />- Clump Weight<br />- Compressor<br />- Counteract<br />- Deck<br />- Distribution Unit<br />- Drilling Rig<br />- Dynamic Platform<br />- Equipment<br />- Facility<br />- Flange<br />- Floating Unit - Ship<br />- Junction/Branch<br />- Living Quarter<br />- Manifold<br />- Other/Undefined<br />- Platform/Rig bridge<br />- PLEM/PLET<br />- Riser Base<br />- Static Platform<br />- Structure<br />- Submerged Loading Buoy<br />- Substructure/Base<br />- Template<br />- Valve/Valve Station<br />- Well/Wellpad<br />- Wind Turbine<br />- Wire</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
CommonProperties

### Kodelister

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
      <td>Air Approach Zone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Anchor Zone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Anchoring and Fishing Prohibited</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Buoy Movement</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Contaminated Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Drill Cuttings/Disposal Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Exclusion Zone - Red</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Exclusion Zone - Yellow</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Loading Zone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Military Zone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>No Loading/Discharging</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Onshore Restricted Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Other/Undefined</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Pipeline Movement Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Plant Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Prohibited Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rig Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rig Handling Zone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Safety Zone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Seabed Caution Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Subsea Caution Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Surface Caution Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Target Box</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Temporary Surveillance Zone</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Wet Store Area</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Windfarm Area</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

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
      <td>Flowline</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gas</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Glycol</td>
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
      <td>Miscellaneous</td>
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
      <td>Power</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Riser</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Seismic</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Serviceline</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spool</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Umbilical</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Unknown</td>
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
      <td>mm</td>
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
      <td>Borehole</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cover</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Distribution Unit</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Equipment</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Facility</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mattress</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Other/Undefined</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Structure</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Substructure/Base</td>
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
      <td>Tunnel</td>
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
      <td>As laid/installed</td>
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
      <td>ST_ED50_WGS84_OffShore_GB_T1311</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>ST_ED50_WGS84_OnShore_Europe_T1133</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>ST_ED50_WGS84_S62_T1613</td>
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
      <td>Askeladd</td>
      <td></td>
      <td></td>
    </tr>
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
      <td>Midgard</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mikkel</td>
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
      <td>Asn Telecom</td>
      <td></td>
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
      <td>Bkk Nett As</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bord Gais</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Bp Exploration</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Britannia</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>British Gas</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>British Telecom International</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Burlington</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>C&amp;W Telecom</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cable &amp; Wireless</td>
      <td></td>
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
      <td>Ch4 Energy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Channel Islands Electricity Grid</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Chevrontexaco</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cnr International</td>
      <td></td>
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
      <td>Dana Pet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dangas/Rlk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dea</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Det Norske</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Deutsche Bundes Post Telecom</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Deutsche Telekom Ag</td>
      <td></td>
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
      <td>Esat Telecom</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Exxonmobil</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Farice Ltd</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flag Ltd</td>
      <td></td>
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
      <td>Gdf Suez</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Global Crossing Telecom</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Global Submarine Telecom</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Global Telesystems</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Great Northern Telegraph</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hamilton</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Haugaland Kraftlag</td>
      <td></td>
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
      <td>Kpn Telecom Bv</td>
      <td></td>
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
      <td>Manx Electricity Authority</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Marathon</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mci Telecom</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mærsk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nederlandse Aardolie Maatschappij Bv</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Netherlands Post,Telegraph,Telephone</td>
      <td></td>
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
      <td>Nordhordaland Kraftlag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Norsk Hydro</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Norske Shell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Northern Ireland Electricity</td>
      <td></td>
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
      <td>Petroleum Geo-Services</td>
      <td></td>
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
      <td>Shell UK E&amp;P</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Smedvig Petroservices</td>
      <td></td>
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
      <td>Sun Oil</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Tampnet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Telecom Danmark</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Telecom Fin/Swe/Nor/Den</td>
      <td></td>
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
      <td>Vsnl Telecoms</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vtl UK Ltd</td>
      <td></td>
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
      <td>In service</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Installed</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Not in service</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Planned</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Temporary</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Under construction</td>
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
      <td>Anode Bed</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Big Bag/Gravel Bag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Buoy (general)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Buoy (midline)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cable Connection Module</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Clamp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Clump Weight/Dead Man Anchor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Compressor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Concrete Block</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Counteract</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cover</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>CP Cabinet</td>
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
      <td>Dynamic Platform</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>El-substation/Power supply</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Equipment</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Facility</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Filter Unit Bag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flange</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Floating Unit - Ship</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hang-off Position</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Hub Position</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>J-tube</td>
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
      <td>Loading Buoy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Manifold</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Marker Bag</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mattress</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>On-shore Facility/Plant</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Other/Undefined</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Pile</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>PLEM/PLET</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Riser Base</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Start/End/Tie-in Position</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Static Platform</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Storage Tank/Unit</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Structure</td>
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
      <td>Substructure/Base</td>
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
      <td>Touch Down Position</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Transponder</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Valve/Valve Station</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Wave Buoy Floater</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Well/Wellpad</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Wind Turbine</td>
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
      <td>Anchor Line</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Cable Connection Module</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Clamp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Clump Weight</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Compressor</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Counteract</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Deck</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Distribution Unit</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Drilling Rig</td>
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
      <td>Facility</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Flange</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Floating Unit - Ship</td>
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
      <td>Platform/Rig bridge</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>PLEM/PLET</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Riser Base</td>
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
      <td>Wind Turbine</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Wire</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
