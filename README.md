# GraphQL-SHOE - Semantic Handling of Errors

Coming soon; in the mean time, check out:

- [GraphQL TOE](https://www.npmjs.com/package/graphql-toe) - Throw on Error:
  takes GraphQL's `{data,errors}` result and turns it into a `data` object such
  that when you read from an errored field it throws the error, for you to
  handle with try/catch or `<ErrorBoundary />`
- [GraphQL SOCK](https://www.npmjs.com/package/graphql-sock) - Semantic Output
  Conversion Kit: takes an SDL marked up with `@semanticNonNull` and outputs it
  either for legacy clients (`semantic-to-nullable`) or error-handling clients
  (`semantic-to-strict`)
- [GraphQL HEEL](https://www.npmjs.com/package/graphql-heel) - Have Errors
  Elevate Locally: if you use the new `onError: "NULL"` then your normalized
  store is happy, but now your existing application has all of its expectations
  broken! GraphQL-TOE is great for new projects, but for existing ones you
  probably don't want errors suddenly throwing everywhere, so use GraphQL-HEEL
  to reproduce traditional GraphQL error propagation on the client side.
