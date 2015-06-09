---
permalink: /sustainable-model/
layout: default
title: A Sustainable Model
---

## Data.gov as the canonical API catalog

When it has been made redundant by the [API listing in Data.gov](http://catalog.data.gov/dataset?res_format=api&_res_format_limit=0), the [18F List](http://pages.18f.gov/API-All-the-X/pages/individual_apis) should be deprecated.  At that point, Data.gov will be the most comprehensive API catalog as well as the canonical API catalog.  

Data.gov's catalog is automatically maintained by harvesting each agency's public data listing, located at _agency.gov/data.json_ [[more info here](https://project-open-data.cio.gov/)].  When new APIs are found or there are existing records should be improved, the requests need to be funneled through agencies.  The changes need to take place at the agency's public data listing.  This will then update Data.gov.  

## Enabling automatic updates to other catalogs

We should build a means by which the API listing of Data.gov can be automatically consumed by other API catalogs, such as ProgrammableWeb and APIs.io.  This is being discussed [here](https://github.com/unitedstates/APIs/issues/7).  

## Enable Easy Contrasts of the Data.gov API catalog and others

As we [gain API access to 3rd party catalogs](https://github.com/unitedstates/APIs/issues/13), we should build sustainable means of comparing those catalogs against Data.gov, primarily for the purpose of discovering APIs that aren't in Data.gov.  

## Report Problems with API Records 

There is a need for a federated feedback engine which supports easily giving feedback from the agency or project developer hub as well as from Data.gov.  On Data.gov, each data record has a `Report Data Issue` button that allows for feedback on that record.  Possibilities include employing API access to the resulting data to offer feedback modules that agencies can integrate into their developer hubs or automatically file an issue in the appropriate GitHub issue tracker.  


## Reward Good Accounting of APIs ??
* SEO-friendly page or site that attracts logical queries [e.g. `census API`]
* Enable automatic updates to other catalogs
* What else?  

## Requests for New APIs 

Data.gov now has a data requests functionality ([form here](http://www.data.gov/data-request/), [submissions here](http://www.data.gov/requests/)).  We've [requested an optional field be added](https://github.com/GSA/data.gov/issues/642) to allow someone to clarify that they are requesting an API, as well as [API access to the data requests](https://github.com/GSA/data.gov/issues/643).  With these, we would be able to easily pull out API requests by agency.  
