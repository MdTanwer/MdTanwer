# SmallRye GraphQL

[All pull requests](https://github.com/smallrye/smallrye-graphql/pulls/MdTanwer) · [Back to profile](../README.md)

MicroProfile GraphQL schema generation fix for Kotlin + Mutiny reactive types.

| Pull request | Detail |
|---|---|
| [#2563](https://github.com/smallrye/smallrye-graphql/pull/2563) | Preserve Kotlin list-item nullability inside Mutiny `Uni` wrappers (`Uni<List<String>>` → `[String!]!` instead of `[String]!`) by recursively applying Kotlin metadata across the wrapper chain. |
