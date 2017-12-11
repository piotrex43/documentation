# Mute User

Mutes a specific user from chat, if you have [permission](/api/roles.md).    
Reason is a number between 1 and 5. More information can be found in [here](/api/endpoints/mutes.md).    
Time can be a [constant](/api/constants.md).

### Code

```js
API.moderateMuteUser(id, reason, time);
```

### Example
```js
API.moderateMuteUser(1337, 1, API.MUTE.SHORT);
```
Mutes user with id 1337 with the reason "Violating community rules" for 15 minutes. 

### Endpoint

[https://plug.dj/_/](/api/endpoints/mutes.md)
