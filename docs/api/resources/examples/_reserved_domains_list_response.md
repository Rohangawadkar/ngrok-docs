
#### Example Response
```json
{
  "reserved_domains": [
    {
      "id": "rd_2PE1UVbnHmWKnqsm9lcDakcw3T9",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2PE1UVbnHmWKnqsm9lcDakcw3T9",
      "created_at": "2023-05-02T06:04:02Z",
      "domain": "myapp.mydomain.com",
      "region": "us",
      "cname_target": "2y6xww85g.cname.us.ngrok.io",
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "certificate": {
        "id": "cert_2PE1UU3DxbzHEcZ57AjQTQsXcyd",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2PE1UU3DxbzHEcZ57AjQTQsXcyd"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "acme_challenge_cname_target": null
    },
    {
      "id": "rd_2PE1UggiaAN8ILXlGOiGPWXIXt2",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2PE1UggiaAN8ILXlGOiGPWXIXt2",
      "created_at": "2023-05-02T06:04:02Z",
      "description": "Device 0001 Dashboard",
      "metadata": "{\"service\": \"dashboard\"}",
      "domain": "manage-0001.app.example.com",
      "region": "us",
      "cname_target": "jxwa35qq.cname.us.ngrok.io",
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "renews_at": null,
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "started_at": "2023-05-02T06:04:03Z",
          "retries_at": null
        }
      },
      "acme_challenge_cname_target": null
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains",
  "next_page_uri": null
}