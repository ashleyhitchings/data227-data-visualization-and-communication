# Data 22700 Data Visualization and Communication
Datasets and visualizations were cleaned and produced using Pandas, NumPy, Altair, MatPlotLib, and NetworkX and PyVis (networks) libraries in Python and were created for DATA 22700: Data Visualization and Communication, a data science elective at UChicago. 

### Twitter Interactions Between the Most-Followed U.S. Congresspeople (2015)
Data Source: Pablo Barbera (GitHub: pablobarbera), “Data Science Workshop - Congress Twitter Network,” https://github.com/pablobarbera/data-science-workshop/tree/master/sna/data. Note: though the source does not specify when the data was pulled from Twitter, the files were uploaded to GitHub in 2015, which is assumed to be the year of data collection.*

<p align="center"><img width="468" alt="congress_twitter_network" src="https://user-images.githubusercontent.com/72634325/147860824-5acf62cc-aaa1-4f2d-afe1-37358226de91.png"></p>

*Among the thirty most-followed Congresspeople on Twitter in 2015, fifteen belonged to the Republican party, fourteen to the Democratic party, and one to the Independent party, representing a balanced composition across party lines. Senator John McCain had the largest following at nearly 2m followers and Sen. Bernie Sanders trailed at 1.2m, followed successively by House Minority Leader Nancy Pelosi, Sen. Ted Cruz, Speaker of the House Paul Ryan, and Senator Elizabeth Warren. For both Democrats and Republicans, most Congresspeople primarily interacted with members of their own party on Twitter, a trend especially prominent for party leaders Pelosi and Ryan, who appear at opposite sides of the network. Nevertheless, there exists a large amount of cross-party digital interaction senators and representatives at the lower end of the top 30, including Sen. Tim Scott, Sen. Chuck Schumer, and Sen. Dick Durbin. Additionally, a subset of politicians who hold relatively radical positions within their party, including Senators Warren and Sanders, appear to display high cross-party Twitter engagement, though further research is necessary to substantiate this finding.*

### Mapping Human Rights Across the World
Data Sources: Schnakenberg and Fariss (2014); Fariss (2019). Note: Scores were produced from an econometric model that combines metrics from nine other sources.

![world_human_rights](https://user-images.githubusercontent.com/72634325/147860926-2c9eb3ce-33b8-4507-9a1e-aa3b867fdabe.png)

As illuminated in the figure above, most countries had Human Rights Scores (HRS) close to or below zero in 2017, with the majority of low-protection countries in Africa, and the highest concentration of high-protection countries in Western Europe and Scandinavia. While South Sudan, Syria, and Myanmar, among others, expectedly displayed low levels of protection for citizen’s physical integrity, North Korea was the fifth worst country for HR protection, despite its notorious reputation. Meanwhile, the U.S. had a HRS of 0.2, far lower than expected given the country’s reputation for peace-keeping and democracy.

![world_human_rights_diff](https://user-images.githubusercontent.com/72634325/147860937-0f26a92c-0b56-42b2-9445-0fbcd1577fa0.png)

 Notably, the second figure reveals that human rights protections in the U.S. declined over the period, even as most countries in the world progressed, indicated by positive changes in their HRS. Nearly every country in South America improved, as did most in Europe, Asia, and Africa. Altogether, recent data on the state of global human rights reveal low levels of protection across most of the world, with some countries displaying surprising results relative to their reputations for oppression or humanitarian intervention. However, whether due to the march of progress, regime change, or random factors, the majority of countries have advanced in protecting citizens’ physical integrity over the last several decades, especially in areas considered ‘developing’ regions of the world, such as Africa, Asia, and Latin America. 
 
 ### U.S. Births - Sites of Delivery by Time of Day
 Data source: CDC Birth Data Files, 2019. 
 
 ![fig_final_2](https://user-images.githubusercontent.com/72634325/147860984-d19db727-9ea9-4dfa-b97d-22c2e0e8d32d.jpg)

Overall, in 2019, the vast majority of births in the U.S. occurred in hospitals, with the highest density of hospital deliveries occurring between the hours of 7:00 a.m. and 6:00 p.m., peaking during the hour following 8:00 a.m. After hospitals, homes and freestanding birth centers were the next two most common sites of delivery. Unlike the hourly distribution for hospitals, however, homes and freestanding birth centers experienced the highest volume of births in the early morning and late evening, representing an inverse trend across the hours of the day. Intended births at home peaked around the hours of 3:00 a.m. and 11:00 p.m., with deliveries at freestanding birth centers displaying a similar pattern. Interestingly, unintended births at home—though significantly less frequent than hospital, birth center, and intended home births) also saw a peak in frequency around 3:00 a.m. Whether hospital births peak during the workday due to modern medical practices (e.g. cesarian sections) can only be inferred from the data, but the visualization suggests that freestanding birth centers and homes may represent alternative delivery sites for mothers who enter labor at unexpected or odd hours of the day—or do not use medical techniques to induce birth during the hours of daylight.

