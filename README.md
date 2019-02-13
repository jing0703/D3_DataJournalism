# Data Journalism by D3

## Preview
This application provides analysis and visulization for the health risks faced by various demographics

[View Website](https://d3-times.herokuapp.com/)

## Method and Usage

### Step 1: Data ETL development

  * Demographic information is pulled from the [U.S. Census Bureau's American Community Survey](http://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml)
  
  * Data for health risk factors is collected from the [Behavioral Risk Factor Surveillance System](https://chronicdata.cdc.gov/Behavioral-Risk-Factors/BRFSS-2014-Overall/5ra3-ixqq)
  * Combine and clean up two datasets by pandas
  
### Step 2: Data visulization 
  * Create a scatter plot by d3.js between two of the data variables such as Healthcare vs. Poverty or Smokers vs. Age

  * Incorporate d3-tip.js plugin to display detailed information for each circle when user hovers their cursor over the element
  
  * Build click events to make the chart dynamics and interactive and allow users to select risk factors for each axis
  
  * Animate the transitions for each data's location as well as the range of the axes
