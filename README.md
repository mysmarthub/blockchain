BlockChain
===
---
![GitHub](https://img.shields.io/github/license/mysmarthub/blockchain)
![GitHub all releases](https://img.shields.io/github/downloads/mysmarthub/blockchain/total)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/mysmarthub/blockchain)
[![Donate](https://img.shields.io/static/v1?label=donate&message=paypal&color=green)](https://paypal.me/myhackband)
[![Donate](https://img.shields.io/static/v1?label=donate&message=yandex&color=yellow)](https://yoomoney.ru/to/4100115206129186)
---

Help the project financially:
---
>Yandex Money:
https://yoomoney.ru/to/4100115206129186

    Visa:    4048 0250 0089 5923

https://paypal.me/myhackband

---
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

