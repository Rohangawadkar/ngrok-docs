
#### Example Request
```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"description":"acme weighted","metadata":"{\"environment\": \"staging\"}","backends":{"bkdhr_2PE1VT6Tlou5jR35vaFZsVdUQ0B":0,"bkdhr_2PE1VYVMXmQwpbObKJ4qJWEUsAH":1}}' \
https://api.ngrok.com/backends/weighted
