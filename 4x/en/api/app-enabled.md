Returns `true` if the setting `name` is enabled (`true`), where `name` is one of the
properties from the [app settings table](#app.settings.table).

```js
app.enabled('trust proxy');
// => false

app.enable('trust proxy');
app.enabled('trust proxy');
// => true
```
