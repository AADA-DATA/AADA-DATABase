Archaeological Artefact Database of Finland (AADA) 

Cite this data as: 
Pesonen, P., Moilanen, U., Roose, M., Saipio, J., Tiilikkala, J., Sanwal, M. U., Immonen, V., Vesakoski, O. & Onkamo, P. . Archaeological Artefact Database of Finland (AADA).

Dataset download of latest releases and descriptions 
Zenodo: https://zenodo.org/records/10437704

Dataset repository for versioning and maintenance
Github: https://github.com/AADA-DATA/AADA-DATABase (private for now)

Format
XSLX, CSV

The data collection is described in Pesonen et al. (resubmitted ms).


General structure of the data 

The AADA dataset is thematically organised into three subset of data according to the chronological periods. Each row in the dataset represents a single artefact.

●	Stone Age: Contains separate tables for pottery, stone tools, clay artefacts, bone artefacts, wooden artefacts, amber, and birch bark tar.
●	Bronze Age: Contains separate tables for pottery, stone tools, clay artefacts, bone artefacts, wooden artefacts, and bronze objects.
●	Iron Age: Contains separate tables for pottery, stone tools, clay artefacts, bone artefacts, wooden artefacts, bronze artefacts, iron artefacts, silver and golden artefacts, beads, and organic materials. Also includes detailed tables of pottery and stone tools with subperiod-specific dating.

Each row in the dataset represents a single artefact, while each column represents a specific attribute, such as its type, period, site, and measurements. Moreover, each subset contains spreadsheets based on artefact type. For example, for the Stone Age period, there are separate tables for pottery, stone tools, clay artefacts, bone artefacts, wooden artefacts, amber, and birch bark tar. Similarly, for the Bronze Age period, there are separate tables for pottery, stone tools, clay artefacts, bone artefacts, wooden artefacts, and bronze objects. For the Iron Age period, there are separate tables for pottery, stone tools, clay artefacts, bone artefacts, wooden artefacts, bronze artefacts, iron artefacts, silver and golden artefacts, beads, and organic materials. In addition, due to chronological period dependent recording procedures, the Iron Age table also contains a detailed table of pottery and stone tools (where e.g., the dating is specified according to Iron Age subperiods).

Pottery tables differ from other artefact tables, where each row denotes the presence of a pottery within a specific collection number. The presence does not record how many vessels etc. there are in the collection number. Quantity is expressed in "count" columns.


Titles of the columns 
General and spatial information
The AADA dataset contains primary information on archaeological artefacts from different prominent institutions across Finland, such as the National Museum of Finland, Ålands Museum, and Turku Museum Centre, among others. These artefacts are organised using a main number and sub-number system. Additionally, the dataset includes information on the municipality. Overall, the primary information contained in the AADA dataset serves as a starting point while querying data.

Collection contains source information of 32 museums:  KM = Kansallismuseo (National Museum of Finland); ÅM = Ålands Museum; TYA = Turun Yliopisto Arkeologia (University of Turku, Archaeology); TMM = Turun museokeskus (Turku Museum Centre; current signum is TMK but dataset uses TMM); SatM = Satakunnan Museo (Museum of Satakunta); KHMESIE = Kuopion kulttuurihistoriallinen museo (Kuopio Cultural History Museum ; EKM = Etelä-Karjalan museo (Museum of South Karelia) ; BM = Porvoon Museo (Porvoo Museum,sw. Borgå Museum); HM = Hämeen museo (Häme Museum, in Museum Centre Vapriikki, Tampere); Hal = Halikon museo (Halikko Museum, part of Salo Historical Museum); Per = Perniön museo (Perniö Museum, part of Salo Historical Museum); Linder = Linder collections in Turku Museum Centre; Nyberg = Nyberg collections in EKTA Museum Raasepori; SII = Pöljän kotiseutumuseo (curated by Kuopio Cultural History Museum); KARTT/VI = Karttulan kotiseutumuseo (curated by Kuopio Cultural History Museum); KIUR = Kiuruveden museo (Kiuruvesi Museum, curated by Kuopio Cultural History Museum); Lauri Nautela kok = Lauri Nautela Museum, Lieto; SHH = Stockholm Historiska Museet, Sweden.

Main numbers and Sub-numbers organise collections, e.g., KM 12456:1–25, where KM indicates the National Museum of Finland’s collection with the main number 12456, which has sub-numbers 1 to 25. Main number is a diary accession number for any single delivery of artefacts in the collections, e.g., an excavation of a site etc. Subnumbers point to separate find contexts within the act.
Municipality. The municipality categorises archaeological artefacts by their place of origin municipality-wise. The dataset reflects the situation as of 2020, although several municipalities have since merged. Old parish names are used for the ceded Karelia and other areas (prior 1945). 
Site id  and Site name. Identification number and name of the find location sites in accordance with the Register of Archaeological Sites curated by the Finnish Heritage Agency. 
Phase. Information on the chronological period of the artefact, with SA denoting the Stone Age (8900-1900 calBC), BA representing the Bronze Age (1900-500 calBC), and IA indicating the Iron Age (500 calBC-1300 calAD).
Coordinates (p/i/z). Two  coordinate reference systems are provided:  World Geodetic System (version WGS 84)  and KKJ / Finland Uniform Coordinate System", with the EPSG identifier 2393 (https://epsg.io/2393).
p	Coordinate northing ”pohjoinen” (in Finnish), KKJ / Finland Uniform Coordinate System, EPSG2393
i	Coordinate easting ”itä” (in Finnish), KKJ / Finland Uniform Coordinate System, EPSG2393
z	Elevation above the site above sea level in meters (m)
X	Coordinate latitude, WGS84.
Y	Coordinate longitude, WGS84.

Temporal information
Period/dating. The dating of the artefacts in the AADA dataset varies according to material. In most tables (pottery, stone tools, clay, bronze, iron, beads) the dating is based on the typology of the artefacts. In some tables, other datable finds from the same site are used as dating criteria, i.e., thus providing a wider range of dating options for the object, including materials such as amber, bone, birch bark, and wood. The periodization for Late Iron Age differs in western, eastern, and northern Finland. Late Iron Age is generally extended to at least c. 1300 AD in eastern Finland and Karelia, and occasionally even longer in northern Finland. The abbreviations are the following:
Mon1	Montelius period 1.
Mon2	Montelius period 2.
Mon3	Montelius period 3.
Mon4	Montelius period 4.
Mon5	Montelius period 5.
Mon6	Montelius period 6.
m1	Early Mesolithic: 8900–8200 BC (10900–10200 calBP)
m1	Early Mesolithic: 8900–8200 BC (10900–10200 calBP)
m2	Middle Mesolithic: 8200–6200 BC (10200–8200 calBP)
m3	Late Mesolithic: 6200–5100 BC (8200–7100 calBP)
n1	Early Neolithic: 5100–3900 BC (7100–5900 calBP)
n2	Middle Neolithic: 3900–2900 BC (5900–4900 calBP)
n3	Late Neolithic: 2900–2400 BC (4900–4400 calBP)
n4	Final Neolithic: 2400–1700 BC (4400–3700 calBP)
p1	Early Bronze Age (Montelian period I-III): 1700–1100 BC (3700–3100 calBP)
p2	Late Bronze Age (Montelian period IV-VI): 1100–500 BC (3100–2500 calBP)
r1	Early Iron Age (Pre-Roman Iron Age and Early/Late Roman Iron Age): 500 BC–400 AD (2500–1600 calBP)
r2	Late Iron Age (Merovingian Period to Medieval Period): 600–1530 AD (1400–470 calBP)
Preroman IA	Pre-Roman Iron Age period:500-1 BC
Early Roman IA	Early Roman Iron Age period 0-200 AD
Late Roman IA	Late Roman Iron Age period: 200-400 AD
Migration period	Migration period: 400-600 AD
Merovingian period	Merovingian period: 600-800 AD
Viking period	Viking period: 800-1050 AD
Crusade period	Crusade period: 1050-1150/1300 AD
1100-1300	Period from 1100 to 1300 AD.
1400-1500	Period from 1400 to 1500 AD.
Typological information
Typology (category, types, subtypes). The artefacts in the dataset are organized hierarchically by typology, which includes category, type, and subtype. For example, the category of Stone Age bark floats is "wooden artefact," the type is "fishing implements," and the subtype is "bark float." In some cases, such as Stone Age stone tools, there is also a lower subtype hierarchy  (subtype 2). In addition, the Finnish terms for subtype (and subtype 2) are presented as well. The columns describing the typology of the artefacts are

Category	The hierarchical category of artefacts (e.g., "Bronze artefacts").
Type	The hierarchical type of artefacts (e.g., " Bronze axe").
Type (Finnish)	Type of artefact, currently in Finnish
Subtype	The hierarchical subtype of artefacts (e.g., "Palstave").
Subtype (Finnish)	The hierarchical subtype of artefacts in Finnish (e.g., “Olkakirves”).
Certainty	Subjective identification of artefact type (1: certain, 2: probable, 3: possible).
Main temper (Finnish)	Main temper of pottery, currently in Finnish. Not to be taken as definite information. 
Other tempers (Finnish)	Other tempers of pottery, currently in Finnish. Not to be taken as definite information.


Subtype 2	Lower hierarchy of subtype for some artefacts.
Subtype 2 (Finnish)	Lower hierarchy of subtype for some artefacts in Finnish.
Integrity	Integrity of the artefact (TRUE/FALSE).
Rock type (Finnish)	Type of rock material, currently in Finnish.
Length (mm)	Length of the artefact in millimeters.
Width (mm)	Width of the artefact in millimeters.
Thickness (mm)	Thickness of the artefact in millimeters.
Fragment length (mm)	Length of the fragment in millimeters.
Fragment width (mm)	Width of the fragment in millimeters.
Fragment thickness (mm)	Thickness of the fragment in millimeters.

Decoration elements (Finnish)	Decoration elements, currently in Finnish.
Wall thickness 1 (mm)	Wall thickness measurement 1 in millimeters.
Wall thickness 2 (mm)	Wall thickness measurement 2 in millimeters.
Rim thickness 1 (mm)	Rim thickness measurement 1 in millimeters.
Rim thickness 2 (mm)	Rim thickness measurement 2 in millimeters.
Crust	Presence of food crusts on the pottery.
Stone art (Finnish)	Stone artefact description, currently in Finnish.
PhotoID	Identification number of the photograph (e.g., “KM 12345_5”)

Decoration	Presence of decoration on pottery
	
Wave motif	Presence of wave motif decoration.
Grid motif	Presence of grid motif decoration.
Cord impression	Presence of cord impression decoration.


Site context information
Settlement, cremation cemetery, inhumation cemetery, cairn, stray find, hoard, other context. For Iron Age artefacts, the main type of find context is also recorded: inhumation cemetery, cremation cemetery, cairn, settlement site, hoard, and stray find. This attribute gives a contextual information of the find circumstances, which is crucial for understanding many of the distributions of the Iron Age artefacts.

Settlement site	Artefacts found at a settlement site.
Cremation cemetery	Artefacts found at a cremation cemetery.
Inhumation cemetery	Artefacts found at an inhumation cemetery.
Cairn	Artefacts found at a cairn.
Stray find	Artefacts found as stray finds.
Hoard	Artefacts found as part of a hoard.
Other context	Other contexts in which artefacts were found.

Other information
Object attributes (certainty, integrity, measures, crust etc). Object attributes, such as integrity and measures, differ depending on the material. Certainty indicates the dataset compiler's subjective identification of the artefact type, with 1 meaning certain, 2 meaning probable, and 3 meaning possible. The integrity is indicated with a TRUE/FALSE statement in the relevant column. The intact and fragmented artefacts' dimensions are recorded in separate columns (length, width, thickness). For pottery, the main temper and other tempers are explained in two columns, currently in Finnish. If present, the decorative motifs on Iron Age pottery are recorded. However, the documentation of stone tool material is only available in Finnish and is based on a quick and superficial visual inspection, making it very subjective. Therefore, the recorded information on stone tools should only be considered suggestive. For Iron Age pottery, a separate “crust”-column was used to record the presence of food crusts in the surfaces of the pottery. In Stone and Bronze Age pottery this is written (in Finnish, “karsta”) in other notes -column.

Count (only pottery). The number of pottery sherds is recorded in three columns (count 1-10, count 10-100, and count >100 sherds) to indicate their relative amount.
Other notes. This column has some additional information in Finnish. The texts are impressionistic observations, but we decided to keep them along. No translation in English is available; this column should not be used as definitive information. 
PhotoID. Each artefacthas an individual name (ID) which also operates as the number within with the respective photo(s) is found in the photo folder. The photos are located in Supplement 2 (https://zenodo.org/records/11256533)  The ID for each artefact was created with the following pattern (titles of columns of the AADA Database): “Collection” + ”Main number” + ”Subnumber” = “PhotoID”, eg. KM + 12345 + 5 = KM 12345_5. Thus the artefact can be found from the Supplement 2. AADA photo folder with the name KM 12345_5.jpg. 
In several cases there are many photographs of the same artefact and then these are indicated with a,b,c etc., e.g., KM 12345_5b.jpg. Unfortunately some of the extra photos are also named as149, 150a, 150b, 150c, 154, 210 ja 210a and so on 
Most of the pottery data do not have photos of them because the material is highly fragmented and unique vessels were not separated.
The artefact photos are arranged according to their collection id:s organised in folders in Supplement 2.To merge the photos to the typological data, users need to download the photos to their computer and run the Python script available in Supplement 2, in the “AADA Photos Hyperlink folder”. The details about the script can be found in the Readme file of the same folder.  Photo links can also be created to the Photo ID column of Excel tables



Notes
Certain aspects still require attention, particularly the completion of the Iron Age artefacts. Approximately 45-50% of the Finnish Iron Age material needs to be added to the dataset (this estimate excludes the metal detector finds made during the past two decades). Additionally, the documentation of Stone Age stone tools is not entirely complete. There are plenty of local museums in Finland, and most of these have a few or a few dozen stone axes and chisels, which were not possible to record during the current project. Within the collections of the National Museum of Finland, recording of stone artefacts acquired in the 1910s and 1920s is unfinished, and the same, to some extent, applies also to the collections of Ålands Museum and Tampere Museum. 

Data collection notes
Emphasizes southern Finland due to lockdowns during the coronavirus pandemic in 2020. Collections from museums in northern and eastern Finland were not studied.
Data restrictions
The AADA dataset publication is available at Zenodo. and the future updates will be at GitHub (https://github.com/AADA-DATA/AADA-DATABase). The AADA data is stored and managed in GitHub (). The Excel workbooks of the AADA dataset are stored as a snapshot in Cern’s Data Centre’s Zenodo-repository including photographs. The dataset and photos are freely and openly available to anyone with the condition of mentioning this publication as a reference when using the data in publications.Dataset and photos are for noncommercial use only.

Reference
Pesonen, P., Moilanen, U., Roose, M., Saipio, J., Tiilikkala, J., Sanwal, U., Immonen, V., Vesakoski, O. & Onkamo, P. 2024. Archaeological Artefact Database of Finland (AADA). Resubmitted manuscript to Nature Scientific Data
