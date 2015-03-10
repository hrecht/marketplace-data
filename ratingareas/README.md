# marketplace-ratingareas
Crosswalk for counties/zip3 to rating areas for health insurance marketplaces, for use in marketplace analysis and mapping.

Data from http://www.cms.gov/CCIIO/Programs-and-Initiatives/Health-Insurance-Market-Reforms/state-gra.html
* Corrected misspellings and duplicates in the source data to match with county FIPS code. 

## Notes
* All counties, including those in states using zip code rating area states, are included in CountyRatingAreas.csv for matching with other data. Rating area is missing when not defined by county.
* See ZipCodeRAs.csv for states using 3-digit zip codes for rating area definitions. These are not included in the county file because zip codes are not consistent geographic boundaries and are not useful for merging other data - demographic, plan information, etc. Federally managed marketplace plan data are released at the county level regardless of rating area boundary type.
* States using zip code rating areas:
  * Alaska
  * Idaho
  * Massachusetts
  * Nebraska
  * Los Angeles County, California

