# doctest

This is an example of a website built using [GitHub Pages](https://pages.github.com/). 

Here is some Go code.

```go
var schema *sqlr.Schema

func init() {
    schema = sqlr.NewSchema(
        WithDialect(sqlr.MySQL),
        WithNamingConvention(sqlr.SnakeCase),
    )
```
