## Requirements
- Respond to Web requests
- support for HTTP/HTTPS traffic
- support for default pages (index.html)
- support for security headers
- support for CORS

## Pros
- Customised response per user
- Smaller javascript files
- No stale data (vs Static Site Generation)
- No exposed APIs

## Cons
- Complexity around page cache invalidation
- Slower load times

## Implementations

### AWS - Lambda@Edge
![aws-ssr-cf](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/scottcowan/building-blocks/main/plantuml/aws-ssr-cf.puml)

### AWS - Elasticbean
![aws-ssr-eb](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/scottcowan/building-blocks/main/plantuml/aws-ssr-eb.puml)

### Azure - App Service Web app

TODO

### Kubernetes

TODO
