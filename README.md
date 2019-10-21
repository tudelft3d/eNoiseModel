## eNoise Model
eNoise Model is the data model for standardising the input/output data for noise simulations using CNOSSOS-EU in the EU.
It is developed as an extension to the international 3D GIS standard [CityGML](http://www.opengeospatial.org/standards/citygml).
It integrates concepts from the CNOSSOS-EU, the geluidregister, the INSPIRE, Dutch IM Geluid and the existing CityGML Noise ADE.

Things to know
---------------

### CNOSSOS-EU
CNOSSOS-EU represents a harmonized method to assess noise levels from the main 80 sources of noise (road traffic, railway traffic, aircraft and industries) across the EU and should replace national models for the next round of strategic noise mapping (2021/2022).
In 2015, an update to the END Annex II was published, it requires all the EU Member States to use CNOSSOS-EU from 31 December 2018 onwards.

### CityGML
The CityGML is an XML based data model for the storage and exchange of virtual 3D city models. It is implemented an application schema of GML3 [Geography Markup Language version 3.1.1 (GML3)](http://www.opengeospatial.org/standards/gml). The data model of CityGML comprises of a core module and several thematic extension modules like Building, Relief, Bridge, LandUse, Tunnel, Transportation, Vegetation, WaterBody, etc for representing 3D city models.
CityGML has the concept of ADEs (Application Domain Extensions) to extend its schema with new classes and objects which are not explicitly modelled in the existing CityGML modules.

Resources
---------------

- The [UML model](https://github.com/tudelft3d/eNoiseModel/blob/master/DataModel/UML/CityGML_eNoise_ADE_v01.eap) of the eNoise ADE was created using Enterprise Architect.
- The [XML Schema file](https://github.com/tudelft3d/eNoiseModel/blob/master/DataModel/XSD/CityGML_eNoiseADE.xsd) of the eNoise ADE were derived automatically from the UML model using [ShapeChange](http://shapechange.net/).
- The input data used in the research is part of the project [Automated reconstruction of 3D input data for noise studies](https://3d.bk.tudelft.nl/projects/noise3d/) and is available [here]( https://3d.bk.tudelft.nl/opendata/noise3d/en.html).
- The data for the roads and the noise barriers is available at the [geluidregister](https://www.rijkswaterstaat.nl/kaarten/geluidregister.aspx).
