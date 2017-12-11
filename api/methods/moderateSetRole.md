# Set Role

Sets the role of a user, if you have [permission](/api/roles.md). You must be at least manager or above to do this.
Role can be a [constant](/api/constants.md).

### Code

```js
API.moderateSetRole(id, role);
```

### Example

```js
API.moderateSetRole(1337, API.ROLE.DJ);
```
Sets the rank of resident DJ to user with id 1337.

### Endpoint

[https://plug.dj/_/](/api/endpoints/.md)
