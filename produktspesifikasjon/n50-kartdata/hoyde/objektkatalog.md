### Datamodell

<a href="hoyde_feature_catalogue.png" title="Klikk for stor visning"><img src="hoyde_feature_catalogue.png" alt="Datamodell Hoyde" style="max-width: 100%; height: auto;" /></a>

#### Terrengpunkt

punkt i terrenget med målt høydeverdi som brukes for å angi høyde på markerte flater i terrenget som for eksempel sadler og store flater, i veg- og gatekryss og andre kryss mellom samferdselslinjer, på gårdsplasser utenfor hovedinnganger og på parkeringsplasser<br /><br /><br />-- Definition --<br />point in the terrain with a measured height value used to indicate the height on pronounced surfaces in the terrain, such as saddles and large surfaces, in road and street intersections and other intersections between transportation lines, in courtyards outside main entrances and in car parks

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
      <td>angivelse av punktets høyde, og oppgis som et desimalt tall hvis nødvendig<br /><br />-- Definition --<br />indication of the height of the point, to be given with decimals if necessary</td>
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

#### Forsenkningskurve

linje i terrenget med fast høydeverdi (z-verdi) som beskriver en forsenkning i terrenget<br /><br />Merknad: Alle kurver som beskriver en forsenkning skal kodes som forsenkningskurver- ikke bare den nederste kurven.<br /><br /><br />-- Definition --<br />line in the terrain with a fixed height value (z value) which describes a depression in the terrain

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
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir forsenkningskurvens  høyde over høydereferansen i meter- og oppgis som et desimalt tall hvis nødvendig<br /><br />-- Definition --<br />indicates the depression curve's height above the height reference in metres - to given with decimals if necessary</td>
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

#### Høydekurve

linje i terrenget med fast høydeverdi (z-verdi) over referansehøyden<br /><br />Merknad: Høydekurver skal ikke krysse hverandre, bortsett fra der dette er tilfelle (overheng).<br /><br /><br />-- Definition --<br />line in the terrain with a fixed height value (z value) above the reference height

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
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av høydekurvens høyde over høydereferansen i meter- og oppgis som et desimalt tall hvis nødvendig<br /><br />-- Definition --<br />indication of the depression curve's height above the height reference in metres - to be given with decimals if necessary</td>
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

#### Hjelpekurve

linje som følger terrenget med fast høydeverdi (z-verdi) og som brukes for bedre å beskrive terrenget mellom de vanlige høydekurvene<br /><br />Merknad: Tidligere kalt mellomkurve<br /><br /><br />-- Definition --<br />line which follows the terrain with a fixed height value (z value), and which is used to provide a better description of the terrain between the ordinary ??(contour lines / height contours)

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
      <td><strong>høyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angivelse av hjelpekurvens høyde over høydereferansen i meter- og oppgis som et desimalt tall hvis nødvendig<br /><br />-- Definition --<br />indication of the auxiliary curve's height above the height reference in metres - to be given with decimals if necessary</td>
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

#### TrigonometriskPunkt

varig merket punkt, markert med bolt eller annet merke, der plane koordinater og høyde er bestemt i et trigonometrisk nett, i et geodetisk system<br /><br /><br />-- Definition --<br />permanently marked point, marked with a bolt or other mark in which the plane coordinates and/or height are determined in a Trigonometrical network in a geodetic system

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
      <td>angivelse av punktets høyde, og oppgis som et desimalt tall hvis nødvendig<br /><br />-- Definition --<br />indication of the height of the point, to be given with decimals if necessary</td>
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
