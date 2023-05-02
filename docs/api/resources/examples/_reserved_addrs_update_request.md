
#### Example Request
```bash
curl \
-X PATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"metadata":"{\"proto\": \"ssh\"}","endpoint_configuration_id":"ec_2PE1Uguun3PypcyB3GLLVLurATa"}' \
https://api.ngrok.com/reserved_addrs/ra_2PE0x8xo6dnnBvRHWmw9AHV2TYl
