# axios-delete-request

**axios `delete` request is a little bit different from others**

**in `post` request you have to write `body` and you have to send `body` before `headers or config`**

But,

**in `delete` request you have to send `headers` first and you have to write `data` instead of `body`**

```js
axios.delete(URL, {
  headers: {
    Authorization: authorizationToken
  },
  data: {
    source: source
  }
});
```

