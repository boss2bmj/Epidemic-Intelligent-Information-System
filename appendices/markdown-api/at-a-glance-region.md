## POST /api/v1/hiv/at-a-glance/region/:region               
## body
``` javascript
{
	"disease": {
		"criteria": "all",
		"disease": "hiv"
	},
	"location": {
		"data": {
			"region": 1
		},
		"mode": "region"
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
      "total": 13953,
      "alive": 13756,
      "inSystem": 11585,
      "lostFollowup": 2171,
      "onDrug": 8518,
      "vlActive": 25,
      "hasVL": 1341,
      "vlSuppressed": 9,
      "foundWithinYear": 804,
      "OI": 0,
      "ipd": 618,
      "death": 197,
      "deathInyear": 50,
      "hivRelatedDeath": 22,
      "deathBeforeDrug": 4
    },
    "foreign": {
      "total": 1586,
      "alive": 1550,
      "inSystem": 1122,
      "lostFollowup": 428,
      "onDrug": 1032,
      "vlActive": 6,
      "hasVL": 48,
      "vlSuppressed": 1,
      "foundWithinYear": 158,
      "OI": 0,
      "ipd": 78,
      "death": 36,
      "deathInyear": 15,
      "hivRelatedDeath": 8,
      "deathBeforeDrug": 5
    }
  },
  "byRegion": ""
}
```