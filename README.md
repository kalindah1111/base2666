# base2666
Tracking Gas Used Per Transaction
receipt = w3.eth.get_transaction_receipt(tx_hash)
print("Gas used:", receipt.gasUsed)
