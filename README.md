
Generates 1,000 samples of size n=10, 100, 1,000, and 10,000 from the distribution Gamma(2,4)

Response to the question below, followed by histograms and q-q plots for each of the three sample sizes of interest:

https://cloud.githubusercontent.com/assets/6961260/7851298/d016d1e6-051f-11e5-861a-caff58a54820.png
https://cloud.githubusercontent.com/assets/6961260/7851300/d54df9be-051f-11e5-9b03-21ff0d2250ac.png
https://cloud.githubusercontent.com/assets/6961260/7851301/d93b9f22-051f-11e5-972c-40a225a15c74.png
https://cloud.githubusercontent.com/assets/6961260/7851302/de8289aa-051f-11e5-92a1-0d6fee65dd3d.png
https://cloud.githubusercontent.com/assets/6961260/7851305/e58a79ec-051f-11e5-8035-d22423db8534.png
https://cloud.githubusercontent.com/assets/6961260/7851307/eaa419ce-051f-11e5-9843-7ff620e8d4e1.png
https://cloud.githubusercontent.com/assets/6961260/7851308/ed61e786-051f-11e5-9388-de3d0dfa6853.png
https://cloud.githubusercontent.com/assets/6961260/7851309/f1518702-051f-11e5-80e9-e839a82d9c05.png

This study extends Barro and Sala-i-Martin’s analysis of the presence of β and σ convergence across US states from 1880 through 1990, examining whether or not these two types of convergence are still present from 1997 to 2013. This study also finds β convergence, or that states that started with a lower level of income per capita in 1997 grew faster from 1997 to 2013. However, whereas Barro and Sala-i-Martin conclude that σ convergence, or the narrowed dispersion of income per capita levels among U.S. states over time, occurred from 1880 to 1990, this trend did not continue from 1997 to 2013. The dispersion of GDP per capita among US states continued to decline until 2003, but began to increase directly prior and over the course of the Great Recession (2007-2009).

 1.FINDING β CONVERGENCE

The growth rate of GDP per capita from 1997, the base year used in this study, to 2013, was calculated using data on real GDP per capita by U.S. State, in terms of chained 2009, from the Bureau of Economic Analysis. In order to derive β, or the measure of the rate at which poorer US states converge on or fall behind the levels of GDP per capita of richer US states over the course of the time period 1997-2013, Barro’s population model in Figure 1 below is estimated, as shown in Appendix A. After the OLS regression of this model is estimated, β can be determined by deriving the β in the coefficient of the log of the initial GDP per capita, or income per capita for states during the base year 1997. If β < 0 and if the coefficient of initial income per capita is statistically significant, the income per capita of poorer states converged on the levels of richer states. However if β > 0 and/or not statistically significant, β convergence did not occurred.

https://cloud.githubusercontent.com/assets/6961260/7851901/86e999f0-0528-11e5-93cc-a454deabe071.png

Figure 1: Population Model used to derive β Convergence 

The OLS regression results below resulted from the regression of the natural log of the GDP per capita across states in the base year on 
the average growth rate in per capita income across US states. The coefficient on the log of the base year is not statistically significant, with a p-value of 0.170.

https://cloud.githubusercontent.com/assets/6961260/7851902/86ee139a-0528-11e5-91cf-cc151ed800b4.png 
https://cloud.githubusercontent.com/assets/6961260/7851903/86f154c4-0528-11e5-88d8-b42c4c9984e3.png   

Since the coefficient on log of the real GDP per capita in the base year 1997, is a function of β convergence and the time period of interest T, as depicted in Figure 2 below, the insignificance of the coefficient means that the β convergence solved for using this coefficient is also statistically insignificant. Including the District of Columbia among US states attributes to the insignificance of the coefficient on initial income, as the GDP per capita in DC over the time period of interest ranges from $130,000 to $170,000, over twice as high as the GDP per capita levels of other states.

https://cloud.githubusercontent.com/assets/6961260/7851904/86f49ddc-0528-11e5-83c2-20f6243329ba.png
                           
Figure 2: Coefficient Equation Used to derive β 

The OLS regression results were obtained after dropping the time series observation of income per capita for over time in Washington DC from the sample. The coefficient on the income per capita in the base year is statistically significant at the 0.05 level of significance with a p-value of 0.042. These results can be interpreted as an increase in the in the initial income per capita in the base year by one percentage point, holding all other factors fixed, results in a decrease in the growth rate of GDP per capita over the time period of interest by about 0.0131%, meaning that poorer states grew faster on average from 1997-2013 compared to initially wealthier states.

https://cloud.githubusercontent.com/assets/6961260/7851905/86f66f18-0528-11e5-86c0-0ff0b284750e.png
https://cloud.githubusercontent.com/assets/6961260/7851906/86fa5cf4-0528-11e5-81eb-eb68c08df4cf.png

Using the equation in Figure 2, β is derived to be approximately -0.01187, as shown in Appendix C. This value of β can be interpreted as poorer US states converging on the income per capita levels of richer states by 1.187% from 1997 to 2013. Therefore, the findings in this study imply that β convergence among US states exists from 1997 to 2013, extending the findings of Barro and Sala-I-Martin for previous time periods.

2. FINDING σ DIVERGENCE

σ divergence occurred among states, or the dispersion in the income per capita levels of US states increased, determined by first calculating the coefficient of variation for year from 1997 to 2013, and then regressing time on the dependent variable containing CV for each year. If the coefficient on time is negative and statistically significant, then σ convergence occurred. If not then σ convergence did not occur from 1997 to 2013, or the trend of σ convergence found by Barro and Sala-I-Martin for previous periods did continue over the past sixteen years. Calculating the coefficient of variation, or a standardized measure of the dispersion of the probability distribution of each variable for GDP per capita for US states in a given year, the following results depicted in Figure 3 were obtained:

https://cloud.githubusercontent.com/assets/6961260/7851907/86fc5de2-0528-11e5-9466-3e425ac46f9e.png
  
Figure 3: CV for Real Income per Capita across US States from 1997-2013

The CV for each year results from dividing the standard deviation of the variable income per capita for a given year by its mean, with the standard deviation and mean of the variable for each year from 1997 to 2013 being calculated in Stata as shown in the part 1 of Appendix A and the corresponding output to this Stata code depicted in part 1 of Appendix B. By looking at the CV values in the fourth column of Figure 3, we can conclude that CV2013 > CV1997, or that σ convergence did not occur over the time period in question. Figure 4 below depicts the trend in CV over the course of 1997 through 2013, with a decrease in CV until t = 7, corresponding to the year 2003. Past 2003, the dispersion in the income per capita of US states increased steadily until 2013, with the exception of the point t = 13 corresponding to the year 2009. In the year 2009, the dispersion of income per capita among US states was exceptionally high, with this year corresponding to the depth of the Great Recession, as discussed in the analysis section below. Even though σ convergence occurred from 1997 to 2003, the income per capita levels diverged at a greater rate from 2003 to 2013, overshadowing any σ convergence that took place from 97-03 and, subsequently, resulted in an overall trend of σ divergence from 1997-2013.

https://cloud.githubusercontent.com/assets/6961260/7851908/870080fc-0528-11e5-8744-6f57f9360c6e.png 

Figure 4: Graph of CV from 1997-2013

The strength of the evidence against σ convergence is verified through the regression results of time on the variable CV, obtained using commands depicted in part 2. of Appendix A. The coefficient on the variable for time of 0.0008969 is derived by estimating the population model below and can be interpreted as, holding all other factors constant, the coefficient of variation increased by 0.0008969 from one year to the next. Not only does σ divergence occur from 1997-2013, but this growth of CV over time is statistically significant at the 5% and 10% levels of significance, with a p-value of 0.029 on the coefficient of time.

https://cloud.githubusercontent.com/assets/6961260/7851909/87013dee-0528-11e5-9e12-c73881e1663f.png                       
