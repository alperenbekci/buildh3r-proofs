# buildh3r-proofs

algorand 

@alperenbekci ➜ /workspaces/codespace_algorand (main) $ python main.py
{'address': 'PIRMXSZ22VC3SDYIODA6KYZIBXO3GRUBQVUPV5HW5RBKXSU7CLXUAW3H4A', 'amount': 10000000, 'amount-without-pending-rewards': 10000000, 'apps-local-state': [], 'apps-total-schema': {'num-byte-slice': 0, 'num-uint': 0}, 'assets': [], 'created-apps': [], 'created-assets': [], 'min-balance': 100000, 'pending-rewards': 0, 'reward-base': 0, 'rewards': 0, 'round': 9, 'status': 'Offline', 'total-apps-opted-in': 0, 'total-assets-opted-in': 0, 'total-created-apps': 0, 'total-created-assets': 0}
2P427IEB7M6WI4Q3HOGCGTI5MBRG35OGX5QA57SG22A2TPIVD2WMV7SY6Y
{'address': '2P427IEB7M6WI4Q3HOGCGTI5MBRG35OGX5QA57SG22A2TPIVD2WMV7SY6Y', 'amount': 9999000, 'amount-without-pending-rewards': 9999000, 'apps-local-state': [], 'apps-total-schema': {'num-byte-slice': 0, 'num-uint': 0}, 'assets': [{'amount': 111, 'asset-id': 1010, 'is-frozen': False}], 'created-apps': [], 'created-assets': [], 'min-balance': 200000, 'pending-rewards': 0, 'reward-base': 0, 'rewards': 0, 'round': 13, 'status': 'Offline', 'total-apps-opted-in': 0, 'total-assets-opted-in': 1, 'total-created-apps': 0, 'total-created-assets': 0}

@alperenbekci ➜ .../codespace_algorand/alperen/projects/alperen (main) $ source /workspaces/codespace_algorand/alperen/projects/alperen/.venv/bin/activate
(alperen-py3.12) @alperenbekci ➜ .../codespace_algorand/alperen/projects/alperen (main) $  /usr/bin/env /workspaces/codespace_algorand/alperen/projects/alperen/.venv/bin/python /home/codespace/.vscode-remote/extensions/ms-python.debugpy-2024.6.0-linux-x64/bundled/libs/debugpy/adapter/../../debugpy/launcher 55519 -- -m smart_contracts 
2024-05-08 10:47:47,498 INFO      : Loading .env
2024-05-08 10:47:47,500 INFO      : Building app at smart_contracts/hello_world/contract.py
2024-05-08 10:47:47,501 INFO      : Exporting smart_contracts/hello_world/contract.py to /workspaces/codespace_algorand/alperen/projects/alperen/smart_contracts/artifacts/hello_world
2024-05-08 10:47:58,990 INFO      : Deploying contract.py
2024-05-08 10:48:01,467 DEBUG     : Couldn't find existing account in LocalNet with name 'DEPLOYER'. So created account NSJYZLUZSSGTK4HM6HF2LLLDOQ3MLB2G2K6JDCWPYAL6TQXLWY4K2LWZHA with keys stored in KMD.
2024-05-08 10:48:01,467 DEBUG     : Funding account NSJYZLUZSSGTK4HM6HF2LLLDOQ3MLB2G2K6JDCWPYAL6TQXLWY4K2LWZHA with 0 ALGOs
2024-05-08 10:48:02,565 DEBUG     : Sent transaction TV2CP4K2ATRFITIXU2RG3ZSAYRZPABQEUKZGWCNNNFPFTUB6TYVQ type=pay from NOURXJDHFV6ATI6K3JDYIESFUKORIMNJ62EDMM42UGJ56MOU4XM24UQKBI
2024-05-08 10:48:02,827 INFO      : HelloWorld not found in NSJYZLUZSSGTK4HM6HF2LLLDOQ3MLB2G2K6JDCWPYAL6TQXLWY4K2LWZHA account, deploying app.
2024-05-08 10:48:02,856 INFO      : HelloWorld (v1.0) deployed successfully, with app id 1015.
2024-05-08 10:48:02,884 INFO      : Called hello on HelloWorld (1015) with name=world, received: Hello, world
(alperen-py3.12) @alperenbekci ➜ .../codespace_algorand/alperen/projects/alperen (main) $ 

api3

0x4dD06E955b39555780f83a3Ba914c7d4790D160D
0xa6ECfB4170dA97e832CB3b63dAF5B7B7C715B153


[vm]from: 0x5B3...eddC4to: DataFeedReaderExample.(constructor)value: 0 weidata: 0x608...90033logs: 0hash: 0x621...011cb
status	0x1 Transaction mined and execution succeed
transaction hash	0x6219f90255d1a198ba8295adcb2b225e523144c62b392152f68a9f249c5011cb
block hash	0xa49bfb5ebb307a0e6677466448cefacb1c6807d0f29ef8b310fcb8ffbf71105e
block number	1
contract address	0xd9145CCE52D386f254917e481eB44e9943F39138
from	0x5B38Da6a701c568545dCfcB03FcB875f56beddC4
to	DataFeedReaderExample.(constructor)
gas	222943 gas
transaction cost	193863 gas 
execution cost	130175 gas 
input	0x608...90033
decoded input	{}
decoded output	 - 
logs	[]
call to DataFeedReaderExample.readDataFeed

starknet 

------------------------ Deploying contract: balance.cairo ------------------------
{
  "transaction_hash": "0x2b53bb27caa92c9260d08a27b5a7463c146e479152d5fcf3bd8a23c0488fe85",
  "contract_address": [
    "0x7ed5bc606b7d605b7fc21653b64ef3d9118e745f7a55f91e3bbe76b5d59b0bf"
  ]
}
---------------------- End Deploying contract: balance.cairo ----------------------
--------------------- Getting deploy contract: balance.cairo tx receipt --------------------
------------------- Calling get ------------------------
