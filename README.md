# AndMalOnt - Android Malware Ontology

## Overview
AndMalOnt is a proposed Android malware ontology aimed at categorizing and classifying Android malware samples. This application utilizes the provided APIs from the https://bazaar.abuse.ch/ portal to download malware reports, parse them, and generate an OWL (Web Ontology Language) representation for further analysis and research.

## Features
- Download Android malware reports from https://bazaar.abuse.ch/ using the provided APIs.
- Parse the downloaded reports to extract relevant information about the malware samples.
- Create an OWL representation for the extracted data, forming the AndMalOnt Android malware ontology.
- We also constructed a knowledge graph of Android malware extracted from the MalwareBazaar repository. 
- The knowledge graph consists of 2600 nodes (i.e., individuals) represented in the RDF using the AndMalOnt ontology.
- Enable categorization and classification of Android malware samples based on the extracted information.

## Usage
1. Set Up the Environment: Java 8+
2. Run the Application: Execute the application to initiate the process of downloading the malware reports, parsing them, and generating the OWL representation.
3. Analyze the AndMalOnt: Utilize the resulting OWL representation of the Android malware samples to perform categorization, classification, or any other desired analysis.
4. To view AndMalOnt instances open the individuals.owl file in Protege.
5. If you need to generate individuals or open in Protege , change the physical path in AndMalOnt.owl and individuals.owl, to include MALOnt.owl :
  ( <owl:Ontology rdf:about="http://secuirty.birzeit.edu/android_malware_ontology">
   <owl:imports rdf:resource="file:///xxxx/MALOnt.owl"/>
   </owl:Ontology>) 

## Requirements

## License
See [LICENSE](LICENSE)

## Contribution

## Contact

