# BLOCKS Data Standard
The BLOCKS Data Standard is an official format for structuring information that is embedded into on-chain data transactions. This standard is designed to streamline app integrations that fetch and display on-chain data. The BLOCKS Data Standard is versioned and may be improved or modified over time.

# Full Example
This example contains all fields including optional fields.
```
{
	"UID": "84DA5E3584B67088247829B2306614901B68D370801783C3DB2872A00D7FCC80",
	"TIME": "1658573199",
	"SRC_WALLET": "0x29489035cd8ae7d074202def9cbf3e34a9657364",
	"HASH": "50FACDE6F3E6BEE06D8A5614145654E5BF688ACE86A8C8915914962FEEC3B270",

	"DATA": {

		"ID": {
			"standard": "0.0.1",
			"asset_network": "polygon",
			"token_standard": "",
			"record_type": "registry",
			"reg_id": "@BLOCKS_DAO",
			"reg_name": "BLOCKS DAO, LLC",
			"contract_addr": "",
			"contract_deployer": "",
			"reg_wallet_addr": "",
			"src_name": "BLOCKS_DAO",
			"src_ip": "",
			"kyc_kyb_hash": "18563861A4A2F81E43F9643711AD66A3710851B556420CA49BB97A8F82AD4287"
		},

		"BLOCKS_OBJ": {
			"id": "BLOCKS OBJ ID",
			"reg_network": "polygon",
			"prev_tx_id": "",
			"title": "BLOCKS OBJ TITLE",
			"description": "BLOCKS OBJ DESCRIPTION"
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
				"type": "Twitter",
				"url": "https://twitter.com/BLOCKS_DAO",
				"handle": "@BLOCKS_DAO",
				"description": "BLOCKS DAO, LLC TWITTER"
			},
			{
				"type": "Discord",
				"url": "https://discord.gg/thx2fWjk",
				"handle": "",
				"description": "BLOCKS DAO, LLC DISCORD"
			}
		],

		"WEB_LINKS": [
			{
				"url": "https://www.blocks.io/",
				"description": "BLOCKS DAO, LLC Official Website"
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
				"table_name": "TABLE 3x3",
				"label": [ "label 1", "label 2", "label 3" ],
				"rows": [
					[ "row1 col1", "row1 col2", "row1 col3" ],
					[ "row2 col1", "row2 col2", "row2 col3" ],
					[ "row3 col1", "row3 col2", "row1 col3" ]
				]
			},
			{
				"table_name": "TABLE 4x3",
				"label": [ "label 1", "label 2", "label 3", "label 4" ],
				"rows": [
					[ "row1 col1", "row1 col2", "row1 col3", "row1 col4" ],
					[ "row2 col1", "row2 col2", "row2 col3", "row2 col4" ],
					[ "row3 col1", "row3 col2", "row3 col3", "row3 col4" ]
				]
			},
			{
				"table_name": "TABLE 2x5",
				"label": [ "label 1", "label 2" ],
				"rows": [
					[ "row1 col1", "row1 col2" ],
					[ "row2 col1", "row2 col2" ],
					[ "row3 col1", "row3 col2" ],
					[ "row4 col1", "row4 col2" ],
					[ "row5 col1", "row5 col2" ]
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
}  
```
