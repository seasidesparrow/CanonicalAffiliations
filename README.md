# CanonicalAffiliations
This repo contains files which help the ADS Abstract Service clean up and group institutional affiliations.

11 September 2019

These are files used by the ADS Abstract Service (ui.adsabs.harvard.edu)
to normalize institutional affiliations.  The following files are included:

- parent_child.tsv, a tab separated file containing:
 - `parent id`, `child id`, `abbreviated affiliation`, `canonical affiliation`

- country_parent_child.tsv, a tab separated file containing:
 - `country`, `parent id`, `child id`, `abbreviated affiliation`, `canonical affiliation`

- historically_black_colleges_universities.tsv, a tab separated file containing:
 - `child id`, `canonical affiliation`
 - Includes all federally-recognized HBCUs as of September 15, 2025

- tribal_colleges_universities.tsv, a tab separated file containing:
 - `child id`, `canonical affiliation`
 - Includes only tribally-controlled institutions
 - Does not include public schools with significant Native American/First Nations enrollment

- ROR_ADS.tsv, a tab separated file containing:
 - `ROR`, `ads_id` where ads_id might be a parent/child combination 

- README.md (this file) 

- Usage.txt (usage examples in the ADS)
 
If you want to discuss additional applications or see more of this work, please
get in touch.

Carolyn Stern Grant
NASA ADS Abstract Service
Harvard-Smithsonian Center for Astrophysics
cgrant@cfa.harvard.edu

