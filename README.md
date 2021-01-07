BlockChain
===
---
![GitHub](https://img.shields.io/github/license/mysmarthub/blockchain)
![GitHub all releases](https://img.shields.io/github/downloads/mysmarthub/blockchain/total)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/mysmarthub/blockchain)

Help:
---
`pip install -r requirements.txt`

`python blockchain.py`

`curl http://localhost:5000/mine`

`curl http://localhost:5000/mine`

`curl http://localhost:5000/chain`


```commandline
curl -X POST -H "Content-Type: application/json" -d '{
    "sender": "d4ee26eee15148ee92c6cd394edd974e",
    "recipient": "someone-other-address",
    "amount": 5
    }' "http://localhost:5000/transactions/new"
```

