```json
{
  "username": "Twitter Webhook",
  "avatar_url": "https://i.imgur.com/gBNcYL9.png",
  "content": "New [tweet]({{LinkToTweet}}) by [@{{UserName}}](https://twitter.com/{{UserName}})",
  "embeds": [
    {
      "author": {
        "name": "@{{UserName}}",
        "url": "https://twitter.com/{{UserName}}",
      },
      "title": "See on twitter",
      "url": "{{LinkToTweet}}",
      "description": "{{Text}}",
      "color": 1942002,
      "footer": {
        "text": "Publié le {{CreatedAt}} - Webhook de Joffrey",
      }
    }
  ]
}
```

https://convertingcolors.com/
