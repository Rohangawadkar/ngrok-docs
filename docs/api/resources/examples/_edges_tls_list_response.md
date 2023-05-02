
#### Example Response
```json
{
  "tls_edges": [
    {
      "id": "edgtls_2PE1W4WY80c8W0ogM2lxSkZo0hP",
      "description": "acme tls edge",
      "metadata": "{\"environment\": \"staging\"}",
      "created_at": "2023-05-02T06:04:14Z",
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2PE1W4WY80c8W0ogM2lxSkZo0hP",
      "hostports": [
        "example.com:443"
      ],
      "backend": null,
      "ip_restriction": null,
      "mutual_tls": null,
      "tls_termination": null
    },
    {
      "id": "edgtls_2PE1VBbRrpyACAurokZzDOiWZ7C",
      "description": "acme tls edge",
      "created_at": "2023-05-02T06:04:07Z",
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2PE1VBbRrpyACAurokZzDOiWZ7C",
      "hostports": [
        "endpoint-example.com:443"
      ],
      "backend": {
        "enabled": true,
        "backend": {
          "id": "bkdhr_2PE1V8oefewUjVque4gxMpXbB6U",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2PE1V8oefewUjVque4gxMpXbB6U"
        }
      },
      "ip_restriction": null,
      "mutual_tls": null,
      "tls_termination": null
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls",
  "next_page_uri": null
}