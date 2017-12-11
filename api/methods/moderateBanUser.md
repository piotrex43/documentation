# Ban User

Bans the specified user, for a set duration.

Please see the [API constants](/api/constants.md) for the ban length values.

**Reason**: The reason member is set as a single number which represent the following reasons:

**1**: (SPAMMING) User spammed the chat

**2**: (VERBAL_ABUSE) User was harsh to other community members

**3**: (OFFENSIVE_VIDEOS) User was playing offensive media

**4**: (PLAYING_INAPPROPIATE_GENRES) User was playing inappropiate media repeatedly

**5**: (NEGATIVE_ATTITUDE) User was having a negative attitude towards others


### Code

```js
API.moderateBanUser(id, reason, duration);
```

### Example

```js
API.moderateBanUse(1337, 3, API.BAN.PERMA);
```

Will permanently ban user with id 1337, with reason number 3.

### Endpoint

[https://plug.dj/_/](/api/endpoints/bans_add.md)
