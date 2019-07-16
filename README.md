# RDA Classes Vocabulary
This vocabulary consists of a list of 'Classes' which are functions of government associated with Commonwealth Agencies as defined in Agency's Records Disposal Authorities.

The [RDA Ontology](http://linked.data.gov.au/def/rda) defines `rda:Class` and its relation to other ojects not in this vocabulary, such as `rda:NumberdSubclass`. Additionally, an `rda:Class` is a subClassOf the [CRS Ontology](http://linked.data.gov.au/def/crs)'s `crs:Function` which means `rda:Class` instnaces can be associated with `crs:CommonwealthAgency` instances, as they are here.

Data in this repository is a formulation of several table's worth of data from the [National Archives of Australia](http://www.naa.gov.au)'s *Commonwealth Record Series* database and this data was extracted and processes for the [Longitudinal Spine of Government Functions](https://longspine.cat) project. The data is formatted in [RDF](https://www.w3.org/RDF/)'s [Turtle serialisation](https://www.w3.org/TR/turtle/).

The persistent URI for this vocabulary is:

* **<http://test.linked.data.gov.au/dataset/rdavoc>**


## Vocabulary content
* [rda-functions.ttl](data/rda-functions.ttl) - Records Disposal Authority's Functions in RDF (turtle) formulated according to [SKOS](https://www.w3.org/TR/skos-reference/) with some CRS ontology additions

The [source/](source/) folder contains raw data from the CRS database (in Excel) and intermediate files and scripts used to process it to created the files listed above.


## Rights and License
All the contents of this repository are derived from NAA source data and thus the rights to that data reside with the NAA.

All work done on the NAA data for its presentation here was undertaken by [CSIRO](https://www.csiro.au).


## Contacts
Creator:  
**Nicholas Car**  
*Senior Experimental Scientist*  
CSIRO Land & Water, Brisbane, Australia  
<nicholas.car@csiro.au>  
<http://orcid.org/0000-0002-8742-7730>  

Data provisioning:  
**National Archives of Australia**  
