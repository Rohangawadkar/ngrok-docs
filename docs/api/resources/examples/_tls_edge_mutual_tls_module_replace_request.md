
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"certificate_authority_ids":["ca_2PE1W9Ldg4imTxj42MJkJPHPUwX"]}' \
https://api.ngrok.com/edges/tls/edgtls_2PE1W9GsAJmOiaxWO9gxkaXva8x/mutual_tls
