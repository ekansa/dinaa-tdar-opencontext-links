# dinaa-tdar-opencontext-links
Simple CSV data documenting cross-references between tDAR site metadata and DINAA site file URIs published by Open Context

BACKGROUND
----------
The Digital Index of North American Archaeology (DINAA) project (see: http://ux.opencontext.org/blog/archaeology-site-data/) works to publish state government curated archaeological "site file" records on the Web via Open Context (http://opencontext.org). To facilitate precise citation and referencing as well as Linked Open Data (LOD) applications, Open Context mints a Web URI for each of the DINAA site file records. This data set correlates and cross-references DINAA site file URIs with metadata URIs for archaeological sites curated by the tDAR (http://tdar.org) digital repository. 

We made links between tDAR metadata entities and DINAA URIs by matching Smithsonian "trinomial" (see: http://en.wikipedia.org/wiki/Smithsonian_trinomial) identifiers by calling one of tDAR's APIs. The Python code used to make these requests and process the results is part of the new version of Open Context (see: https://github.com/ekansa/open-context-py/tree/master/opencontext_py/apps/ldata/tdar) that is currently in development. 

This dataset is current as of April 10, 2015 but will be updated shortly once we have completed publication of additional state site file datasets.

CAVEATS / ISSUES
----------------
The Open Context project is currently wholly revising source code, data models and databases. Open Context's website (http://opencontext.org) still runs the depreciated software and databases, while the new version of Open Context is currently undergoing development and testing at a host (http://opencontext.dainst.org) provided by the German Archaeological Institute (DAI). To view DINAA records linked to tDAR, please use the URLs for the DAI mirror / testing site provided in the CSV file. Structured (linked) data relating DINAA with tDAR are available in the JSON-LD format at Open Context's DAI mirror / testing site.

ACKNOLWEDGEMENTS
----------------
We would like to thank Adam Brin of Digital Antiquity for his help in using the tDAR API. 
