# Env_LISPT
Adding an environmental dimension to LMPs

During a technical workshop in December 2018, the “better incorporation of environmental impacts/consequences in the livestock sector development” was identified as a priority for future development of the LISPT toolbox. Recommendations of the workshop were to start off by developing a stand-alone environmental module that uses data from LSIPT to calculate GHG emissions and water use from livestock. Later activities would include the incorporation of a feed basket and development of scorecards to highlight the trade-offs that exist amongst different interventions.  This page presents all progress towards that objective.

The proposed steps for calculating tier 1 and tier 2 GHG emissions and associated land requirements for feed production are as follows: 
1.	Calculate Tier 1 GHG emissions for BAU as well as SCEN (based on animal numbers from the LMP - BAU and “with intervention”)
2.	Add Tier 2 GHG emissions and land requirements using CLEANED
  i.	Description of feed baskets: The core of the CLEANED model are the feed baskets, which will need to be defined for every combination of LMP defined production zone with cow breed. There are two strategies for developing feed baskets that are assumed to produce milk yields as stated in the LMP (in each sub-system; for BAU and with-intervention).  
    (1) Prescribing the share of each feed source as per expert consultation and triangulation with data in the LMP feed resources module and FEAST assessments. 
    (2) Refine/calibrate these expert-opinion-based feed baskets, through running RUMINANT to figure out the feed requirements for the desired milk yield. 
  ii.	Extract animal numbers and productivities from the core model (different for BAU and SCEN)
  iii.	Collate secondary data/assumptions on manure management system, rice growing systems and the length of the dry season


Data from the LMP-LISPT runs will be extracted/transferred to an intermediate excel file, which will in turn be linked to the latest version of the CLEANED model (https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/G0G8IY).  
--> "skeleton for env calculations.xls"
