---
title: "Install"
weight: 20
---

Using Cobra is easy. First, use `go install` to install the latest version
of the library. This command will install the [`cobra` generator](https://github.com/spf13/cobra-cli/blob/main/README.md) 
executable along with the library and its dependencies:

    go install github.com/spf13/cobra-cli@latest

Next, include Cobra in your application:

```go
import "github.com/spf13/cobra"
```
