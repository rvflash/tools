# Tools

Lists of underrated tools to use and more. 

* Golang Vulnerability: https://vuln.go.dev/  
```
$ go install golang.org/x/vuln/cmd/govulncheck@latest
```
* Golang updates
> https://github.com/golang/dl
```
$ go install golang.org/dl/go1.19.2@latest
$ go1.19.2 download
$ ln -s /home/rv/sdk/go1.19.2 /usr/local/go
```
* Online converter from JSON to Go struct
> https://mholt.github.io/json-to-go/
* Fieldalignment: A part of gotools and govet linter, `fieldalignment` prints out misaligned structs and the current/ideal size of struct.
> https://pkg.go.dev/golang.org/x/tools/go/analysis/passes/fieldalignment/cmd/fieldalignment
```bash
fieldalignment -fix ${package_path}
```
* Stringer is a tool to automate the creation of methods that satisfy the fmt.Stringer interface. 
> https://pkg.go.dev/golang.org/x/tools@v0.1.1/cmd/stringer
* Go fmt also provides an interface to perform replacements in the codes base 
> https://pkg.go.dev/cmd/gofmt
