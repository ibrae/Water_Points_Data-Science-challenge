# Water_Points_Data-Science-challenge
-Implement a data processing module in python which takes a dataset URL as input and returns:
● The number of water points that are functional,
● The number of water points per community,
● The rank for each community by the percentage of broken water points.
## There should be a top level object or function calculate(“http://...”), which returns a data
structure with the above information, something like:
{
number_functional: ...,
number_water_points: {
communityA: ...,
},
community_ranking: ...
}
But that’s just a suggestion and we can think of alternative, maybe better, data structures
to use.
## We will use a water point dataset that contains many columns, the relevant ones are:
- communities_villages, water_functioning
## The data can be found on this URL(https://raw.githubusercontent.com/onaio/ona-tech/master/data/water_points.json)

# - follow JTP.ipynb for step by step implementation of the above

# - open the analysis.json file to view result in json format
