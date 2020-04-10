# Roller coasters API

Public API with a selection of roller coasters around the world => https://coasters-api.herokuapp.com/

## Endpoints

| HTTP Method 	| URI path      	| Description                                    	| Example 	|
|-------------	|---------------	|------------------------------------------------	|---------	|
| GET         	| /             	| All records on JSON format          	| <a href="https://coasters-api.herokuapp.com" target="_blank">Link</a>     	|
| GET         	| /coaster/:id 	| Matching ID record on JSON format 	| <a href="https://coasters-api.herokuapp.com/coaster/5e8ef56a60fa824d1e2db3d9" target="_blank">Link</a> 	|
| GET         	| /name/:name 	| Matching `name` record on JSON format 	| <a href="https://coasters-api.herokuapp.com/name/Shambhala" target="_blank">Link</a> 	|
| GET         	| /model/:model 	| Matching `model` records on JSON format 	| <a href="https://coasters-api.herokuapp.com/model/Accelerator%20Coaster" target="_blank">Link</a> 	|
| GET         	| /country/:country 	| Matching `country` records on JSON format 	| <a href="https://coasters-api.herokuapp.com/country/Spain" target="_blank">Link</a> 	|
| GET         	| /year/:year 	| Matching `year` records on JSON format 	| <a href="https://coasters-api.herokuapp.com/year/2005" target="_blank">Link</a> 	|
| GET         	| /park/:park 	| Matching `park` records on JSON format 	| <a href="https://coasters-api.herokuapp.com/park/PortAventura%20Park" target="_blank">Link</a> 	|

## JSON response format

```json
{
    "length": 1564,
    "height": 75,
    "speed": 134,
    "inversions": 0,
    "gForce": 3.8,
    "country": "Spain",
    "year": 2012,
    "type": [
      "Roller Coaster",
      "Steel",
      "Sit Down",
      "Extreme"
    ],
    "_id": "5e8ef56a60fa824d1e2db3d9",
    "name": "Shambhala",
    "park": "PortAventura Park",
    "model": "Hyper Coaster",
    "createdAt": "2020-04-09T10:14:02.718Z",
    "updatedAt": "2020-04-09T10:14:02.718Z",
    "__v": 0
  }
```

## JSON response data types
| Property 	| Data type      	| 
|-------------	|---------------	|
| `_id`         	| String             	| 
| `name`         	| String             	| 
| `park`         	| String             	| 
| `length`         	| Number             	| 
| `height`         	| Number             	| 
| `speed`         	| Number             	| 
| `inversions`         	| Number             	| 
| `gForce`         	| Float             	| 
| `country`         	| String             	| 
| `year`         	| Number             	| 
| `type`         	| Array             	| 
| `model`         	| String             	| 
