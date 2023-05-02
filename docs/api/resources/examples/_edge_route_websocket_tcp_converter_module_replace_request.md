
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true}' \
https://api.ngrok.com/edges/https/edghts_2PE1W1Yo3vmmKr7pji7Xj5A2KWQ/routes/edghtsrt_2PE1W1tRqu5XcLtkGuYvig3XCFv/websocket_tcp_converter
