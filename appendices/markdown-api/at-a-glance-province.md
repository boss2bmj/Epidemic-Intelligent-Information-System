## POST /api/v1/hiv/at-a-glance/province/:provincel               
## body
``` javascript
{
	"disease": {
		"criteria": "all",
		"disease": "hiv"
	},
	"location": {
		"data": {
			"province": 55,
			"region": 1
		},
		"mode": "province"
	},
	"time":{
		"cutoff": {
			"month": 3,
			"year": 2017
		},
		"interval": {
			"end":{
				"month": 3,
				"year": 2017
			},
			"start":{
				"month": 3,
				"year": 2017
			}
		},
		"mode": "all"
		
	}
}




```
## response 

``` javascript
{
  "summary": {
    "thai": {
      "total": 0,
      "alive": 0,
      "inSystem": 0,
      "lostFollowup": 0,
      "onDrug": 0,
      "vlActive": 0,
      "hasVL": 0,
      "vlSuppressed": 0,
      "foundWithinYear": 0,
      "OI": 0,
      "ipd": 0,
      "death": 0,
      "deathInyear": 0,
      "hivRelatedDeath": 0,
      "deathBeforeDrug": 0
    },
    "foreign": {
      "total": 0,
      "alive": 0,
      "inSystem": 0,
      "lostFollowup": 0,
      "onDrug": 0,
      "vlActive": 0,
      "hasVL": 0,
      "vlSuppressed": 0,
      "foundWithinYear": 0,
      "OI": 0,
      "ipd": 0,
      "death": 0,
      "deathInyear": 0,
      "hivRelatedDeath": 0,
      "deathBeforeDrug": 0
    }
  },
  "byRegion": ""
}
```