# Glass-Diapositives-Egyptology-Dataset
Full dataset from the collection of glass diapositives Egyptology offered as open data for digital humanities research and other creative engagement. 
## KU Leuven Libraries on Github 
Read [here](https://github.com/KU-Leuven-Libraries/Welcome-to-KU-Libraries-OpenGLAM/blob/master/README.md) a brief introduction of KU Leuven Libraries on GitHub

## Glass diapositives Egyptology
The collection of glass diapositives Egyptology of KU Leuven Libraries consists of approximately 3500 slides, which are currently stored at 2Bergen Campus Arenberg. Within this collection, there is huge variety in the themes that are depicted, ranging from daily life and travel photography, educational slides with views of monuments and museum artifacts to slides depicting ongoing excavations such as those at the ancient sites of Medamud and El-Tod at the beginning of the twentieth century. Little information is known on the origin of the collection or the age of the slides, although they were surely used to teach Egyptology at KU Leuven well into the seventies. The glass diapositives were digitized and described as part of the [EuropeanaPhotography](https://pro.europeana.eu/project/europeanaphotography) project with digitisation being completed in two batches, the first one performed between January 2014 and 2016 and the second one between April 2020 and June 2021.

## Glass diapositives Egyptology dataset 
The glass diapositives Egyptology dataset is a repository of descriptive metadata of all the glass slides depicting Egypt or related to the subject of Egyptology from KU Leuven Libraries. The collection can be explored through the [Libraries’ Curated Collections](https://limo.libis.be/primo-explore/collectionDiscovery?vid=KULeuven&collectionId=81386064490001488&lang=en_US) discovery interface, within the thematic collection [“Photography”](https://limo.libis.be/primo-explore/collectionDiscovery?vid=KULeuven&collectionId=81475525920001488&lang=en_US). As part of a Digital Humanities internship at the department of Digitisation of KU Leuven Libraries, a selection of glass slides depicting the excavations at El-Tod and Medamud and their associated metadata were pushed to both [Wikidata](https://www.wikidata.org/wiki/Q112958007) and [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Glass_diapositives_Egyptology,_KU_Leuven_Libraries), making them consultable on these platforms as well. 

## Who can use it
The repository is designated as a free resource for digital humanities research, for scholars, students and teachers. It also is intended for creative reuse.

## Provenance 
The dataset is fully based on the library catalog metadata, which follows the MARC21 Format for Bibliographic data. It consists of descriptive metadata and URLs to the digital representation on PRIMO, the search interface of KU Leuven Libraries. The unprocessed data was downloaded as a MARCXML file from the ALMA digital preservation environment and converted into a CSV and XLSX file using the MarcEdit tool. Data cleaning and enrichment were performed using OpenRefine, ExifTool, and Jupyter Notebooks, the results of which will be published [here](10.5281/zenodo.6993205). The raw dataset can be found in the current repository as a XLSX file. 

## Technical aspects
The XLSX file consists of 3485 records and twenty-four columns. For a correct download click on the [glass-diapositives-egyptology-metadata](https://github.com/KU-Leuven-Libraries/Glass-Diapositives-Egyptology-Dataset/blob/main/glass-diapositives-egyptology-metadata.xlsx) and then right-click on 'Download' selecting 'Save link as'. The XLSX file can also be downloaded from [Zenodo](http://doi.org/10.5281/zenodo.6907228). To correctly display the contents of the XLSX file, it is advised that Libre Office, Microsoft Excel or Google Spreadsheets is used. As the descriptive metadata follows the MARC21 standard, the header will consist of the related field tags. 

The XLSX file contains the following metadata:
| Column | Content Type | MARC21 field tag and description | Instance 
|--|--|--|--|
| 1 | Leader | Field 000: Leader with g (position 6) for type of record (projected medium) and m (position 7) for bibliographic level (monograph/item) |  01695ngm a2200373 u 4500
| 2 | Record ID | Field 001: Control number | 9992119903601488
| 3 | Timestamp | Field 005: Date and Time of Latest Transaction | 20220322152459.0
| 4 | Background information: date and material type | Field 008: General information with position 6-14 indicating type of date(s) and position 33 indicating type of visual material (slide) | 141016s\\\\\\\\xx\\\\\\r\\\\\000\s\und\d
| 5 | System control number | Field 035: System Control Number $a System control number | \\$a(BeLVLBS)9992159258801471 A
| 6 | Cataloging source | Field 040: Cataloging Source - fixed value $a Original cataloging agency $b Language of cataloging $e description conventions | \\$aBeLVLBS$bLanguage of cataloging varies$erda based
| 7 | Main title | Field 245: $a Title Statement $b Remainder of Title Statement | 00$aBawit. Klooster van de Heilige Apollo$bArchivolt met plantaardig motief in reliëf
| 8 | Varying title(s) | Field 246: 1$$a and 1$$b: Impressum 13$a Varying Form of  title 33$a Fixed Value (Europeana Photography 2Bergen glasdia’s. Collectie Egyptologie) | 13$aBaouit;33$aEuropeana Photography 2Bergen glasdia's. Collectie Egyptologie
| 9 | Manufacturer | Field 264: $a Place of manufacture $b Name of manufacturer | $aParis $bProjections Molteni
| 10 | Physical extent | Field 300: Description of physical object $a Extent $b Other physical details $c Dimensions | \\$a1 glasdia$b100 x 85 mm
| 11| Content type | Field 336:  Content type - Fixed value $a Content type term $2 Source | \\$astill image$2rdacontent
| 12 | Media type | Field 337: Media type - Fixed value $a Media type term $2 Source | \\$aprojected$2rdamedia
| 13 | Carrier type | Field 338: Carrier type - Fixed value $a Carrier type term $2 Source | \\$aslide$2rdacarrier
| 14 | Description of physical material | Field 340: Physical medium - Fixed value $a Material base and configuration | \\$aSlide
| 15 | Series title | Field 490: Series statement 1 Series traced $a Series statement | 1\$aKU Leuven. Glasdia's landschap, architectuur en vormgeving. Université de Louvain, tussen 1839 en 1939
| 16 | General notes | Field 500: General note $a General note - multiple values for same tag which are separated by ; - fixed values: ‘toegevoegde informatie op dia’ and ‘fotograaf onbekend’ | \\$aFotograaf onbekend;\\$aToegevoegde informatie op dia;\\$aCreator unknown
| 17 | Copyright status | Field 542: Information Relating to Copyright Status - fixed value $l Copyright Status $n Note $u Uniform Resource Identifier | \\$lpublic domain$navailable as open data$ugebruiksvoorwaarden
| 18 | Notes | Field 545: Biographical or Historical Data $a Biographical or historical data - multiple values for same tag which are separated by ; . 5 Notes exist for this collection: (1) Stroming/stijl (Art movement/style) (2) Oorspronkelijke locatie/vindplaats (original (find) location) (3) Creatie/bouw (creation/construction) (4) Techniek/materiaal (technique/material) (5) Huidige locatie (current location) | \\$aHuidige locatie: France, Paris, Musée du Louvre;\\$aOorspronkelijke locatie: Egypte, Bawit, Klooster van de Heilige Apollo
| 19 | Series added entry | Field 830: Series Added Entry - Uniform Title $a Uniform title - multiple values for same tag which are separated by ; | \\$aEuroPhot. Kunstgeschiedenis. Periode onbekend. Beeldhouwkunst. Reliëf;\\$aEuroPhot. Art history. Period unknown. Sculptures. Relief;\\$aEuroPhot. Kunstgeschiedenis. Periode onbekend. Architectuur. Architecturaal element;\\$aEuroPhot. Art history. Period unknown. Architecture. Architectural element
| 20 | URL and physical location glass slide | Field 856: Electronic Location and Access - Direct URL to image viewer 4 HTTP (Hypertext Transfer Protocol) $u Uniform Resource Identifier $y Link text | 4\$uhttp://resolver.libis.be/IE2842287/representation$yKU Leuven Libraries WBIB WMAG PRECA GDE000794/box 007
| 21 | Fixed value | Field 902: Local tag | \\$rSLIDE$mPHYSICAL
| 22 | Shape designation | Field 950: Shape designation - fixed value | \\$bglass slide(s)
| 23 | Fixed value | Field 981: Equivalence or Cross-Reference Series Statement Corporate Name/Title | \\$aDigital title KU Leuven Libraries
| 24 | Fixed value | Field 996: Local tag | \\$aWBIB$bphysical$c202010$dinvoer_project_Europeana_Photography$9local

## Cite this dataset 
When referring to or using this dataset in research publications and documentation, consider citing the repository with its [Zenodo DOI](https://doi.org/10.5281/zenodo.6907228)
 (digital object identifier).Citation of the glass diapositives Egyptology dataset creates a mapping of attribution and this way supports the libraries’ efforts to release other datasets in the future. It further limits the amount of orphan data as it secures source links. Cite the repository as: KU Leuven Libraries, Digitisation Department. (2022). Glass diapositives Egyptology, KU Leuven Libraries [Data set]. Zenodo. http://doi.org/10.5281/zenodo.6907228.

## License 
The glass diapositives Egyptology dataset is licensed under a [Public Domain Mark](https://creativecommons.org/share-your-work/public-domain/pdm/) (PDM), which means that the dataset is copyrighted but dedicated to the public domain by the copyright holder. This way, it can be freely used by anyone. KU Leuven Libraries follows an open images policy that allows its public domain digitised heritage collections to be freely copied, modified, distributed and reused, only by mentioning “KU Leuven. [Name of the collection]” without asking for further permission. For a detailed view of the library’s terms of service see: https://bib.kuleuven.be/BD/digitalisering-en-document-delivery/digitalisering/gebruiksvoorwaarden

## Code of conduct 
The GitHub repository of the Digitisation Department of KU Leuven Libraries follows the [Contributor Covenant](https://www.contributor-covenant.org) as a way to be overt in its openness, welcoming all people to engage and contribute, pledging in return to value them. In order to make our open communities welcoming, diverse and inclusive, we are encouraging the adaptation of a mindful code of conduct as a means to express and share those values. Any unacceptable behavior such as trolling, insulting/derogatory comments, personal or political attacks will not be tolerated. The Contributor Covenant is released under the Creative Commons Attribution 4.0 International Public License.

## Project Attribution 
[KU Leuven Libraries ](https://bib.kuleuven.be/english)
* Nele Gabriëls: Digitisation Department (project supervisor)
* Hendrik Hameeuw: Digitisation Department (project supervisor)
* Demmy Verbeke: Head of Artes (project advisor)
* Laura Narli: Metadata Services and Acquisitions
* Mark Verbrugge: Digitisation Department 

[Advanced MSc in Digital Humanities, KU Leuven](https://set.kuleuven.be/onderwijs/mdh) 
* Luna Beerden: Research and Traineeship, thesis project

## Contributors 
This project follows the [all-contributors](https://allcontributors.org) specification. KU Leuven Libraries recognises contributions and engagement for its open data repository through [emoji key](https://allcontributors.org/docs/en/emoji-key)✨, in a way to reward every contribution, not only code. Contributions of any kind like questions, ideas, link to videos, translations and many more will be automatically acknowledged through the all-contributors bot 🤖.

KU Leuven Libraries would like to thank the following contributors (emoji key):

