# [graphdoc](https://graphdoc.io)

_Instant, beautiful docs for your GraphQL API_

## Providing a custom configuration

GraphDoc will check for a the existence of `.well-known/graphql.json` file on the same domain as your GraphQL API. So if your API runs on `https://api.example.com/graphql` the config will be expected at `https://api.example.com/.well-known/graphql.json`.

### Example configuration

```json
{
  "title": "My GraphQL API",
  "description": "Awesome API that provides a ton of value.",
  "favicon_url": "http://static.example.com/favicon.ico",
  "logo_light_url": "http://static.example.com/logo-light.svg",
  "logo_dark_url": "http://static.example.com/logo-dark.svg",
  "headers": {
    "Authorization": "Bearer MyPublicSecret"
  }
}
```

## Issues

If you have any issues regarding rendering your GraphQL API, [don't hesitate to report it here](https://github.com/launchport/graphdoc/issues).
