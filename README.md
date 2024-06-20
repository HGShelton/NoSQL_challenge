Tech Used: pymongo, pprint

Credits:
- # Xpert Learning Assistant was used to identify missing piece of code to change data type - 'geocode.'
- # ChatGPT was used to identify radius code - '{'$gte': latitude - degree_search, '$lte': latitude + degree_search}'

Import the dataset with `mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json`

The top ten results for each inquiry are below:

Establishments with a hygiene score equal to 20:
- The Chase Rest Home
- Brenalwood
- Melrose Hotel
- Seaford Pizza
- Golden Palace
- Ashby's Butchers
- South Sea Express Cuisine
- Golden Palace
- The Tulip Tree
- F & S

Establishments in London with a rating value greather than or equal to 4:
-Charlie's
-Mv City Cruises Erasmus
-Benfleet Motor Yacht Club
-Coombs Catering t/a The Lock and Key
-Tilbury Seafarers Centre
-Mv Valulla
-Tereza Joanae
-City Bar & Grill
-WH Smith
-The Nuance Group (UK) Limited

The top 5 establishments with a rating value of 5, sorted by lowest hygiene score, nearest Penang Flavours:
-Volunteer
-Plumstead Manor Nursery
-Atlantic Fish Bar
-Iceland
-Howe And Co Fish and Chips -Van 17

A count of establishments in each local authority area that have a hygiene score of 0, sorted from highest to lowest:
- Thanet (1130)
- Greenwich (882)
- Maidstone (713)
- Newham (711)
- Swale (686)
- Chelmsford (680)
- Medway (672)
- Bexley (607)
- Southend-on-Sea (586)
- Tendring (542)