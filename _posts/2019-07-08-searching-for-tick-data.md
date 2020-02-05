---
layout: post
title: "Searching for Tick Data"
author: Rowan Christie
---
During my RIT-RISE research with Dr. Kaitlin Stack Whitney, I started a new research project with collaborators from Kent State University.

I decided to focus on Ixodes scapularis, the deer tick, which is a primary vector of Borrelia burgdorferi, which transmits Lyme disease. Ixodes scapularis populations have been appearing to increase, according to a previous study (Eisen et al 2016). However, biological studies generally collect short term datasets, and the trends observed from these studies may not be indicative of longer term trajectories.

So to address this, I aimed to use a 'moving window' algorithm developed by Dr. Christie Bahlai, one of the collaborators from Kent State to analyze long term datasets. This analysis would break up the long term tick datasets into different length time intervals, and produce summary statistics (slope, R squared value, p-value, standard error) for these intervals. This would help us analyze how the stability changes with the length of the study. Since these ticks are a critical health concern due to their vector status, understanding their long term population dynamics can inform public health policy.

First, I had find long term publicly available tick datasets to use on the algorithm.

**My criteria was that the dataset had to be at least 10 years long in at least one location, have numerical density, abundance, or count data for the tick species Ixodes scapularis, and can be any life stage of the tick.**

First, I started with the LTER Data portal. I typed in the keyword **scapularis**. There were two results - both were at least 12 years long but I excluded one because it had no count data, only a standard of uncommon, rare, and common. The other dataset, which was focused in Harvard forest, did have count data, so I added the link to my list of candidate datasets. I then typed in the keyword **tick** and found 11 results, however most focused on different animals and had no tick sampling data, and I did not find any new datasets that fit the criteria. I was hoping that there would be more candidate datasets, especially from a data portal focusing on long term datasets.

Next, I searched the Data Dryad repository by first typing in **scapularis**, which turned up 9 results. Several focused on the microbiology of the tick. I found two datasets that fit the criteria. I then typed in **tick** for the search term, and found several more datasets focusing on tick abundance, but some of them were only short term. I found one possible dataset that focused on several different tick species.

I searched through NEON data portal by typing in **scapularis**, which turned up 0 results, then **tick**, which turned up 2 results. Only one of them contained tick sampling data, and it was too short of a study.

I searched through google datasets by typing in the keyword **scapularis**. There were 76 results. Many of the results were duplicates of themselves. I also found some that focused on the microbiology of ticks, rather than working to sample ticks out in the field. Some were only short term. In short, there were a lot of datasets that had to be filtered through, but I found 4 datasets fitting the criteria from the NY department of health. These four datasets were from studies that collected data in the same way, by dragging and was in the metric of average # of ticks per 1000 meters. However, this metric was linear, so it could not be compared as easily to a spatial metric like # ticks per meter squared.

When I showed my mentor the NY department of health data I had found, she suggested looking at data portals from other states, especially the Eastern ones, such as Connecticut, which could have publicly available tick datasets due to the higher prevalence of ticks in those states.

I actually looked at a map of Ixodes scapularis tick presence of the US to help me prioritize which states I should be looking at. I predicted that if a state has a confirmed deer tick population, then those states will be more likely to have collected tick data, although whether or not it is publicly available is still questionable.

For example, the University of Rhode Island has collected tick data, but they do not seem to have it publicly available. They have a site called TickEncounter (https://tickencounter.org/) which provides all sorts of information about ticks, like what species are common in Rhode Island, how to identify them, how to remove them, and what kind of habitat different tick species may be found in. They also have a crowd-sourced survey called TickSpotters where the public can submit tick data, which includes the tick species, life stage, whether it was found on person, pet, or wandering, date, and what country it was found. They then use this information to provide a TickEncounter index, which seems to be ranked as 'Low', 'Medium', or 'High.' That's not exactly as helpful as providing the raw data, however.

Another common issue I encountered was that some of the states only had surveillance reports for Lyme disease, and no surveillance tick data.

For New Jersey, I started by searching for the NY department of health webpage (https://www.nj.gov/health/). I accessed the Offices & Programs dropdown at the front of the page, tabbed to the Communicable Disease page, accessed the Statistics, Reports, & Publication dropdown, and clicked on Vector borne surveillance reports. While some of the earlier reports did provide data on tick related emergency visits and tick borne diseases, the older reports only provided data about mosquito borne diseases, and weren't enough reports with tick data to constitute 10 years. So I did not include the New Jersey reports in my list of candidate datasets.

I searched through for the Connecticut department of health webpage (https://portal.ct.gov/DPH) and typed in the keyword **tick**. There were 75 results. I tabbed to the link worded "Tick" which led to this page (https://portal.ct.gov/DPH/Epidemiology-and-Emerging-Infections/Ticks), and upon scrolling down to the CAES Tick Office & Tick Testing section, led to a link titled "Tick Test Summaries" (https://portal.ct.gov/CAES/Fact-Sheets/Tick-Summary/Summaries-of-Tick-Testing). This page provided a list of tick testing results for each page. These reports included data for several tick species, such as **Ixodes scapularis**, and also included data on the percentage found positive for Borrelia burgdorferi, the bacterium that transmits Lyme disease. As there were over 10 years worth of reports, it met my criteria and I added to my list of candidate datasets.

I then looked to Pennsylvania for tick datasets. I searched their department of health webpage using the keyword tick, but found no datasets. After this, I tried something else and searched google using the keyword **Pennsylvania tick datasets.** Lo and behold, there was actually a study that provided 117 years of data (https://parasitesandvectors.biomedcentral.com/articles/10.1186/s13071-019-3451-6#Sec9). The data provided through the study had count data of Ixodes scapularis over all life stages, and as it fit the criteria, I added it to my list of candidate datasets.

I used the same method to search for tick data in the state of Delaware, however, I did not find any results.

At this point, I stopped looking for tick data, but searching through all of these different sites did show me how diverse studies can be in terms of collecting and reporting tick data. There are many different metrics, standards, methods for tick data, and comparing the tick abundance, count, or density data from different studies isn't that simple.
