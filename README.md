# envoy-example

### Test request:
```
curl --location 'http://localhost:8080/invite' \
--header 'X-Kamailio: test' \
--header 'Content-Type: application/json' \
--data-raw '{
    "callId": "1",
    "uri": "sip:1@dev-sip.webinar.ru;kamailio=tes"
}'
```
