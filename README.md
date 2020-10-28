<h1>BlockChain</h1>
<p>...</p>
<hr>
<code>pip install -r requirements.txt</code>
<hr>
<code>python3 blockchain.py</code>
<hr>
<code>curl http://localhost:5000/mine</code>
<hr>
<code>curl http://localhost:5000/mine</code>
<hr>
<code>curl http://localhost:5000/chain</code>
<hr>
<code>
    curl -X POST -H "Content-Type: application/json" -d '{
    "sender": "d4ee26eee15148ee92c6cd394edd974e",
    "recipient": "someone-other-address",
    "amount": 5
    }' "http://localhost:5000/transactions/new"
</code>
