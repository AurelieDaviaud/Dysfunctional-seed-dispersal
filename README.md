# Dysfunctional seed dispersal in the endemic flora of Madagascar

* Language: R
* Methods: linear regression, multivariate imputation by chained equations (MICE), spatial analyses
* Associated publication: (in prep)

## Context

Seed dispersal is a key process in plant reproduction in which animals can play an important role.
There are two ways animal can disperse seeds:
* via the gut (=endozoochory) and
* via the hair or hooves (=epizoochory).

In many parts of the world, animal-dispersed plant species face a dysfunctional seed dispersal due to:
* the global extinction of their dispersers and/or
* the local extinction of their dispersers.

In __Madagascar__, following Holocene extinctions (from ~2000 years  B.P.), a large number of dispersers have been lost (giant lemurs, elephant birds,...). Now, due to deforestation, the remaining dispersers (mainly lemurs) face a strong decrease of their range distribution. Our aim is to highlight the dysfunctional seed dispersal faced by the Madagascan plant species. 

1) We will estimate the __number of potential dispersers__ for each endemic endozoochorous plant species. We will compare the __seed size__ of each plant species to the size of the largest seed able to be ingested by each frugivorous animal. 

2) We will estimate the __number of available dispersers__ (lemurs only) by matching the __distribution__ of plant species to the distribution of their potential dispersers. 

*Data collection*: I performed a literature review, checked databases and examined herbarium specimens to gather data on seed dispersal, and traits and distribution of plants and frugivores in Madagascar.


The notebook has been divided into 3 parts:
* Preparation of data and imputation of missing values (Dysfunctional_seed_dispersal-1-DataPreparation-Imputation)
* Preparation of imputed data  and some statistics (Dysfunctional_seed_dispersal-2-ImputedDataPreparation-Statistics)
* Spatial analysis (Dysfunctional_seed_dispersal-3-SpatialAnalysis)


*IMPORTANT NOTE*: The data used for this project are private. Therefore, they won't be disclosed before the publication of the related article.
