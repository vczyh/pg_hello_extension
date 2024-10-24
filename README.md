
## Getting Started

Install extension and connect pg server.

```shell
cargo pgrx run
```

Create extension.

```sql
CREATE EXTENSION pg_hello_extension;

SELECT to_uppercase('hello');
```


