
# Alan Turing
Codes du bot pour rapeller les pauses, le pointage et les meets.

## Comment @mentionner via un Webhook ?
1. Taper la commande `\@Votre Mention`
2. Discord vous répond un code du type `<@&745193069946863626>`
3. Utilisez directement ce code dans le JSON

## Rappels:

### Pointage 9h00 - Becode
 - **Trigger**: 8h45
 - **Jours**: Mardi - Mercredi
```json
{
  "username": "Alan Turing",
  "avatar_url": "https://i.imgur.com/JD51N3v.jpg",
  "content": "Salut <@&745193069946863626> ! Le dernier qui pointe à perdu: [Becode](https://my.becode.org/dashboard)."
}
```

### Pointage 9h00 - Home
 - **Trigger**: 8h45
 - **Jours**: Lundi - Jeudi - Vendredi
```json
{
  "username": "Alan Turing",
  "avatar_url": "https://i.imgur.com/JD51N3v.jpg",
  "content": "Bonjour à tous ! On commence dans *15 minutes* sur [Google Meet](https://meet.google.com/hfe-twue-vsb). Et pointez sur [Becode](https://my.becode.org/dashboard)."
}
```

### Pointage 12h30 - All
 - **Trigger**: 12H30
 - **Jours**: Lundi - Mardi - Mercredi - Jeudi - Vendredi
```json
{
  "username": "Alan Turing",
  "avatar_url": "https://i.imgur.com/JD51N3v.jpg",
  "content": "Un bon lunch commence par un bon **pointage** sur [Becode](https://my.becode.org/dashboard). Bon appétit !"
}
```

### Pointage 13h30 - Becode
 - **Trigger**: 13H15
 - **Jours**: Mardi - Mercredi
```json
{
  "username": "Alan Turing",
  "avatar_url": "https://i.imgur.com/JD51N3v.jpg",
  "content": "La veille démarre dans **15 minutes** ! **Pointez** sur [Becode](https://my.becode.org/dashboard)."
}
```

### Pointage 13h30 - Home
 - **Trigger**: 13H15
 - **Jours**: Lundi - Jeudi - Vendredi
```json
{
  "username": "Alan Turing",
  "avatar_url": "https://i.imgur.com/JD51N3v.jpg",
  "content": "La veille démarre dans **15 minutes** sur [Google Meet](https://meet.google.com/hfe-twue-vsb). Et **pointez** aussi sur [Becode](https://my.becode.org/dashboard)."
}
```

### Débriefing 16h45 - Home
 - **Trigger**: 16h30
 - **Jours**: Lundi - Jeudi
```json
{
  "username": "Alan Turing",
  "avatar_url": "https://i.imgur.com/JD51N3v.jpg",
  "content": "Les <@&745193069946863626>, le **débrief** commence dans **15 minutes** sur [Google Meet](https://meet.google.com/hfe-twue-vsb) !"
}
```

### Kahoot 16h40 - Home
 - **Trigger**: 16h30
 - **Jours**: Vendredi
```json
{
  "username": "Alan Turing",
  "avatar_url": "https://i.imgur.com/JD51N3v.jpg",
  "content": "Lequel des <@&745193069946863626> gagnera une gourde durant le [Kahoot](https://meet.google.com/hfe-twue-vsb) aujourd'hui ? Ca commence dans **10 minutes** !"
}
```

### Pointage 17h00 - All
 - **Trigger**: 17h00
 - **Jours**: Lundi - Mardi - Mercredi - Jeudi - Vendredi
```json
{
  "username": "Alan Turing",
  "avatar_url": "https://i.imgur.com/JD51N3v.jpg",
  "content": "**Pointez** sur [Becode](https://my.becode.org/dashboard), et passez une bonne soirée !"
}
```
