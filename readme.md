# Ford GoBike Exploration
## by Jonathan Obise


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

> Bay Wheels (Formerly Ford GoBike) is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is 'the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.

> In June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company. After Motivate's acquisition by Lyft, the system was renamed to Bay Wheels in June 2019. The system is expected to expand to 7,000 bicycles around 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose.

> To prepare the data, I loaded it in from a csv file and converted the start and end time columns to datetime, extracted the dayofweek and hours information from the start_time variable and converted the start_time_dayofweek to ordinal variables.


## Summary of Findings

> In the exploration, I found that there are more subscribers compared to customers who use the bikesharing service. Also, subscribers mostly used the service to commute to work while customers mostly used it for pleasure. In adittion, I found out that the average trip duration on weekends was longer than trips on weekdays.


## Key Insights for Presentation

> For the presentation, I tried to display plots from the three different exploration that could better present the relationships I observed. I started by displaying the univariate visualizations, followed by the bivariate visualizations and then the multivariate visualizations of the relationships between the variables.

> In addition to all these and to better understand the data, I analyzed the Biker types, weekday trip duration, daily/hourly trip duration and more. 

## Reference
> https://www.kaggle.com/residentmario/bivariate-plotting-with-pandas
> https://mgimond.github.io/ES218/Week09a.html
> https://seaborn.pydata.org/generated/seaborn.FacetGrid.html#seaborn.FacetGrid
> https://seaborn.pydata.org/tutorial/distributions.html
