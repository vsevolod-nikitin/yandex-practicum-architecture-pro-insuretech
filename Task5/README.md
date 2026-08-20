# Задание 5. Проектирование GraphQL API

**Пример запроса**

``` graphql
query {
  client(id: "123") {
    documents {
      id
      type
      number
      issueDate
      expiryDate
    }
  }
}
```