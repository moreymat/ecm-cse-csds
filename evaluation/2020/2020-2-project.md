# Project

## Data

You will work on an extract from OpenFoodFacts filtered to keep 29 columns, and only the entries that are marked "complete".

You can download the CSV file from the servers at Centrale :
`/users/prof/mmorey/datasets/off_complete.csv` .

You should be able to download it from the command line :
`scp yourlogin@sas2.centrale-marseille.fr:/users/prof/mmorey/datasets/off_complete.csv .`

## Subject

You need to write Jupyter notebooks that contain :
- An analysis of the products, with dataviz showing characteristics of certain product groups, similarities between products and product groups, etc. Your goal here should be to provide a global view of the dataset, and exhibit salient features that are of interest for an analyst or stakeholder in this sector ;
- A set of prediction models that are able to:
  * predict the `nutriscore_grade` of a product given nutritional values and possibly other fields (as few as possible),
  * predict the `nova_group` of a product given nutritional values and possibly other fields (as few as possible),
  * predict the `pnns_groups_1` of a product given nutritional values and possibly other fields (as few as possible),
  * predict the `pnns_groups_2` of a product given nutritional values and possibly other fields (as few as possible),
  * predict the `categories` (either atomic categories or lists of categories) of a product given nutritional values and possibly other fields (as few as possible),
  * predict one or more nutritional values (ex: `sugars_100g`) given nutritional values and possibly other fields (as few as possible).

The analysis and prediction can be done for all categories together, or for specific categories separately.

The deliverable should consist in a set of Jupyter notebooks, broken down by product category or prediction.
  
## Delivery

You need to send your set of notebooks by email :
- at <mathieu@datactivist.coop>
- before 2020-11-06, 10am.

