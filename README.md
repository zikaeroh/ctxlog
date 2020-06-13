# ctxlog

A context-based wrapper for the zap logger.

```go
import (
    "context"

    "github.com/zikaeroh/ctxlog"
    "go.uber.org/zap"
)

func doSomething(ctx context.Context) {
    ctxlog.Debug(ctx, "something happened", zap.Int("cool", 1234))
    // ...
}
```
