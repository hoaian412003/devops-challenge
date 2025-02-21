Provide your CLI command here:

```bash
cat transaction-log.txt | grep 'TSLA' | jq '.order_id' | xargs -I :orderId curl "https://example.com/api/:orderId" -v > ouput.txt
```
