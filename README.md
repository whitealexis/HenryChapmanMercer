<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Girl with a Pearl Earring"
       author="JSTOR Labs team"
       banner="https://iiif.juncture-digital.org/banner/?url="{"@context": "http://iiif.io/api/presentation/2/context.json", "@id": "https://www.loc.gov/item/2011633553/manifest.json", "@type": "sc:Manifest", "attribution": "Provided by the Library of Congress", "description": "1 transparency : color ; 4 x 5 in. or smaller.", "label": "Moravian Pottery and Tile works, opened in 1912 on the estate of Henry Chapman, Doylestown, Pennsylvania", "logo": "https://loc.gov/static/images/logo-loc-new-branding.svg", "metadata": [{"label": "APA Citation Style", "value": "Highsmith, C. M., photographer. <cite>Moravian Pottery and Tile works, opened inon the estate of Henry Chapman, Doylestown, Pennsylvania</cite>. Pennsylvania United States Doylestown, None. [Between 1980 and 2006] [Photograph] Retrieved from the Library of Congress, https://www.loc.gov/item/2011633553/."}, {"label": "MLA Citation Style", "value": "Highsmith, Carol M, photographer. <cite>Moravian Pottery and Tile works, opened inon the estate of Henry Chapman, Doylestown, Pennsylvania</cite>. [Between 1980 and 2006] Photograph. Retrieved from the Library of Congress, &lt;www.loc.gov/item/2011633553/&gt;."}, {"label": "Chicago Citation Style", "value": "Highsmith, Carol M, photographer. <cite>Moravian Pottery and Tile works, opened inon the estate of Henry Chapman, Doylestown, Pennsylvania</cite>. Pennsylvania United States Doylestown, None. [Between 1980 and 2006] Photograph. https://www.loc.gov/item/2011633553/."}, {"label": "Contributors", "value": ["Highsmith, Carol M., 1946-, photographer"]}, {"label": "Created Published", "value": ["[between 1980 and 2006]"]}, {"label": "Original Format", "value": ["photo, print, drawing"]}, {"label": "Subjects", "value": ["henry chapman", "pennsylvania", "transparencies", "doylestown", "united states", "color", "moravian pottery and tile works", "america", "graumann's chinese theater"]}, {"label": "Online Format", "value": ["image"]}, {"label": "Item Url", "value": "https://www.loc.gov/item/2011633553/"}], "navDate": "1980-01-01:T00:00:00Z", "seeAlso": [{"@id": "https://lccn.loc.gov/2011633553/marcxml", "format": "text/xml"}, {"@id": "https://lccn.loc.gov/2011633553/mods", "format": "text/xml"}, {"@id": "https://lccn.loc.gov/2011633553/dc", "format": "text/html"}], "sequences": [{"@type": "sc:Sequence", "canvases": [{"@id": "https://tile.loc.gov/image-services/iiif/service:pnp:highsm:15300:15360", "@type": "sc:Canvas", "height": 1645, "images": [{"@id": "https://www.loc.gov/resource/highsm.15360/seq-1/", "@type": "oa:Annotation", "motivation": "sc:painting", "on": "https://tile.loc.gov/image-services/iiif/service:pnp:highsm:15300:15360", "resource": {"@id": "https://tile.loc.gov/image-services/iiif/service:pnp:highsm:15300:15360/full/pct:25/0/default.jpg", "@type": "dctypes:Image", "format": "image/jpeg", "height": 1645, "service": {"@context": "http://iiif.io/api/image/2/context.json", "@id": "https://tile.loc.gov/image-services/iiif/service:pnp:highsm:15300:15360", "profile": "http://iiif.io/api/image/2/level2.json"}, "width": 1286}}], "label": "Page 1", "metadata": [{"label": "Library of Congress Resource URL", "value": "https://www.loc.gov/resource/highsm.15360/?sp=1"}], "related": "https://www.loc.gov/resource/highsm.15360/?sp=1", "service": {"@context": "http://iiif.io/api/image/2/context.json", "@id": "https://tile.loc.gov/image-services/iiif/service:pnp:highsm:15300:15360", "profile": "http://iiif.io/api/image/2/level2.json"}, "thumbnail": {"@id": "https://tile.loc.gov/image-services/iiif/service:pnp:highsm:15300:15360/full/pct:6.25/0/default.jpg", "format": "image/jpeg", "height": 411, "width": 321}, "width": 1286}], "label": "Order of the views"}], "thumbnail": {"@id": "https://tile.loc.gov/storage-services/service/pnp/highsm/15300/15360_150px.jpg"}, "viewingDirection": "left-to-right", "viewingHint": "paged"}" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">

# Basic usage

## Image

_Girl with a Pearl Earring_ (Dutch: Meisje met de parel) is an oil painting by Dutch Golden Age painter Johannes Vermeer, 
dated c. 1665. Going by various names over the centuries, it became known by its present title towards the end of the 
20th century after the earring worn by the girl portrayed there.[^1]
<param ve-image 
       label="Girl with a Pearl Earring" 
       description="painting by Johannes Vermeer" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/0/0f/1665_Girl_with_a_Pearl_Earring.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Wikipedia: Girl with a Pearl Earring](https://en.wikipedia.org/wiki/Girl_with_a_Pearl_Earring)
