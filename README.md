[![banner with logo](https://cdn.alemi.dev/profile/pic/banner.png)](https://alemi.dev)

> i rarely make sense but still make things

```sh
curl -X PUT \
    -H 'Content-Type: application/json' \
    --data '{"body": "hiii :3 how are you??", "public": false, "author": "curl from your git :p"}' \
    https://api.alemi.dev/msg
```

```sh
curl -s https://api.alemi.dev/msg | jq '.[:5].[] | {author, body, date}'
```
