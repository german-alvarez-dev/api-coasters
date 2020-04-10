# Roller coasters API

Public API with a selection of roller coasters around the world => https://coasters-api.herokuapp.com/

## Endpoints

| HTTP Method 	| URI path      	| Description                                    	| Example 	|
|-------------	|---------------	|------------------------------------------------	|---------	|
| GET         	| /             	| All records on JSON format          	| <a href="https://coasters-api.herokuapp.com" target="_blank">Link</a>     	|
| GET         	| /coaster/:id 	| Matching ID record on JSON format 	| <a href="https://coasters-api.herokuapp.com/coaster/5e8c9fb416c9eb164fb0eec6" target="_blank">Link</a> 	|
| GET         	| /name/:name 	| Matching `name` records on JSON format 	| <a href="https://coasters-api.herokuapp.com/name/Shambhala" target="_blank">Link</a> 	|
| GET         	| /model/:model 	| Matching `model` records on JSON format 	| <a href="https://coasters-api.herokuapp.com/model/Accelerator%20Coaster" target="_blank">Link</a> 	|
| GET         	| /country/:country 	| Matching `country` records on JSON format 	| <a href="https://coasters-api.herokuapp.com/country/Spain" target="_blank">Link</a> 	|
| GET         	| /year/:year 	| Matching `year` records on JSON format 	| <a href="https://coasters-api.herokuapp.com/year/2005" target="_blank">Link</a> 	|
| GET         	| /park/:park 	| Matching `park` records on JSON format 	| <a href="https://coasters-api.herokuapp.com/park/PortAventura%20Park" target="_blank">Link</a> 	|

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
