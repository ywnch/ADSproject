# Post-event Citi Bike Ridership Analysis of Barclays Center
### NYU CUSP Fall 2017 Appied Data Science Coursework Project

## Objectives

1. Predict Citi Bike demands for stations around Barclays Center
2. Identify ridership and popular destinations based on event types

## Data
### Events Data
- All 2016 events in Barclays Center via Facebook Fanpage API.
  
Caveats:

1. No end time from both FB and official website.
2. No event categories in FB data.
3. No event attendee numbers data.

Potential Solutions:

1. Manually assign reasonable categories and end time.
2. Find a list of 2016 concerts in Barclays Center in Wiki, which has "Tickets Sold" info.

### Citi Bike Data
- Retrieved from Citi Bike system data on the official website.

## Method
1. OLS multivariate regressions
2. K-means clustering