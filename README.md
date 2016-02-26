
# MMC Multimodell-Container
Multimodels combine building information models and other application models to allow for a flexible integration of distributed information from design, production and operations. To exchange multimodels the Multimodel-Container (MMC) was defined within the buildingSMART German Speaking Chapter.

## Purpose and Design Rational
In design and construction practice it is often not suitable to keep all project information within a single model. There are software applications to coordinate different building models (e.g. of architectural, structural and building systems) and to integrate them with schedule (4D), risk, quality and cost information (5D). However, the variety of application domains hinders a standardised exchange of the resulting model compounds. 

The MMC combines different application models based on their metadata retaining their original (standard or proprietary) data formats. The interdependencies amongst the models are represented by Link Models comprising a set of link objects directly referencing (connecting) interrelated elements by ID. 

## MMC Specifications
A multimodel-container comprises three types of resources:
* MMC Description (1,1), a data file conformant to the MMContainer.xsd
* Link Models (0,*), data files conformant to the LinkModel.xsd
* Application Models (0,*), data files (or their resources locations) in any data format

The MMC-Schemas have been published in verions:
* MMContainer-2.0.xsd
* LinkModel-2.0.xsd
* MMContainer-1.0.xsd
* LinkModel-1.0.xsd

## Application Domains
The MMC Version 2.0 is generic and can be applied in literally any domain. In the Germany there are two initiatives working on implementation guidelines to use the MMC in the domains of: 
* Tendering, contracting and billing of construction works combining building models, bill of quantities and time schedules, see
* Facility management and documentation combining building models with as-build documentation and manuals 

The MMC Version 1.0 was developed in the German research project Mefisto to mainly support construction project management and construction simulation (cf. www.mefisto-bau.de).

## Software and Examples
The creation and exchange of MMC Version 1.0 is supported by software applications from RIB Software AG, gibGreiner GmbH, f:data GmbH und Tragwerk Software GmbH. 

Examples can be found at http://www.mefisto-bau.de/resources.html.


