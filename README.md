# Udacity_Project_Tableau_Story
The focus of this project will be to create a data visualization using Tableau that tells a story or highlights trends or patterns in a data set. This will a reflection of the theory and practice of data visualization, such as visual encodings, design principles, and effective communication.

## Summary

This data visualization project focuses on analyzing those accounts in the Prosper Loans dataset which have single or multiple verified delinquencies. A concerted attempt has been made to generate visualizations which first show aggregated measures at the state level and then become more granular and segmented with the progression of the Tableau story. 


## Design

The design choices made during the course of this project can be broken down according to the three dashboards which make up the final Tableau story. 

## Dashboard 1 – Top 10 States by Delinquencies

The purpose of this dashboard is to provide the viewer with a state-level view of the problem of delinquencies in the Prosper Loans dataset. Initially, it would have featured information on every state. However, in accordance to the suggestions made during the feedback portion of the project, this was then focused on the top ten states by applying filters to the visualization. An orange to gold color scheme was also implemented to give off a heat-map effect. A pie chart showing the overall proportion of delinquencies of the top 10 states versus the rest of the states in the US was also imbedded following the feedback round. For this chart, a set of top-10 and non-top-10 states was created as a means of differentiation

For additional clarity, a table listing the total delinquent amounts for every state was also imbedded into the map visualization. Then the option to use the map visual as the primary filter was selected so that users could drill down to the details of every state. The bottom half of the dashboard is made up of a line-chart which shows the total number of delinquencies spread over the various fiscal quarters in the dataset. Markers were also added to the line-chart to indicate the positions of the different quarters. Finally, a horizontal bar chart was added which features the total amounts of delinquencies according to the employment status mentioned in the dataset. A text field was added to show precise values to the viewers. Both visualizations can change to show information on individual states in the map view.

## Dashboard 2 – Delinquency Information by Employment Status 

This dashboard allows the viewers to take a closer look at various features associated with delinquent accounts, based on the employment status of the account holders. A horizontal bar chart was created for this purpose. The initial design of this dashboard only featured aggregated values based on the total amounts and numbers of delinquencies. However, in keeping with the feedback suggestions listed below, a calculated field was created to show delinquency rates instead.  This calculated field, in addition to Total Credit Lines and Total Delinquencies would be used in the remainder of the analysis. To top things off, the bar chart also incorporated proportions of home-owners to non-home-owners for each employment status.

Following this, a line chart showing the various borrower APRs for every employment status was added to the bottom of the chart. Although it may look very busy at first glance, the viewer can simplify it by choosing a specific employment status at the top of the dashboard. This, in addition to the added trend line, gives a very clear view of the trend of borrower APRs. Further drilling-down can also be achieved if the viewer selects ‘Home- Owner’ or ‘Not Home Owner’ on the bar chart.

Additionally, a scatterplot is added to the bottom right corner, which shows the delinquency rate against the total credit lines issued to the various occupations. This view also adjusts according to the choices made in the employment status bar chart.

## Dashboard 3 – Delinquency Information by Occupation

The last part of the Tableau story is meant to convey information about the delinquency rates, debt to income ratios, prosper ratings, prosper scores and average days delinquent according to the various occupations provided in the dataset.

The primary visualization in this dashboard is the horizontal bar chart which lists each occupation and arranges it according to the delinquency rate. To add an interesting contrast, the bars were then colored according to the debt-to-income ratios of every occupation. Below this, a vertical bar chart was generated which segments the occupations according to the various earning brackets, starting from $0 to $100,000+. Within this view, color gradients were added to highlight the differences in average days of loan delinquencies for every segment, with darker colors indicating longer time periods. 

The three supporting visuals on the right-hand side feature a scatterplot which shows the delinquency rate and average debt-to-income ratios for employment statuses within each occupation. The choice to add this plot was made intuitively given the variability of employment statuses in these economically disruptive times. Below the scatterplot are two vertical bar charts which show both the Prosper Rating (Alpha) and the Prosper Score for every occupation according to total number of delinquencies.

As before, the primary visualization in this dashboard is the chart listing the occupations and their delinquency rates. The filter option on this chart was also applied to every other chart in the dashboard

## Feedback

In order to get meaningful feedback on my visualizations, I solicited the help of my current line manager and colleagues who are much more experienced in using Tableau for visual analysis. I skipped the online option in favor of a face-to-face feedback session. The various suggestions made include:

1. Making the analysis more granular by looking at information from the perspective of top 10 states by delinquencies and not every state. This filtering of the data should be applied to every worksheet. 
2. Instead of solely focusing on summed or averaged values for delinquency amounts, a calculated field which shows delinquency rates should be featured instead.
3. The analysis should be made even more granular by differentiating between the various segments of income groups.
4. Add a small pie chart to show proportion of delinquencies for top ten and the rest of the States to the first dashboard.




