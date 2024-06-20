Tech Used: pymongo, pprint

Credits:
- # Xpert Learning Assistant was used to identify missing piece of code to change data type - 'geocode.'
- # ChatGPT was used to identify radius code - '{'$gte': latitude - degree_search, '$lte': latitude + degree_search}'

Import the dataset with `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`
