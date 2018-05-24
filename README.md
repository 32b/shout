# shout
sh[ell]out - a helper for external commands

```go
if s("ls *").p("xargs rm -rf") {
	s("echo it worked")
}
```
```go
s("ls").tf("contents.txt")
```
```go
s(myVar).p("cat")
```
```go
s("echo",myVar1,myVar2)
```
