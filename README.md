[![banner with logo](https://cdn.alemi.dev/profile/pic/banner.png)](https://alemi.dev)

> i touch computers for a living, try to make music for fun and bike everywhere (cars bad)

```sh
curl -X PUT \
    -H 'Content-Type: application/json' \
    --data '{"body": "hiii :3 how are you??", "public": false, "author": "curl from your git :p"}' \
    https://api.alemi.dev/msg
```

```sh
curl -s https://api.alemi.dev/msg | jq '.[:5].[] | {author, body, date}'
```

<p align="right"><a href="https://github.com/alemidev/guestbook.rs">guestbook.rs</a></p>
