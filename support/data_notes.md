# Notes on data:

## LODES:
- Description:
  + Bloc level data counts of workers
- Geographic level:
  + Block level
  + Crosswalk file maps block to county, city, metropolitan area, etc.
- File Name:
  + MAIN: only workers who work and live in the state
  + AUX: Also consider workers from outside of state who work in state
  + JT00: All type of jobs (can be split by primary, private, federal, etc.)
  + S000: Total number of jobs (can be split by age, wage, industry)
  + S001: Primary jobs (can be split by age, wage, industry)
    - *Why primary jobs only?*
- OD data:
- RAC data:
- WAC data:
  + *No sex, race, education, firm age information before 2009*
- Geographic Crosswalk File:
  + 343,565 blocks (many therefore with neither residents nor workers)



## Quarterly Workforce Indicator (QWI):

- Description:
  + Geographic labor statistics
- Geographic level:
  + Most granular seems to be Workforce Investment Area but this is not mappable to block!
  + Most useful probably Metropolitan Area
- Necessary files:
  + GM: Metropolitan level
  + NS: NAICS industry sectors (there are other industry categorizations as well)
  + F: firm age and size not included (can be additional information for further groups)