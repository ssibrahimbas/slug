# Slug

Slug is a simple, lightweight, and fast slug generator for Go.

## Installation

```bash
go get github.com/ssibrahimbas/slug
```

## Usage

```go
package main

import (
    "fmt"

    "github.com/ssibrahimbas/slug"
)

func main() {
    fmt.Println(slug.New("Hello World!"))
    // Output: hello-world

    // check if a string is a valid slug
    res := slug.Is("hello-world") // true
}
```

## Documentation

Documentation is available at [pkg.go.dev](https://pkg.go.dev/github.com/ssibrahimbas/slug).

## Contributing

Contributions are always welcome!

## License

[MIT](LICENSE)
