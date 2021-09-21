# Rust app 🦀

Rust GraphQL backend using [async-graphql](https://github.com/async-graphql/async-graphql).

GraphQL schema
```rust
enum ChocolateType {
  Bitter, White, Milk
}
type Product {
  id: Int!
  name: String!
  description: String!
  price: Int!
  chocolateType: chocolateType!
  fillings: [String]!
  images: [String]!
}
```
