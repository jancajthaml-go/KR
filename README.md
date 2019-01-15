## Karp-Rabin algorithm

[![Go Report Card](https://goreportcard.com/badge/jancajthaml-go/kr)](https://goreportcard.com/report/jancajthaml-go/kr)

### Usage ###

```
import "github.com/jancajthaml-go/kr"

kr.Search("GEEKS FOR GEEKS", "GEEK")
```

### Performance ###

```
BenchmarkKarpRabinSmall-4          30000000   54.2 ns/op   8 B/op  1 allocs/op
BenchmarkKarpRabinLarge-4          10000000    174 ns/op  24 B/op  2 allocs/op
BenchmarkKarpRabinSmallParallel-4  50000000   28.7 ns/op   8 B/op  1 allocs/op
BenchmarkKarpRabinLargeParallel-4  20000000   85.5 ns/op  24 B/op  2 allocs/op
```

verify your performance by running `make benchmark`

## Resources

* [Wikipedia - Rabin–Karp algorithm](https://en.wikipedia.org/wiki/Rabin%E2%80%93Karp_algorithm)
