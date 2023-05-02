
#### Example Request
```bash
curl \
-X PATCH \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"metadata":"{\"region\": \"us-west-2\"}"}' \
https://api.ngrok.com/ssh_host_certificates/shcrt_2PE1VMya0cVcUY15odrV1kjfegb
