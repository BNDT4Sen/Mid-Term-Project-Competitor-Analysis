# Mid-Term-Project-Competitor-Analysis
The goal of this project was to identify potential areas of opportunity within Vancouver based on nearby competition. 

## API_Requests
Raw data was retrieved from the Google Places and Yelp APIs.

## API_Data
The data collected includes a file identifying SkyTrain stations located on the Canada and Expo lines, as well as a file of restaurants from both the Yelp and Google API requests. 

## Data_Cleaning
Distances between points were calculated using coordinates and a handy package called Haversine. This information was appended to the Yelp and Google DataFrames.
These DataFrames were then standardized and merged.

## Cleaned_Data
The csv file in this folder represents the DataFrame that our Tableau visualizations and prediction model are based on.

## Prediction_Model
It quickly became apparent that a statistically significant relationship between the variables was not going to be found. Instead focus was shifted to data visualization, and in particular, geographically using Tableau maps. This ended up being a solid decision, as enhanced visuals gave us a much stronger grasp on the data we had collected.

## SkyTrain_Venue_Visualizations
We created 4 dashboards all covering similar but separate areas. They can be found annotated in the SkyTrain Restaurants Visualization story.

Link to Tableau Visualizations:
https://public.tableau.com/views/Mid-Term-Visualizations/SkyTrainRestaurantsVisualization?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link