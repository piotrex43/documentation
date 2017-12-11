# Set Minimum Chat Level

Sets the minimum chat to users with a specific level (1, 2 or 3), if you have [permission](/api/roles.md).

This prevents someone creating new accounts and spamming the room's chat.

### Code

```js
API.moderateMinChatLevel(number);
```

### Example
```js
API.moderateMinChatLevel(2);
```
Sets the minimum chat level to 2.

### Endpoint

[https://plug.dj/_/](/api/endpoints/.md)
