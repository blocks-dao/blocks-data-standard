# BLOCKS Data Standard
The BLOCKS Data Standard is an official format for structuring information that is embedded into on-chain data transactions. This standard is designed to streamline app integrations that fetch and display on-chain data. The BLOCKS Data Standard is versioned and may be improved or modified over time.

# Full Example
This example contains all fields including optional fields.
```
{
	"ID": {
		"uid": "",
		"time": 1658573199,
		"standard": "vs 0.0.2",
		"network": "",
		"token_standard": "",
		"record_type": "",
		"reg_id": "",
		"reg_name": "",
		"contract_addr": "",
		"contract_deployer": "",
		"wallet_addr": "",
		"source": "",
		"source_ip": "",
		"kyc_kyb_hash": ""
	},
	"BLOCKS_OBJ": {
		"id": "",
		"index": 0,
		"index_limited": false,
		"index_max": 0,
		"network": "",
		"prev_tx_id": "",
		"title": "",
		"description": "",
		"data": "",
		"hash": ""
	},
	"TOKEN_ID_ADD": [
		{
			"start": null,
			"stop": null,
			"notes": ""
		}
	],
	"TOKEN_ID_DELETE": [
		{
			"start": null,
			"stop": null,
			"notes": ""
		}
	],
	"SOCIAL_MEDIA": [
		{
			"type": "",
			"url": "",
			"handle": "",
			"description": ""
		},
		{
			"type": "",
			"url": "",
			"handle": "",
			"description": ""
		}
	],
	"WEB_LINKS": [
		{
			"url": "",
			"description": ""
		}
	],
	"FILES": [
		{
			"type": "",
			"ext": "",
			"url": "",
			"checksum": "",
			"encrypted": false,
			"license": "",
			"name": "",
			"description": ""
		}
	],
	"TABLE": [
		{
			"table_name" : "TABLE 3x3",
			"label" : ["label 1","label 2", "label 3"],
			"rows" :[
				["row1 col1","row1 col2","row1 col3"],
				["row2 col1","row2 col2","row2 col3"],
				["row3 col1","row3 col2","row1 col3"]
			]
		},
		{
			"table_name" : "TABLE 4x3",
			"label" : ["label 1","label 2", "label 3", "label 4"],
			"rows" :[
				["row1 col1","row1 col2","row1 col3","row1 col4"],
				["row2 col1","row2 col2","row2 col3","row2 col4"],
				["row3 col1","row3 col2","row3 col3","row3 col4"]
			]
		},
		{
			"table_name" : "TABLE 2x5",
			"label" : ["label 1","label 2"],
			"rows" :[
				["row1 col1","row1 col2"],
				["row2 col1","row2 col2"],
				["row3 col1","row3 col2"],
				["row4 col1","row4 col2"],
				["row5 col1","row5 col2"]
			]
		}
	],
	"DATA_LIST": [
		{
			"name": "",
			"value": ""
		}
	],
	"OBJ_LINK": [
		{
			"title": "",
			"description": "",
			"network": "",
			"tx_id": ""
		}
	]
}
```
# Minimum Required Fields
```
{
	"ID": {
		"uid": "",
		"time": 1658573199,
		"standard": "vs 0.0.2",
		"network": "",
		"token_standard": "",
		"record_type": "",
		"reg_id": "",
		"reg_name": "",
		"contract_addr": "",
		"contract_deployer": "",
		"wallet_addr": "",
		"source": "",
		"source_ip": "",
		"kyc_kyb_hash": ""
	},
	"BLOCKS_OBJ": {
		"id": "",
		"index": 0,
		"index_limited": false,
		"index_max": 0,
		"network": "",
		"prev_tx_id": "",
		"title": "",
		"description": "",
		"data": "",
		"hash": ""
	}
}  
```
