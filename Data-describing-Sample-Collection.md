## Definition

For MIABIS Core 2.0 purpose, Sample Collection represents a set of samples with at least one common characteristic (Merino-Martinez et al. Biopreserv Biobank. 2016; 14(4):298-306).

| Attribute Code| Attribute Name| Allowed Values| Description |
|---|---|---|---|
| MIABIS-2.0-01| ID| Text| Sample Collection ID that also links the sample collection to the hosting biobank or study| 
| MIABIS-2.0-02| Acronym| Text| Short name in use for the sample collection| 
| MIABIS-2.0-03| Name| Text| The name of the sample collection in english| 
| MIABIS-2.0-08| Description| Text| A description of the sample collection. Recommendation max. 2000 char.| 
| MIABIS-2.0-09| Sex| Text list| The sex of the individuals in the sample collection. Can be one or more of the following values: Male, Female, Unknown, Undiferrentiated [MIABIS-2.0-09](https://github.com/MIABIS/miabis/wiki/Structured-data-and-lists#sex)| 
| MIABIS-2.0-10| Age Low| Integer| Age of youngest sample donor at time of sample donation| 
| MIABIS-2.0-11| Age High| Integer| Age of oldest sample donor at time of sample donation| 
| MIABIS-2.0-12| Age Unit| Text list| Unit defining Age Low and Age High. Can be one of the following values: years, months, weeks, days| 
| MIABIS-2.0-13| Data categories| Text list| The data catagories from which data is available. Can be several values [MIABIS-2.0-3](https://github.com/MIABIS/miabis/wiki/Structured-data-and-lists#data-categories)| 
| MIABIS-2.0-14| Material type| Text list| The biospecimen saved from a biological entity for propagation e.g. testing, diagnostics, treatment or research purposes. Can be several values [MIABIS-2.0-14](https://github.com/MIABIS/miabis/wiki/Structured-data-and-lists#material-type)| 
| MIABIS-2.0-15| Storage temperature| Text list| The long term storage temperature at which the samples are stored after preparation. Can be several values: [MIABIS-2.0-15](https://github.com/MIABIS/miabis/wiki/Structured-data-and-lists#storage-temperature)| 
| MIABIS-2.0-16| Collection type| Text list| The type of the sample collection. Can be several values [MIABIS-2.0-16](https://github.com/MIABIS/miabis/wiki/Structured-data-and-lists#collection-type)| 
| MIABIS-2.0-17| Disease| Structured data| The disease of main interest in the sample collection, if any. Can be several values as defined in [MIABIS-2.0-17](https://github.com/MIABIS/miabis/wiki/Structured-data-and-lists#disease)| 
| MIABIS-2.0-07| Contact information| Structured data| Contact information for the contact person of the sample collection [MIABIS-2.0-07](https://github.com/MIABIS/miabis/wiki/Structured-data-and-lists#contact-information) and [MIABIS-2.0-23](https://github.com/MIABIS/miabis/wiki/Structured-data-and-lists#researcher-information) of the PI| 