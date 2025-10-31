# What is CoRA Analytics?

The CoRA Analytics engine is part of the CoRA Ecosystem that can be thought of as an extension and a framework to perform analytics on forensic anthropology datasets. It is also designed to act as a broker facilitating exchange of data from various systems such as the native CoRA projects data, CMS/StarLIMS data in the appropriate format and sending the various datasets to the appropriate analytics apps. These analytics apps can be independent self contained applications build by individual researchers and are independent of the CoRA Ecosystem developed and managed by the researcher/author. These apps must follow and comply with established architecture guidelines to work with the base CoRA Analytics engine and established data quality parameters and established APIs.

The diagram below details the logical diagram for the CoRA Ecosystem Analytics Architecture.
![CoRA Ecosystem Analytics Architecture](../assets/images/architecture/Cora-Ecosystem-Analytics-Architecture-Diagram.png)

## Dashboard Visualizations

!!! warning

    The following section on this page is work in progress.

## Built-in Analytics
The CoRA analytics engine provides some built-in analytics out of the box such as simple regression analysis for the datasets that are most commonly used in forensic anthropology. Other more advanced analytics will be provided via independent analytics application that can be developed by any researcher and plug-in into the CoRA Ecosystem.

## Knowledge Graphs
The CoRA analytics engine provides the ability to leverage advanced analytics using project specific knowledge graphs. The CoRA knowledge graphs leverages the [Neo4J](https://neo4j.com/) Graph database to allow forensic anthropologists and scientists to better understand & analyze their project specimens and its related data to help in the missing persons identification process. It allows forensic scientists to find relationships between specimens using related data such as DNA, pair matching, articulations, taphonomy, anomaly, trauma, pathology, among others.

### So What is a Knowledge Graph?
A knowledge graph is a design pattern for storing, organizing, and accessing interrelated data entities, including their semantic relationships. With knowledge graphs, you can better understand your data and build more intelligent applications. A knowledge graph contains three essential elements:

1.	**Entities**, which represent the data of the organization or domain area.
2.	**Relationships**, which show how the data entities interact with or relate to each other. Relationships provide context for the data.
3.	An **organizing principle** that captures meta-information about core concepts relevant to the business.

Here is the [process guide](./knowledge-graphs/cora-knowledge-graph-database-manual.pdf) that project leads and their teams can use to get access to their projects knowledge graph DBMS.

## Independent Analytics Applications
Following are some of the independent analytics applications that are either being developed or have already been developed that work with the CoRA Ecosystem.

!!! warning "Independent Analytics Applications"

    The following section on this page is work in progress.

### Osteometric Sorting
Blurb by author here - Jeffery Lynch

### Z-Transform
Blurb by author - Julia Sommer

### Odontosearch
Blurb by author here - Author Name

### Optosearch
Blurb by author here - Author Name

### HumanID
Blurb by author here - Author Name

### Dental Metrics
Blurb by author here - Author Name

## Contribution Guidelines for CoRA Analytics
