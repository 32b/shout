# shout
sh[ell]out - a helper for external commands

```go
if s("ls *").p("xargs rm -rf") {
	s("echo it worked")
}
```
