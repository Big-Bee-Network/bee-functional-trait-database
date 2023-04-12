## Bee Functional Trait Database

[```Functional Traits```](#functional-traits) / [```Contribute```](#contribute) / [```Data Definitions```](#data-definitions) / [```Citation```](#citation) / [```Acknowledgements```](#acknowledgements)

The Bee Functional Trait Database is a repository for bee functional trait data, including data on morphological, physiological, ecological, and behavioral traits. Observations are sourced from the literature and from preserved museum specimens.

### Functional Traits

* **Social Organization**:
* **Nesting Biology**:
* **Diet Breadth**
* **Body Size**:
<br/>[GitHub repository](https://github.com/Big-Bee-Network/bee-body-size)
* **Thermal Tolerance**:
* **Desiccation Resistance**:
* **Phenology**:
* **Biotic Associations**:
<br/>[GitHub repository](https://github.com/Big-Bee-Network/global-bee-interaction-data)<br/>[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6564718.svg)](https://doi.org/10.5281/zenodo.6564718)
* **Pilosity**:

### Contribute
To contribute a new dataset, please [open an issue here](https://github.com/Big-Bee-Network/bee-functional-trait-database/issues/new) and provide a link to the dataset and how you would like your dataset cited.

### Data Definitions

The definitions of the columns used in the functional trait dataset are described here. If these correspond with Darwin Core they are mapped to those classes. 
  * **basisOfRecord**: [DWC:BasisOfRecord](http://rs.tdwg.org/dwc/terms/basisOfRecord) The specific nature of the data record (character). Eligible values include: ```preserved specimen```, ```literature record```, or ```ocurrence record```.
  * **specimenCatalocNumber**: The catalog number of the specimen (character and numeric).
  * **specimenCatalocNumber**: The biological level to which the trait data refers (character). Eligible values include: ```individual```, ```species```, ```population```, or ```colony```.
  * **acceptedTaxonName**: [DWC:acceptedNameUsage](http://rs.tdwg.org/dwc/terms/acceptedNameUsage) The full name, with authorship and date information if known, of the currently valid taxon (character).
  * **acceptedTaxonName**: [DWC:acceptedNameUsageID](http://rs.tdwg.org/dwc/terms/acceptedNameUsageID) An identifier for the name usage (documented meaning of the name according to a source) of the currently valid taxon (character.
  * **traitName**: The relevant functional trait (character). Eligible values include: ```social organization```, ```nesting biology```, ```diet breadth```, ```body size```, ```thermal tolerance```,```desiccation resistance```,```phenology```,```biotic associations```,or ```pilosity```.
  * **traitDataType**: The class of functional trait data recorded (character). Eligible values include: ```integer```, ```real number```, or ```character```.
  * **traitDataType**: The unit of measurement of the data (character). Examples include: ```mm```,```deg C```,```hours```, or ```NA``` for character data.
  * **value** The value of the trait measurement (real number, integer, or character). Examples include: ```14```,```22.534```, ```eusocial``` or ```stem nesting```
  * **valueMeasure**: The type of value represented in the "value" column (character). Eligible values include: ```single observation```, ```mean```,```median```,```min```, ```max```,or ```description```.
  * **variance**: A measure in the variance of the value measurement, if applicable, typically for reported mean values (real number). 
  * **varianceMeasure**: The type of value represented in the "variance" column, if applicable (character).  Examples include: ```std dev```, or ```std error```.
  * **sampleSize**: The relevant sample size used for the value measure, if applicable (integer). Typically applies for reported mean values.
  * **treatment**: The experimental treatment group relevant to the value measure, if applicable (character).
  * **methodName**: The name of the method used to measure the trait (character). Examples include: ```CTmax```, ```mark-recapture```, or ```ITS measurement```.
  * **methodDescription**: A short description of the methods used (character). For example: "Intertegular measurements taken from images using ImageJ".
  * **note**: Any relevant information not included in the above categories, if applicable (character).
  * **study**: A unique name referring to the study in which the data were collected, likely uniting multiple lines of entered data (character). This entry is particularly useful for uniting datasets not yet published. For example: "Ostwald Thermal Tolerance 2022".
  * **reference**: A formatted citation for the reference including the relevant data, if applicable (character). APA citation format preferred. For example: "Hamblin, A. L., Youngsteadt, E., Lopez-Uribe, M. M., & Frank, S. D. (2017). Physiological thermal limits predict differential responses of bees to urban heat-island effects. Biology Letters, 13, 0125."
  * **referenceDOI**: The digital object identifier (DOI) of the above reference, if applicable (character).

## Citation
  
## Acknowledgements
The following organizations and projects that made this work and tutorial possible:
[NSF](https://nsf.gov) for their support and funding of [Big-Bee](https://www.idigbio.org/wiki/index.php?title=TCN:_Extending_Anthophila_research_through_image_and_trait_digitization_(Big-Bee)&mobileaction=toggle_view_desktop), Extending Anthophila research through image and trait digitilization. ([NSF:DBI:2102006](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2102006&HistoricalAwards=false))

<a href="https://www.idigbio.org/wiki/index.php?title=TCN:_Extending_Anthophila_research_through_image_and_trait_digitization_(Big-Bee)&mobileaction=toggle_view_desktop"><img src="https://www.idigbio.org/wiki/images/8/84/Big-Bee-logo-2022.png" class="inline-image" style="height: 6em;"></a>
<a href="https://nsf.gov"><img src="https://big-bee.ccber.ucsb.edu/images/NSF_4-Color_bitmap_Logo-small.png" class="inline-image" style="height: 6em;"></a> 
