
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"backend_id":"bkdtg_2PE1W8RtFnPqHwRKpoBR5uM7snJ"}' \
https://api.ngrok.com/edges/tls/edgtls_2PE1W6yXeYB2SdGtubeWbzAAtPE/backend
