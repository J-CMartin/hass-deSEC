# hass-deSEC
Home Assistant HACS deSec integration (dedyn.io)

```
# Example configuration.yaml entry
desec_io:
  # full DNS name
  domain: example.dedyn.io 
  # access token in quotes
  access_token: "CopyYourTokenHere_KeepTheDoubleQuotes"
  protocol:
    - ipv4
    - ipv6
  # if you don't want to set either ipv4 or ipv6 records just comment or remove
  # this means also that correspoding ipv4 (A) or ipv6 (AAAA) dns record also be removed 
```
