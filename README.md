# Data Management Project

For this project, my research question centers around exploring the impact of gender on the prevalence and patterns of drunk driving among individuals who consume alcohol. According to the National Highway Traffic Safety Administration (NHTSA), research shows that in the United States, approximately 37 people die each day due to driving while intoxicated. Additionally, about 31% of car crash deaths in the United States involve drunk drivers (NHTSA, n.d.). Studies from previous experiments show that alcohol impairs both men and women significantly, but women show greater impairment than men (Miller et al., 2009). Furthermore, men are more likely to be current drinkers and to engage in heavy drinking compared to women (Wilsnack et al., 2009). Schwartz & Beltz (2018) found that male intoxicated drivers outdo female rates; however, female rates of intoxicated drivers are on the rise. I will be using data from the National Survey on Drug Use and Health (NSDUH) from 1996. The NSDUH is a series of surveys conducted to measure prevalence and correlated of substance abuse in the United States. The population is individuals over the age of 12, active-duty military, and individuals that are homeless in the United States. The NSDUH covers substance use, mental health, alcohol, tobacco, and other health issues. The variables in the dataset are of the types categorical and continuous. The units used for measurement are length in inches, weight in pounds, and counts.

I began manipulating the data by creating a smaller subset (DrugData2) and exporting it for analysis. Missing codes in alcohol and drunk driving-related variables were addressed by replacing them with NA and replacing certain codes like “did not drive drunk” or “did not use alcohol in the past 30 days” to 0. Additionally, the dataset was segmented into alcohol users and non-alcohol users based on drink counts, and a new categorical variable categorizing drinkers into three categories was created based on the number of drinks consumed.
