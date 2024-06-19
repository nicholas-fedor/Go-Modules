# Go-Modules

## Description

A simple tutorial for locally calling code from another module.

## Tutorial Source

<https://go.dev/doc/tutorial/call-module-code>

## Note

The following terminal command is used to add the local reference within the go.mod
file, while the import within hello.go references the remote location.

```console
go mod edit -replace example.com/greetings=../greetings
```
