# BI environment components

**Data Containers**

* **Data dispersion**: Data tends to be dispersed and exist in _**different types of containers**_
* **Data containers**: _**Data stores**_ whose content may be _**of a different nature**_, due to the tool that generates said data.
* _**Contents**_: _**Text files, databases, etc**_. They are _**limited by**_ the corresponding access to the _**connectors available to the extraction tools**_. Apply to:
  * _**Data sources**_: Elements that store data in origin.
  * _**Data targets**_: Target data stores.
  * _**Data intermediate**_: Intermediate stores, which may be necessary to use for a specific treatment of the data at a given time, for the modeling of these.

**ETL tools (Extract-Transform-Load)**

* Tools for the _**extraction**_ of the content from the sources, _**modeling**_ (transformation) of said information and _**loading**_ in the destination containers.
* They are _**essential**_, since _**the contents can be scattered and in different formats**_.
* Once the information has been _**extracted and filtered**_ (excluding those rows that are not necessary), the _**crosses, calculations and other necessary operations**_ will be carried out with the aim of _**relating all the origins involved**_. **Intermediate tables**: They may exist and are intended to _**insert information with the raw data**_. _**At the end of the modeling process they can be eliminated**_, depending on the temporality of the information they store. These data stores _**give rise to 'stages'**_, which are intermediate loading scenarios.

**Dashboards**

* They are business management tools created to _**measure the evolution of activities and processes generated within organizations**_.
* They are used to _**build visual resources**_, which facilitate the representation of the analyzed content, to subsequently _**speed up and facilitate decision-making**_.
* They display the data in a _**friendly**_ way and allow _**interaction**_ with the user, that is, it is _**quick and easy**_ to carry out _**segmentation and filtering**_, in order to put the focus on certain data.
* Within the data presentation cycle, it will be the _**last step found in the development**_.
* It is the _**layer of greatest interest to the client**_, it is the one that represents the data required by the client in a visual and friendly way.

**KPI's (Key Performance Indicators)**

* Key Performance Indicators
* They refer to a series of _**metrics that are used to synthesize the information**_ (they detail what the measurement objectives are).
* With them, data related to the _**efficiency and productivity of the actions carried out will be analyzed, in a way that facilitates decision-making**_.
* They make it possible to _**determine the strategic actions of the business**_, which have been most effective in meeting the objectives set in a specific process or project.
* _**It is not**_ a resource in the form of a _**tool**_, it is an essential element when planning a project, which _**will tell us what needs to be measured**_.
* They not only serve to _**detail where the measurement focus is placed**_, but also serve so that _**developments are constantly evolving in order to improve**_ the data represented and, therefore, from his _**analysis**_.
