# sdm-to-owl-transformation

This repository contains the Scorpio Support Module sdm-to-owl-transformation. It is implemented as a Jupyter Notebook whose purpose is to translate NGSI-LD compatible Smart Data Models represented as JSON-Schema into an OWL ontology. The Smart Data Models are available from https://github.com/smart-data-models. For a description of the Jupyter Notebook code, how to run it and its current limiations, check "OWLOntologiesFromSmartDataModels.pdf". Please note that the content is open source under a [3-clause BSD license](https://github.com/ScorpioBroker/sdm-to-owl-transformation/blob/main/LICENSE).

- SmartDataModels.ipynb - Jupyter Notebook
- OWLOntologiesFromSmartDataModels.pdf - Slide set describing the Jupyter Notebook, how it works and what the current limitations are.
- BuildingAndEnergy.ttl - example created from Building and Energy Smart Data Models
- SmartDataModelsList.txt - list of all smart data models existing at creation time, i.e. around 2021/2022
- SmartDataModelsList-WithoutEnergyCIM.txt - list of all smart data models existing at creation time without the energy ones (as there are many), i.e. around 2021/2022
