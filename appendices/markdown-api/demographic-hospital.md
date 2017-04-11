## POST /api/v1/hiv/demographic/hospital/:hospcode             
## body
``` javascript
{
 "nation": {
  "nation": "all"
 },
 "time": {
  "cutoff": {
   "month": 3,
   "year": 2017
  },
  "interval": {
   "end": {
    "month": 3,
    "year": 2017
   },
   "start": {
    "month": 3,
    "year": 2016
   }
  },
  "mode": "all"
 },
 "disease": {
  "criteria": "all",
  "disease": "hiv"
 },
 "location":{
  "mode": "hospital",
  "data": {
  	"hospital": "11178",
  	"region": 1,
  	"province": 55
  }
 }
}
```
