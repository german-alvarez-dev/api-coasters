# Roller coasters API

Public API with a selection of roller coasters around the world => https://coasters-api.herokuapp.com/

## Endpoints

| HTTP Method 	| URI path      	| Description                                    	| Example 	|
|-------------	|---------------	|------------------------------------------------	|---------	|
| GET         	| /             	| All records on JSON format          	| <a href="https://coasters-api.herokuapp.com" target="_blank">Link</a>     	|
| GET         	| /coaster/[id] 	| Matching ID record on JSON format 	| <a href="https://coasters-api.herokuapp.com/coaster/5e8c9fb416c9eb164fb0eec6" target="_blank">Link</a> 	|

## JSON response format

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
