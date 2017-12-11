# Move DJ

Moves the position of the specified user, if you have [permission](/api/roles.md).

### Code

```js
API.moderateMoveDJ(id, position);
```
### Example


```js
API.moderateMoveDJ(1337, 2);
```
Will move user with id 1337 to second position in the waitlist.

### Endpoint

[https://plug.dj/_/](/api/endpoints/booth_move.md)
