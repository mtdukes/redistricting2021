# Preliminary findings
***NOTE: The results here are PRELIMINARY and are subject to change.***

Detecting signs of gerrymandering in electoral maps can be complicated, especially in a state like North Carolina.

It's not enough to examine how the overall vote compares to the makeup of a delegation – whether it's the state House, state Senate or U.S. House. Proportional representation isn't required in the U.S. winner-take-all system, and there are natural biases caused by the way partisan voters have sorted themselves into various regions.

But we can look for gerrymandering by comparing maps drawn by lawmakers [to what's "normal"](http://newsobserver.com/monster) – a collection of tens of thousands of computer-generated maps that follow a set of more-or-less neutral [redistricting criteria set by the legislature](https://ncleg.gov/documentsites/committees/Senate2021-154/2021/08-12-2021/Criteria.adopted.8.12.pdf). 

For each of these maps, we can take precinct-level vote totals from past elections and re-sort them into districts, simulating outcomes under different scenarios. The method doesn't *predict* how maps will perform in the future. Instead, it uses actual election data from past races unaffected by gerrymandering – president or governor, for example – where all voters cast ballots for the same set of candidates.

By counting how many Republicans or Democrats are elected using each map and in each election, we can see how often a given proposal lines up with what we'd expect from our collection of tens of thousands of maps.

These techniques have been used both before the U.S. Supreme Court and North Carolina state courts to claim past maps were extreme partisan gerrymanders, and it was among the arguments that convinced judges in 2019 that those maps violated the North Carolina constitution.

Below are some of the preliminary findings from a 2021 analysis of N.C. General Assembly redistricting proposals using some of the same techniques conducted by Tyler Dukes, of The News & Observer, based on [data produced by Jonathan Mattingly and Greg Herschlag](https://git.math.duke.edu/gitlab/gjh/redistricting2020results) of the [Quantifying Gerrymandering project at Duke University](https://sites.duke.edu/quantifyinggerrymandering/2021/10/26/the-geopolitical-landscape-of-the-north-carolina-general-assembly/).

***NOTE: The results here are PRELIMINARY and are subject to change as additional verification, fact-checking, etc. takes place. If you spot any errors, please contact [Tyler Dukes](mailto:mtdukes@newsobserver.com).***

## Overview
***NOTE: The results here are PRELIMINARY and are subject to change.***

### N.C. Senate proposal (SST-13, [SB 739](https://www.ncleg.gov/BillLookUp/2021/S739), 2nd edition)
In general, [the overall results](https://github.com/mtdukes/redistricting2021/blob/main/prelim-findings.md#nc-senate-proposal-sst-13-sb-739-2nd-edition-1) show that the proposed state Senate map (SST-13) drawn by Republicans in 2021 would elect one to two more Republicans than expected under most past electoral conditions, based on a collection of 100,000 computer-generated maps provided by the Duke team.

![us_president20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_us_president20_mcd.png)
*Count of the number Democrats elected under SST-13 compared to 100,000 maps generated by Duke mathematicians according to the legislature's redistricting criteria, using statewide vote totals from 2020 presidential race re-sorted into districts.*

In particular, [district-level election results](https://github.com/mtdukes/redistricting2021/blob/main/prelim-findings.md#nc-senate-proposal-sst-13-sb-739-2nd-edition-2) using this map show evidence of "packing" and "cracking" voters across some districts as the percentage of Democratic voters increases beyond 40%, evidenced by outcomes that fall outside the bulk of what's expected using the computer-generated maps.

![governor20](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_box_governor20_mcd.png)
*Percentage of the vote for Democrats in each district, ordered from most Republican to most Democratic, under SST-13 compared to 100,000 maps generated by Duke mathematicians according to the legislature's redistricting criteria, using statewide vote totals from 2020 governor race re-sorted into districts.*

### N.C. House proposal (HBK-14, [HB 976](https://www.ncleg.gov/BillLookUp/2021/H976), 3rd edition)
In general, [the overall results](https://github.com/mtdukes/redistricting2021/blob/main/prelim-findings.md#nc-house-proposal-hbk-14-hb-976-3rd-edition-1) show that the proposed state House map (HBK-14) drawn by Republicans in 2021 would elect four to seven more Republicans than expected under most past electoral conditions, based on a collection of 100,000 computer-generated maps provided by the Duke team.

Under the conditions of many statewide elections, not a single one of the 100,000 maps generated by the Duke team would elect as many Republicans as the state House map proposal would.

![president20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_president20_mcd.png)
*Count of the number Democrats elected under HBK-14 compared to 100,000 maps generated by Duke mathematicians according to the legislature's redistricting criteria, using statewide vote totals from 2020 presidential race re-sorted into districts.*

In particular, [district-level election results](https://github.com/mtdukes/redistricting2021/blob/main/prelim-findings.md#nc-house-proposal-hbk-14-hb-976-3rd-edition-2) using this map show evidence of "packing" and "cracking" voters across some districts as the percentage of Democratic voters increases beyond 40%, evidenced by outcomes that fall outside the bulk of what's expected using the computer-generated maps.

![governor20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_box_governor20_mcd.png)
*Percentage of the vote for Democrats in each district, ordered from most Republican to most Democratic, under HBK-14 compared to 100,000 maps generated by Duke mathematicians according to the legislature's redistricting criteria, using statewide vote totals from 2020 governor race re-sorted into districts.*

*Note: The results shown here arbitrarily use "Democrats elected" to stay consistent with the Duke analysis. The findings would be identical (but reversed) if we used "Republicans elected."*

***NOTE: The results here are PRELIMINARY and are subject to change as additional verification, fact-checking, etc. takes place. If you spot any errors, please contact [Tyler Dukes](mailto:mtdukes@newsobserver.com).***

## Findings
***NOTE: The results here are PRELIMINARY and are subject to change.***

### Comparing overall outcomes

The histograms below show electoral outcomes calculated by re-sorting precinct level results from 2020 races into each of the 100,000 district plans created by the Duke Quantifying Gerrymandering team, as well as the outcome of the given race using votes re-sorted into the 2021 map proposal.

The accompanying table shows how the result of the graph are distributed across all 100,000 maps, with the most common value (mode) in bold. 

#### N.C. Senate proposal (SST-13, [SB 739](https://www.ncleg.gov/BillLookUp/2021/S739), 2nd edition)

##### U.S. President, 2020 (R +0.7)

![us_president20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_us_president20_mcd.png)

| Democrats elected| Number of maps| Percent of maps|
|-----------------:|--------------:|---------------:|
|                15|              0|             0.0|
|                16|              0|             0.0|
|                17|              0|             0.0|
|                18|              0|             0.0|
|                19|             25|             0.0|
|                20|           6,336|             6.3|
|                **21**|          **43,870**|            **43.9**|
|                22|          43,568|            43.6|
|                23|           6,201|             6.2|
|                24|              0|             0.0|
|                25|              0|             0.0|

##### U.S. Senate, 2020 (R +0.9)
![us_senate20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_us_senate20_mcd.png)

| Democrats elected| Number of maps| Percent of maps|
|-----------------:|--------------:|---------------:|
|                15|              0|             0.0|
|                16|              0|             0.0|
|                17|              0|             0.0|
|                18|              0|             0.0|
|                19|              0|             0.0|
|                20|          14,249|            14.2|
|                **21**|          **38,992**|            **39.0**|
|                22|          34,885|            34.9|
|                23|          10,821|            10.8|
|                24|           1,053|             1.1|
|                25|              0|             0.0|

##### N.C. Governor, 2020 (D +2.3)
![governor20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_governor20_mcd.png)

| Democrats elected| Number of maps| Percent of maps|
|-----------------:|--------------:|---------------:|
|                20|              0|             0.0|
|                21|              0|             0.0|
|                22|              0|             0.0|
|                23|          16,452|            16.5|
|                **24**|          **48,240**|            **48.2**|
|                25|          33,468|            33.5|
|                26|           1,838|             1.8|
|                27|              2|             0.0|
|                28|              0|             0.0|
|                29|              0|             0.0|
|                30|              0|             0.0|

##### N.C. Lt. Governor, 2020 (R +1.6)
![lt_governor20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_lt_governor20_mcd.png)

| Democrats elected| Number of maps| Percent of maps|
|-----------------:|--------------:|---------------:|
|                15|              0|             0.0|
|                16|              0|             0.0|
|                17|              0|             0.0|
|                18|              0|             0.0|
|                19|          18,468|            18.5|
|                **20**|          **43,952**|            **44.0**|
|                21|          31,301|            31.3|
|                22|           5,944|             5.9|
|                23|            335|             0.3|
|                24|              0|             0.0|
|                25|              0|             0.0|

##### N.C. Attorney General, 2020 (D +0.1)
![attorney_general20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_attorney_general20_mcd.png)

| Democrats elected| Number of maps| Percent of maps|
|-----------------:|--------------:|---------------:|
|                20|              0|             0.0|
|                21|           4,344|             4.3|
|                22|          41,570|            41.6|
|                **23**|          **45,519**|            **45.5**|
|                24|           8,567|             8.6|
|                25|              0|             0.0|

#### N.C. House proposal (HBK-14, [HB 976](https://www.ncleg.gov/BillLookUp/2021/H976), 3rd edition)

##### U.S. President, 2020 (R +0.7)
![president20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_president20_mcd.png)
| Democrats elected| Number of maps| Percent of maps|
|-----------------:|--------------:|---------------:|
|                50|              0|             0.0|
|                51|              0|             0.0|
|                52|             12|             0.0|
|                53|            273|             0.3|
|                54|           2,011|             2.0|
|                55|           9,739|             9.7|
|                56|          27,419|            27.4|
|                **57**|          **35,328**|            **35.3**|
|                58|          20,174|            20.2|
|                59|           4,684|             4.7|
|                60|            350|             0.4|
|                61|             10|             0.0|
|                62|              0|             0.0|
|                63|              0|             0.0|
|                64|              0|             0.0|
|                65|              0|             0.0|

##### U.S. Senate, 2020 (R +0.9)
![us_senate20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_us_senate20_mcd.png)
| Democrats elected| Number of maps| Percent of maps|
|-----------------:|--------------:|---------------:|
|                45|              0|             0.0|
|                46|              0|             0.0|
|                47|              0|             0.0|
|                48|              0|             0.0|
|                49|             19|             0.0|
|                50|            134|             0.1|
|                51|           1,010|             1.0|
|                52|           4,819|             4.8|
|                53|          16,518|            16.5|
|                54|          33,293|            33.3|
|                **55**|          **34,299**|            **34.3**|
|                56|           8,909|             8.9|
|                57|            961|             1.0|
|                58|             37|             0.0|
|                59|              1|             0.0|
|                60|              0|             0.0|

##### N.C. Governor, 2020 (D +2.3)
![governor20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_governor20_mcd.png)
| Democrats elected| Number of maps| Percent of maps|
|-----------------:|--------------:|---------------:|
|                55|              0|             0.0|
|                56|              0|             0.0|
|                57|              0|             0.0|
|                58|            210|             0.2|
|                59|           3,504|             3.5|
|                60|          15,312|            15.3|
|                61|          27,976|            28.0|
|                **62**|          **28,303**|            **28.3**|
|                63|          17,402|            17.4|
|                64|           6,069|             6.1|
|                65|           1,127|             1.1|
|                66|             94|             0.1|
|                67|              3|             0.0|
|                68|              0|             0.0|
|                69|              0|             0.0|
|                70|              0|             0.0|

##### N.C. Lt. Governor, 2020 (R +1.6)
![lt_governor20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_lt_governor20_mcd.png)
| Democrats elected| Number of maps| Percent of maps|
|-----------------:|--------------:|---------------:|
|                45|              0|             0.0|
|                46|              0|             0.0|
|                47|             12|             0.0|
|                48|            194|             0.2|
|                49|           1,693|             1.7|
|                50|           8,204|             8.2|
|                51|          22,086|            22.1|
|                **52**|          **34,211**|            **34.2**|
|                53|          24,477|            24.5|
|                54|           7,768|             7.8|
|                55|           1,263|             1.3|
|                56|             90|             0.1|
|                57|              2|             0.0|
|                58|              0|             0.0|
|                59|              0|             0.0|
|                60|              0|             0.0|

##### N.C. Attorney General, 2020 (D +0.1)
![attorney_general20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_attorney_general20_mcd.png)
| Democrats elected| Number of maps| Percent of maps|
|-----------------:|--------------:|---------------:|
|                50|              0|             0.0|
|                51|              0|             0.0|
|                52|             14|             0.0|
|                53|            524|             0.5|
|                54|           4,688|             4.7|
|                55|          20,876|            20.9|
|                **56**|          **36,025**|            **36.0**|
|                57|          26,908|            26.9|
|                58|           9,434|             9.4|
|                59|           1,424|             1.4|
|                60|            102|             0.1|
|                61|              5|             0.0|
|                62|              0|             0.0|
|                63|              0|             0.0|
|                64|              0|             0.0|
|                65|              0|             0.0|

### Comparing outcomes by district
The charts below show the percentage of the vote for the Democratic candidate for each district from most Republican to most Democratic, calculated by re-sorting precinct level results from 2020 races into each of the 100,000 district plans created by the Duke Quantifying Gerrymandering team.

The dot indicates the same percentage using votes re-sorted into the 2021 map proposal, again sorted from most Republican to most Democratic.

#### N.C. Senate proposal (SST-13, [SB 739](https://www.ncleg.gov/BillLookUp/2021/S739), 2nd edition)

##### U.S. President, 2020 (R +0.7)
![us_president20](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_box_us_president20_mcd.png)

##### U.S. Senate, 2020 (R +0.9)
![us_senate20](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_box_us_senate20_mcd.png)

##### N.C. Governor, 2020 (D +2.3)
![governor20](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_box_governor20_mcd.png)

##### N.C. Lt. Governor, 2020 (R +1.6)
![lt_governor20](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_box_lt_governor20_mcd.png)

##### N.C. Attorney General, 2020 (D +0.1)
![attorney_general20](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/sst13_2e_box_attorney_general20_mcd.png)

#### N.C. House proposal (HBK-14, [HB 976](https://www.ncleg.gov/BillLookUp/2021/H976), 3rd edition)

##### U.S. President, 2020 (R +0.7)
![president20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_box_president20_mcd.png)

##### U.S. Senate, 2020 (R +0.9)
![us_senate20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_box_us_senate20_mcd.png)

##### N.C. Governor, 2020 (D +2.3)
![governor20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_box_governor20_mcd.png)

##### N.C. Lt. Governor, 2020 (R +1.6)
![lt_governor20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_box_lt_governor20_mcd.png)

##### N.C. Attorney General, 2020 (D +0.1)
![attorney_general20_chart](https://github.com/mtdukes/redistricting2021/blob/main/media/charts/hbk14_3e_box_attorney_general20_mcd.png)

***NOTE: The results here are PRELIMINARY and are subject to change as additional verification, fact-checking, etc. takes place. If you spot any errors, please contact [Tyler Dukes](mailto:mtdukes@newsobserver.com).***

## Methodology
***NOTE: The results here are PRELIMINARY and are subject to change.***

Reporters at The News & Observer used statistical software to match block assignment files describing the shape of electoral districts provided by the N.C. General Assembly with [block-level election data](https://git.math.duke.edu/gitlab/gjh/redistricting2020results/-/blob/main/NC/Shapefiles/cblocks_w20210812Pcts.zip) calculated by the Duke University Quantifying Gerrymandering team.

To ensure accuracy, reporters compared resulting district-level population counts with the legislature's "stat pack" files showing population counts and deviation for each district. Reporters also compared calculated county-level election results to county-level results from the 2020 precinct sort file provided by the State Board of Elections.

For each race studied (this analysis focused on 2020 contests), reporters generated a count of Democrats elected, defined as a two-party election result above 50%, for each map proposal. This figure was then compared to the distribution of Democrats elected in each race across all 100,000 maps, values provided by the Duke Quantifying Gerrymandering team. These distributions are depicted in histograms to show how the performance of a given proposal compares to the "ensemble" or map collection.

The results shown here arbitrarily use "Democrats elected" to stay consistent with the Duke analysis. The findings would be identical (but inverse) if we used "Republicans elected."

The Duke team generated map collections that kept municipal boundaries whole to the greatest extent possible, as well as collections that did not consider municipal boundaries. The bulk of this analysis focuses on maps that are weighted toward whole municipal boundaries.

For the district-level analysis, reporters plotted the distribution of the vote percentage for Democratic candidates across all 100,000 maps for each district, ordered from most Republican to most Democratic. They then plotted the vote percentage for Democratic candidates for the proposed map in each district using the same order. Distributions for the ensemble of maps is shown in a boxplot, with the box representing 50% of the outcome and a horizontal line marking the median value. Lines (or "whiskers") extend outward to show the range of values in the distributions.

***NOTE: The results here are PRELIMINARY and are subject to change as additional verification, fact-checking, etc. takes place. If you spot any errors, please contact [Tyler Dukes](mailto:mtdukes@newsobserver.com).***

## Source data
***NOTE: The results here are PRELIMINARY and are subject to change.***

### Map proposal files
- [Member-submitted block assignment files// N.C. Senate](https://www.ncleg.gov/Committees/CommitteeInfo/SenateStanding/154#2021%5CMember%20Submitted%20Maps)
- [Member-submitted block assignment files// N.C. House](https://www.ncleg.gov/Committees/CommitteeInfo/HouseStanding/182#2021%5CMember%20Submitted%20Maps)

### Election result files
- [2020 precinct sort file // N.C. State Board of Elections](https://dl.ncsbe.gov/?prefix=ENRS/2020_11_03/results_precinct_sort/)
- [Block-to-precinct result crosswalk // Duke Quantifying Gerrymandering team](https://git.math.duke.edu/gitlab/gjh/redistricting2020results/-/blob/main/NC/Shapefiles/cblocks_w20210812Pcts.zip)
- [N.C. House vote distribution data // Duke Quantifying Gerrymandering team](https://git.math.duke.edu/gitlab/gjh/redistricting2020results/-/tree/main/NC/Ensembles/House)
- [N.C. Senate vote distribution data // Duke Quantifying Gerrymandering team](https://git.math.duke.edu/gitlab/gjh/redistricting2020results/-/tree/main/NC/Ensembles/Senate)

### Population files
- [2020 N.C. redistricting file // U.S. Census Bureau](https://www2.census.gov/programs-surveys/decennial/2020/data/01-Redistricting_File--PL_94-171/North_Carolina/)

### Convenience files
- [County FIPS codes](https://gist.githubusercontent.com/mtdukes/ff6e59acde4858a8b174a83d2fce915c/raw/c32f49e339c3dc2340111f0f6174ee21a7f2fc5d/us_fips_tab.tsv)

***NOTE: The results here are PRELIMINARY and are subject to change as additional verification, fact-checking, etc. takes place. If you spot any errors, please contact [Tyler Dukes](mailto:mtdukes@newsobserver.com).***