
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"certificate_authority_ids":["ca_2PE1W2TSvtUEQAj3dxKejS38FOl"]}' \
https://api.ngrok.com/edges/https/edghts_2PE1VzBy6FedS60RBAhYXXGikXv/mutual_tls
