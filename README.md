# The Rise of Home Schooling
## Data from The Post's analysis of home-schooling enrollment across the US

This repository shares data hand-collected by The Washington Post from individual school districts and states as a whole regarding home-school enrollment from 2017-18 through 2022-23. The data is what is behind this [story](https://www.washingtonpost.com/education/interactive/2023/homeschooling-growth-data-by-district/) published on Oct. 31, 2023 by Peter Jamison, Laura Meckler, Prayag Gordy, Clara Ence Morse and Chris Alcantara.

There are two separate data files, both of which cover the same time period: 
- [home_school_district.csv](https://github.com/washingtonpost/data_home_schooling/blob/main/home_school_district.csv)
- [home_school_state.csv](https://github.com/washingtonpost/data_home_schooling/blob/main/home_school_state.csv)

There is also a data [dictionary](https://github.com/washingtonpost/data_home_schooling/blob/main/home_school_data_dictionary.csv) explaining each file.

## Methodology
To measure the growth of home schooling during the pandemic, The Washington Post collected home-school student counts from 6,738 school districts. Together with students from The Washington Post Investigative Reporting Workshop practicum at American University, reporters trawled state websites, contacted education officials in all 50 states and the District of Columbia and submitted multiple public records requests for an annual count of home-schoolers from the 2017-18 school year through 2022-23. The Post ultimately collected data for all public school districts in 29 states and D.C. In all, The Post gathered data from states representing 61% of the American school-age population.

Three states — Pennsylvania, Rhode Island and Tennessee — have not published the number of home-schoolers in 2022-23, and Maine only shared district-level data starting with the 2020-21 school year. In seven states, The Post was unable to obtain usable home-school enrollment figures: In Arizona, Nevada and Oregon, only new home-school registrations are tracked annually at the district level; in North Carolina, home-school registration rolls are not regularly purged as students age out of the system; and in West Virginia, Utah and Alabama, annual enrollment data is unavailable. Eleven additional states do not require any notice when families decide to home-school their children, so enrollment figures in those states are also unavailable. Finally, Montana, Vermont and Nebraska collect data at a county level, not a district level, so there is no district data available.

The Post made every effort to capture all legal ways to home-school, which vary by state. However, data on home schools established by certain methods, such as registering one’s home-school as a private school, are tracked by some states but not others. That means The Post’s tally is almost certainly an undercount, even in the states from which it gathered data. For instance, Wisconsin and Georgia only provided The Post with tallies of home-schoolers who had submitted required forms electronically. In Kentucky, some districts incorrectly reported zero or one home-schooled students in certain years, which a state education official attributed to an unclear form. The Post excluded those enrollment figures from its analysis. In California, which does not explicitly permit home schooling, many parents operate home-based private schools. The California Department of Education characterizes private schools with five or fewer students as home schools. In Louisiana, many home schools operate as nonpublic schools not seeking accreditation; The Post counted such schools with five or fewer students as home schools as well.

The statewide numbers are not always equivalent to the sum of all district totals in a state. Some states suppress district-level counts of home schoolers below a certain threshold. In Maine, the threshold is 5; in New Mexico, 6; in Mississippi, Ohio and Tennessee, 10; in Wisconsin before 2020-21, 5; and in Wisconsin from 2021-22 on, 20. The Post marked such suppressions as NA within its data. In addition, New Hampshire collects separate data on students who enter home schooling from schools run by the state department of education or from private schools; these additional students are reflected in state data but not district data. 

The Post used a variety of methods to match each school district name to an NCES district id. However, this was not always possible. In Georgia, families self-report their school district on home-schooling forms; some report programs which are not school districts, and therefore have no corresponding NCES id. In California, families were only required to report county and school district beginning in 2020-21; in addition, district mergers and name changes mean that some districts could not be matched with NCES ids. In Arkansas, 12 home-schoolers reported no school district in 2022-23. The Post marked all such home-schoolers as being within NA districts.

## Contact & Contributing
Please reach out with any questions about the data, feedback, updated information or corrections. Before you do, take a moment to review the [Code of Conduct](https://github.com/washingtonpost/data-police-shootings/blob/master/CODE_OF_CONDUCT.md).

Please note that we do not accept pull requests.

## Licensing
The data is published under an Attribution-NonCommercial-ShareAlike 4.0 International CC BY-NC-SA 4.0 license.

## Credits
Data analysis, standardizing and cleaning by Prayag Gordy and Clara Ence Morse.

Ibrahim Aksoy, Alexander Fernandez, Nami Hijikata, Soléne Guarinos, Lalini Pedris, Emily Seymour and Annie Rupertus from the Investigative Reporting Workshop at American University contributed to the data collection. 

Editing by Lynda Robinson, Meghan Hoyer, Reuben Fischer-Baum, Mark Miller, Mark Gail, Jay Wang and Christian Font. Copy editing by Brian French. Design by Jennifer C. Reed. Animation by Emma Kumer.
