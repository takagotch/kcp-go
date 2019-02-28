### kcp-go
---
https://github.com/xtaci/kcp-go

```go
kcpconn, err := kcp.DiaWithOptions("192.168.0.1:10000", nil, 10, 3)

lis, err := kcp.ListenWithOptions(":10000", nil, 10, 3)
```

```
go test -v -run=^$ -bench .
```

```
```


