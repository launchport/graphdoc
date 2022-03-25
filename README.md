# graphdoc

## Provding a custom configuration

GraphDoc will check for a the existence of `.well-known/graphql.json` file on the same domain as your GraphQL API. 

### Example configuration

```json
{
   "title":"My GraphQL API",
   "description":"Awesome API that provides a ton of value.",
   "favicon_url":"http://static.example.com/favicon.ico",
   "logo_light_url":"http://static.example.com/logo-light.svg",
   "logo_dark_url":"http://static.example.com/logo-dark.svg",
   "accent_color":"#ff0000",
   "headers":{
      "Authorization":"Bearer MyPublicSecret"
   }
}
```
