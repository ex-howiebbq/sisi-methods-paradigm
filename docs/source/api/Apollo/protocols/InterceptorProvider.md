**PROTOCOL**

# `InterceptorProvider`

```swift
public protocol InterceptorProvider
```

> A protocol to allow easy creation of an array of interceptors for a given operation.

## Methods
### `interceptors(for:)`

```swift
func interceptors<Operation: GraphQLOperation>(for operation: Operation) -> [ApolloInterceptor]
```

> Creates a new array of interceptors when called
>
> - Parameter operation: The operation to provide interceptors for

#### Parameters

| Name | Description |
| ---- | ----------- |
| operation | The operation to provide interceptors for |