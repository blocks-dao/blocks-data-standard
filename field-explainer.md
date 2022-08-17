```
	"ID": {
		"uid": "",              // * Partner generated value, typically a SHA256 hash of proprietary data.
		"time": 1658573199,     // * UNIX time stamp of the time the transaction is generated.
		"standard": "0.0.1",    // * The current BLOCKS Data Standard version being used.
		"network": "",          // * The blockchain network this transaction will be posted to.
		"token_standard": "",   // Ethereum token standard if verification for NFT (721, 1155).
		"record_type": "",      // * "VBB", "Registry"
		"reg_id": "",           // Partner generated regisatration id.
		"reg_name": "",         // Partner generated regisatration name.
		"contract_addr": "",    // Contract address of NFT project if verification for NFT.
		"contract_deployer": "",// Wallet address of the contract deployer.
		"wallet_addr": "",      // * Wallet address of the sender of this transaction.
		"source": "",           // Partner project name, i.e. "Search3"
		"source_ip": "",        // IP of transaction creator
		"kyc_kyb_hash": ""      // Partner generated value 
	},
```
```
	"BLOCKS_OBJ": {
		"id": "",              // Partner generated value
		"index": 0,            // For linking multiple transactions, the index of the current transaction.
		"index_limited": false,// Ignore "index_max" if true.
		"index_max": 0,        // For linking multiple transactions, the index of the last transaction.
		"prev_tx_id": "",      // Previous transaction id when linking multiple transactions.
		"title": "",           // * Title of the data object, partner genegated
		"description": "",     // * Description of the data object, partner genegated
		"data": "",            // Any additional data related to the object, partner genegated
		"hash": ""             // 
	},
```
```
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
```
```
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
```
```
	"WEB_LINKS": [
		{
			"url": "",
			"description": ""
		}
	],
```
```
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
```
```
	"DATA_LIST": [
		{
			"name": "",
			"value": ""
		}
	],
```
```
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
