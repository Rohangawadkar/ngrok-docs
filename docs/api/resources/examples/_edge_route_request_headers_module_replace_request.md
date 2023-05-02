
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"add":{"x-frontend":"ngrok"},"remove":["cache-control"]}' \
https://api.ngrok.com/edges/https/edghts_2PE1Vi3uL9Mu1Y6386WzDupuA78/routes/edghtsrt_2PE1Vhan2DWdZLVxJ45uVgyfQXE/request_headers
