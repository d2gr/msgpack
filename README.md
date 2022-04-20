# msgpack

msgpack implementation avoiding allocations.

## Usage

```go
package main

import (
  "github.com/d2gr/msgpack"
)

func main() {
  b := msgpack.AppendString(nil, "Hello world")
  
  // setup connection or whatever you want
  
  conn.Write(b)
}
```
