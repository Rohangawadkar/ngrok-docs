
#### Example Response
```json
{
  "ip_policy_rules": [
    {
      "id": "ipr_2PE1VJZLAXyCc0jDBYTVTMf4mdI",
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2PE1VJZLAXyCc0jDBYTVTMf4mdI",
      "created_at": "2023-05-02T06:04:08Z",
      "description": "alan laptop",
      "cidr": "2.2.2.2/32",
      "ip_policy": {
        "id": "ipp_2PE1VExdtilKbnf8R3EZWVTwP0R",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2PE1VExdtilKbnf8R3EZWVTwP0R"
      },
      "action": "allow"
    },
    {
      "id": "ipr_2PE1VFqU6gbM80OYtkzVsuBR5gw",
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2PE1VFqU6gbM80OYtkzVsuBR5gw",
      "created_at": "2023-05-02T06:04:08Z",
      "description": "sf office",
      "cidr": "132.2.19.0/24",
      "ip_policy": {
        "id": "ipp_2PE1VExdtilKbnf8R3EZWVTwP0R",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2PE1VExdtilKbnf8R3EZWVTwP0R"
      },
      "action": "allow"
    },
    {
      "id": "ipr_2PE1VDbEWg5gn3uhpXz8scepHAM",
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2PE1VDbEWg5gn3uhpXz8scepHAM",
      "created_at": "2023-05-02T06:04:08Z",
      "description": "nyc office",
      "cidr": "212.3.14.0/24",
      "ip_policy": {
        "id": "ipp_2PE1VExdtilKbnf8R3EZWVTwP0R",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2PE1VExdtilKbnf8R3EZWVTwP0R"
      },
      "action": "allow"
    }
  ],
  "uri": "https://api.ngrok.com/ip_policy_rules",
  "next_page_uri": null
}