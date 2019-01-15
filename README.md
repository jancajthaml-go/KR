## Karp-Rabin algorithm

[![Go Report Card](https://goreportcard.com/badge/jancajthaml-go/kr)](https://goreportcard.com/report/jancajthaml-go/kr)

### Usage ###

```
import "github.com/jancajthaml-go/kr"

kr.Search("GEEKS FOR GEEKS", "GEEK")
```

### Performance ###

```
BenchmarkHammingParallel-4    300000000           4.25 ns/op
BenchmarkHammingSerial-4      200000000           8.77 ns/op
```

test on your own by running `make benchmark`

## Resources

* [Wikipedia - Hamming distance](https://en.wikipedia.org/wiki/Hamming_distance)
