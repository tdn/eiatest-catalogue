# EIA Test Catalogue

This catalogue was created in May/June 2025 to test a proposed EIA "Supermodel".

The catalogue lists test versions of major Australian environmental datasets within the scope of [Environment Information Australia (EIA)](https://www.dcceew.gov.au/environment/environment-information-australia) [DCCEEW](https://www.dcceew.gov.au/). A demonstration client, which will soon be online at <https://portal.bdr.gov.au> will show how these datasets can be "deeply integrated" using [Semantic Web](https://en.wikipedia.org/wiki/Semantic_Web) and [Knowledge Graph](https://en.wikipedia.org/wiki/Knowledge_graph) methods.

While most data catalogues list datasets so they can be discovered easily, they don't often provide much assistance for their deep integration, i.e. integration of elements within the datasets. This catalogue does provide for this by ensuring that each dataset listed here is available in a form that is conceptually and technically aligned to a cohesive [Supermodel](https://linked.data.gov.au/def/supermodel).

The supermodels used for the items in this catalogue is online at:

* **<https://linked.data.gov.au/def/eia-supermodel>** - _coming soon!_

## License & Rights

The contents of this catalogue, and of the individual dataset within it, are made available for reuse according to Australian government standard practice under the [Creative Commons BY 4.0 license](https://creativecommons.org/licenses/by/4.0/), a copy of the deed of which is contained in this repository in the `LICENSE` file.

_Note that not all the content of all the datasets listed in this catalogue is publicly available: some of it is protected due to environmental or legal sensitivities._

All this work is copyright as follows:

&copy; Department of Climate Change, Energy, the Environment and Water 2025

## Contact

*contact:*  
[Biodiversity Data Repository Team](https://www.dcceew.gov.au/environment/environment-information-australia/biodiversity-data-repository)  
<bdr@dcceew.gov.au>

*publisher:*  
Environment Information Australia  
[Department of Climate Change, Energy, the Environment and Water](https://www.dcceew.gov.au)  
<eia.feedback@dcceew.gov.au>

*creator:*  
[KurrawongAI](https://kurrawong.ai)  
<info@kurrawong.ai>  
<https://orcid.org/0000-0002-8742-7730>

## Catalogue Resources

| Resource                                                                                                                                                                                                  | Role                                                                                                                | Description                                                                              |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| Reference Vocabularies:<br />[`resources/reference/*.ttl`](resources/reference/*.ttl)                                                                                                                     | [Resource Data](https://prez.dev/ManifestResourceRoles/ResourceData)                                                | EIA Reference Vocabularies                                                               |
| Spatial Datasets:<br />[`https--linked.data.gov.au-def-eia-supermodel.ttl`](https--linked.data.gov.au-def-eia-supermodel.ttl)<br />[`resources/datasets/spatial/*.ttl`](resources/datasets/spatial/*.ttl) | [Resource Data](https://prez.dev/ManifestResourceRoles/ResourceData)                                                | Spatial EIA Datasets                                                                     |
| Non-Spatial Datasets:<br />[`resources/datasets/non-spatial/*.ttl`](resources/datasets/non-spatial/*.ttl)                                                                                                 | [Resource Data](https://prez.dev/ManifestResourceRoles/ResourceData)                                                | Non-spatial EIA Datasets                                                                 |
| Catalogue Definition:<br />[`catalogue.ttl`](catalogue.ttl)                                                                                                                                               | [Catalogue Data](https://prez.dev/ManifestResourceRoles/CatalogueData)                                              | The definition of, and medata for, the container which here is a dcat:Catalog object     |
| Background Details:<br />[`resources/background/*.ttl`](resources/background/*.ttl)                                                                                                                       | [Complete Catalogue and Resource Labels](https://prez.dev/ManifestResourceRoles/CompleteCatalogueAndResourceLabels) | Files containing all the labels and vocab inScheme predicates for the resources' content |
