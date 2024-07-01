This is a base Go template for Dispatch.

Install the Dispatch CLI:
```bash
brew tap dispatchrun/dispatch && \
brew install dispatch
```

Login to Dispatch:
```bash
dispatch login
```

Install dependencies from `go.mod`:
```bash
go mod download
```

Run:
```bash
dispatch run -- go run main.go
```
