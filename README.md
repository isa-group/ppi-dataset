# The PPIs Dataset

**Summary**

In this chapter, we present the PPIs Dataset, a set of process performance indicators defined in natural language, related to the IT service management processes of several public organizations in Spain. This dataset has been used as a basis for the development of techniques for modelling PPIs using different notations as well as for the transformation of natural language PPI definitions into others amenable to automated computation, applying natural language processing and matching learning techniques. The PPI information was obtained from the Service Level Agreements (SLA) of the technical specifications of the request for quote (RFQ) that these organizations have made. A pre-processing of the data was carried out to verify the completeness of PPI definitions, obtaining a total of 102 indicators associated to different processes. The data was originally provided in Spanish and was translated for dissemination purposes. This dataset has been used in several research articles, two of them focused on the automatic transformation of PPIs defined in natural language to others that are defined in a structured way to facilitate their automatic calculation, and one oriented to the definition of PPIs through graphic notations.


**Content**

The repository contains 102 PPIs identified in the service level agreements of the technical specifications of the request for quote that several public organizations provided. These indicators are distributed in different files in CSV format, separating the definitions by language (English and Spanish).
* ENG_ThePPIDataset.csv
* SPA_ThePPIDataset.csv


Each spreadsheet contains the following information:
* _Process_: The process identifier
* _PPI identifier_: A number to identify the PPI
* _PPI name_: Short description of the indicator
* _Calculation of the indicator_: Detailed description indicating how the indicator should be calculated
* _PPI Type_: It indicates the type of information or data calculated by the PPI, e.g. time, percentage, etc.





**Authors**
* Bedilia Estrada-Torres
* Adela del-Río-Ortega
* Manuel Resinas
* Antonio Ruiz-Cortes


