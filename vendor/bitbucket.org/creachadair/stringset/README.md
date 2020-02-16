# stringset

http://godoc.org/bitbucket.org/creachadair/stringset

[![Go Report Card](https://goreportcard.com/badge/bitbucket.org/creachadair/stringset)](https://goreportcard.com/report/bitbucket.org/creachadair/stringset)

The `stringset` package implements a lightweight set-of-strings type based
around Go's built-in map type.

## Generating the Code

The `stringset` package is generated by the `makeset` program. To modify the
package, edit `makeset/makeset.go` and then run:

```shell
go run makeset/makeset.go -config makeset/stringset.toml -output .
```