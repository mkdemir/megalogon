<p align="center">
    <img src="./assets/images/logo.png" width="450">
</p>

![Version](https://img.shields.io/badge/version-0.0.0-orange.svg)
![Go](https://img.shields.io/github/go-mod/go-version/mkdemir/megalogon)
![Go Build Status](https://github.com/mkdemir/megalogon/actions/workflows/go.yml/badge.svg)
![GolangCI-Lint Status](https://github.com/mkdemir/megalogon/actions/workflows/golang-lint.yml/badge.svg)
[![Documentation](https://godoc.org/github.com/mkdemir/megalogon?status.svg)](https://pkg.go.dev/github.com/mkdemir/megalogon)
[![Go Report Card](https://goreportcard.com/badge/github.com/mkdemir/megalogon)](https://goreportcard.com/report/github.com/mkdemir/megalogon)

# Megalogon

**Megalogon** is an advanced Cyber Threat Intelligence tool. Its purpose is to gather, analyze, and present data from various threat sources to enhance the digital security of organizations and individuals. **Megalogon** provides a powerful toolset to combat complex and rapidly evolving cyber threats.

---

## Installation

Go to your project root, where `go.mod` file exists, than grab the library via:

```bash
go get github.com/mkdemir/megalogon@latest
```

---

## Usage

```go
package main

import (
	"fmt"
)

func main(){
	fmt.Println("mkdemir") // mkdemir
}
```

---

## Makefile

```bash
make help
```

Commands usage:

```bash
make <command>

commands:

test       run tests
testfuzz   run tests with fuzz (30 seconds)
bench      run benchmark tests
doc        run godoc server at 3000 unless PORT env-var is set
```

- `make test`: Runs tests
- `make testfuzz`: Runs Fuzzy tests for 30seconds (`go 1.18`)
- `make bench`: Runs benchmark tests
- `make doc`: Runs godoc server on port 3000. Use `PORT` environment variable
  for different port -> `PORT=4000 make doc`

---

## Contributor(s)

* [mkdemir](https://github.com/mkdemir) - Creator, maintainer

---

## Contribute

All PR’s are welcome!

1. `fork` (https://github.com/mkdemir/megalogon/fork)
1. Create your `branch` (`git checkout -b my-feature`)
1. `commit` yours (`git commit -am 'add some functionality'`)
1. `push` your `branch` (`git push origin my-feature`)
1. Than create a new **Pull Request**!

---

## License

This project is licensed under MIT

---

This project is intended to be a safe, welcoming space for collaboration, and
contributors are expected to adhere to the [code of conduct][coc].

[coc]: https://github.com/mkdemir/megalogon/blob/main/CODE_OF_CONDUCT.md