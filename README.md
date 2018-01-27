# strava_exp
playing with the strava api, this is really just a knowledge capture for myself. 

strava:
http://strava.github.io/api/

not sure why this page doesn't accept my creds and auth me:
 https://developers.strava.com/playground/#/Athletes/getStats

```curl -X GET https://www.strava.com/api/v3/athletes/23261551 -d access_token=ACCESS_TOKEN -H "accept:application/json"

curl -X GET https://www.strava.com/api/v3/activities -d access_token=ACCESS_TOKEN -H "accept:application/json"

curl -X GET https://www.strava.com/api/v3/athlete -d access_token=ACCESS_TOKEN -H "accept:application/json"

generated from developers playground link above:

curl -X GET "https://www.strava.com/api/v3/athletes/23261551/stats?page=3&per_page=30" -d access_token=ACCESS_TOKEN -H "accept:application/json"```
