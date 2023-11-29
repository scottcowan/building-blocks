## Requirements
- Respond to GET requests
- support for HTTPS traffic
- support for default pages (index.html)
- support for security headers
- support for CORS

## Pros
- Fast response times
- Highly cacheable
- Can be implemented without any compute, only storage and hosting

## Cons
- Mixing Static and Dynamic pages can be complex 

## Implementations

### AWS - Cloudfront

![aws-static-site](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/scottcowan/building-blocks/main/plantuml/aws-static-site.puml)

| Component                                 | Description                                                                                                                                                                                                         |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Certificate Manager                       | Provision, manage, and deploy public and private Secure Sockets Layer/Transport Layer Security (SSL/TLS) certificates for use with AWS services                                                                     |
| Amazon CloudFront                         | Content delivery network (CDN) service built for high performance, security, and developer convenience.                                                                                                             |
| Amazon Simple Storage Service (Amazon S3) | Object storage service offering industry-leading scalability, data availability, security, and performance.                                                                                                         |
| Amazon Route 53                           | Highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost effective way to route end users to Internet applications |

### Azure - CDN

![azure-static-site-1](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/scottcowan/building-blocks/main/plantuml/azure-static-site-1.puml)

### Azure - Front Door

![azure-static-site-2](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/valtech-uk/building-blocks/main/plantuml/azure-static-site-2.puml)
