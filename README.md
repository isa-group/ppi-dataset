# The PPIs Dataset
Dataset of Process Performance Indicators for IT Service Management

**Summary**

In this chapter, we present the PPIs Dataset, a set of process performance indicators (PPIs) defined in natural language, related to business processes identified in the Information Technology (IT) Service Management of several public organizations in Spain. This dataset has been used as a basis for the development of techniques for modelling PPIs using different notations as well as for the transformation of natural language PPI definitions into others amenable to automated computation, applying natural language processing and matching learning techniques. The PPI information was obtanied from the Service Level Agreements (SLA) of the technical specifications of the request for quote (RFQ) that these organizations make. A pre-processing of the data was carried out to verify the completeness of PPI definitions, obtaining a total of 71 indicators associated to different processes. The data was originally provided in Spanish and was translated for dissemination purposes. To the present, this dataset has been used in several researches, two of them focused on the automatic transformation of PPIs defined in natural language to others that are defined in a structured way to facilitate their automatic calculation, and one oriented to the definition of PPIs through graphic notations.

**Content**

The repository contains 71 PPIs identified in the service level agreements of the technical specifications of the request for quote that several public organizations provided. These indicators were distributed in different spreadsheets in CSV format, separating the definitions by language (English and Spanish) and by process.
* ENG_P-RequestForRelease-PPIs.csv
* ENG_P-RequestForChange-PPIs.csv
* SPA_P-PeticionDeLanzamiento-PPIs.csv
* SPA_P-PeticionDeCambio-PPIs.csv

Each spreadsheet contains the following information:
* _Process_: Process Identifier
* _Measured data_: Type of information expected from the calculation of the indicator.
* _PPI identifier_: A number to identify the PPI.
* _PPI name_: Short description of the indicator. 
* _Calculation of the indicator_: Detailed description indicating how the indicator should be calculated
* _Interested rol_: Participating role in the process (human resource), involved in the calculation of the indicator.




**Authors**
* Bedilia Estrada-Torres
* Adela del-Río-Ortega
* Manuel Resinas
* Antonio Ruiz-Cortés
