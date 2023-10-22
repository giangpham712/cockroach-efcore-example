Set the connection string

Example connection string

```
Host=localhost;Port=26257;Username=username;Password=password;Database=CockroachEFCoreExample
```

For more information on how to construct a connection string, see this [page](https://www.npgsql.org/doc/connection-string-parameters.html)

Set a DATABASE_CONNECTION environment variable to your connection string.

```
export DATABASE_CONNECTION="{connection string}"
```