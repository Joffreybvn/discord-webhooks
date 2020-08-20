```json
{
  "username": "Webhook",
  "avatar_url": "https://i.imgur.com/zwBAhNE.png",
  "content": "[{{EntryTitle}}]({{EntryUrl}})",
  "embeds": [
    {
      "author": {
        "name": "{{FeedTitle}}",
        "url": "{{FeedUrl}}",
      },
      "title": "{{EntryTitle}}",
      "url": "{{EntryUrl}}",
      "description": "{{EntryContent}}",
      "color": 15258703,
      "thumbnail": {
        "url": "{{EntryImageUrl}}"
      },
      "footer": {
        "text": "Publié le {{EntryPublished}} - Webhook de Joffrey",
      }
    }
  ]
}
```
