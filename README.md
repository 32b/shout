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
result:=s("echo",myVar1,myVar2)
```
```go
lines:=s("cat",myVar2).list()
```
