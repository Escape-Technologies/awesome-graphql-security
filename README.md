<!--lint disable awesome-list-item awesome-toc-->

# Awesome GraphQL Security [![awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

A curated list of awesome GraphQL Security frameworks, libraries, software and resources

## Contents

- [Defensive Security](#defensive-security)
  - [Authentication & Authorization](#authentication--authorization)
  - [Continous Security Testing](#continous-security-testing)
  - [Security Solutions](#security-solutions)
- [Offensive Security](#offensive-security)
  - [Discovery](#discovery)
  - [Exploitation](#exploitation)
  - [Vulnerable Applications](#vulnerable-applications)
  - [Visualizer](#visualizer)
- [Resources](#resources)
  - [Blogs](#blogs)
  - [Vulnerabilities](#vulnerabilities)

## Defensive Security

### Authentication & Authorization

- [GraphQL Shield](https://github.com/maticzav/graphql-shield) - GraphQL Shield helps you create a permission layer for your application. 

### Continous Security Testing

- [Escape - GraphQL Security](https://escape.tech) - Continuous GraphQL Security Testing for Developers. Find and fix GraphQL security flaws in the CI/CD.

### Security Solutions

- [WAF for GraphQL](https://lab.wallarm.com/api-security-solution/) - Web Application Firewall for GraphQL APIs.

## Offensive Security

### Discovery

- [GraphDNA](https://github.com/Escape-Technologies/GraphDNA) - Fast GraphQL engine fingerprinting tool using multi heuristics.
- [Graphinder](https://github.com/Escape-Technologies/graphinder) - Blazing fast GraphQL endpoints finder using subdomain enumeration, scripts analysis and bruteforce.
- [GraphMan](https://github.com/Escape-Technologies/graphman) - Generate a complete Postman collection from a GraphQL endpoint. Allows instant and easy discovery and exploration of the API.
- [Graphw00f](https://github.com/dolevf/graphw00f) - GraphQL Server Engine Fingerprinting utility.
- [Clairvoyance](https://github.com/nikitastupin/clairvoyance) - Patrial introspection fetcher when introspection is disabled.
- [GraphQL Path Enum](https://gitlab.com/dee-see/graphql-path-enum) – Tool that lists the different ways of reaching a given type in a GraphQL schema.

### Exploitation

- [GraphCrawler](https://github.com/gsmith257-cyber/GraphCrawler) - A GraphQL automated security toolkit. Grab introspection, search for sensitive queries, and then test authorization.
- [CrackQL](https://github.com/nicholasaleks/CrackQL) - GraphQL password brute-force and fuzzing utility.
- [GraphQLMap](https://github.com/swisskyrepo/GraphQLmap) - A scripting engine to interact with a GraphQL endpoint for pentesting purposes.
- [GraphQL.Security](https://graphql.security) - One-click quick security scan of your GraphQL endpoints. Free, no login required.
- [GraphQL Threat Matrix](https://github.com/nicholasaleks/graphql-threat-matrix) - GraphQL threat framework to research security gaps in GraphQL implementations.
- [InQL](https://github.com/doyensec/inql) - A Burp Extension for GraphQL Security Testing.

### Vulnerable Applications

- [Damm Vulnerable GraphQL Application](https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application) - Damn Vulnerable GraphQL Application is an intentionally vulnerable implementation of Facebook's GraphQL technology, to learn and practice GraphQL Security. 

### Visualizer

- [GraphQL Visualizer](https://www.graphqlvisualizer.com) - Visualize GraphQL schema.
- [Voyager](https://github.com/IvanGoncharov/graphql-voyager) - Represent any GraphQL API as an interactive graph.

## Resources

### Blogs

- [Access Control Best Practices for GraphQL with Authentication and Authorization](https://blog.escape.tech/authentication-authorization-access-control/) - Confusion between authentication and authorization causes data leaks. Learn the difference and how to implement the right access control pattern in your GraphQL API.
- [Apollo Blog](https://www.apollographql.com/blog/graphql/security/9-ways-to-secure-your-graphql-api-security-checklist/) - Take your GraphQL skills to the next level with our free interactive GraphQL tutorials, videos, quizzes and code challenges.
- [The GraphQL Security Blog](https://blog.escape.tech/9-graphql-security-best-practices/) - Learn about GraphQL security, performance, testing and building production-ready APIs with the latest tools and best practices of the GraphQL ecosystem.

### Vulnerabilities

- [Aliasing Attacks](https://blog.escape.tech/graphql-batch-attacks-cause-dos/) - Addressing the Security concerns of GraphQL Aliases.
- [File Inclusion and Directory Traversal](https://blog.escape.tech/file-inclusion-directory-traversal-graphql/) - File Inclusion and Directory Traversal in GraphQL.
- [GraphQL CSRF](https://blog.escape.tech/understanding-and-dealing-with-cross-site-request-forgery-attacks/) - Understanding and Dealing with Cross-Site Request Forgery Attacks (CSRF) in GraphQL.
- [GraphQL Cyclic Queries and Depth Limiting](https://blog.escape.tech/cyclic-queries-and-depth-limit/) - The relational aspect of GraphQL can be a vulnerability exploited by running deep and cyclic queries causing your API to crawl under the load and crash.
- [HTTPS and GraphQL](https://blog.escape.tech/prevent-data-leaks-with-https/) - How HTTPS can prevent Data Leaks.
- [SQL Injection](https://blog.escape.tech/sql-injection-in-graphql/) - SQL Injections in GraphQL.
- [Verbose Errors Suggestions](https://blog.escape.tech/graphql-verbose-error-suggestions/) - When GraphQL Error Messages become a Security Issue.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/Escape-Technologies/awesome-graphql-security/blob/main/CONTRIBUTING.md) first.

We will keep some pull requests open if we are not sure whether those libraries are awesome, you could [vote for them](https://github.com/Escape-Technologies/awesome-graphql-security/pulls) by adding :+1: to them.

---

If you have any question about this opinionated list, do not hesitate to contact us [@escapetechHQ](https://twitter.com/escapetechHQ) on Twitter or open an issue on GitHub.
