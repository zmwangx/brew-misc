See [Homebrew/brew-evolution#17](https://github.com/Homebrew/brew-evolution/pull/17).
Here we compare the size and compression/decompression performance of .tar.gz
vs .tar.xz bottles.

Benchmark scripts usage:

```sh
$ ./benchmark | tee /dev/tty | ./process-benchmarks >results/result-01.tsv
$ tr '\t' , <results/result-01.tsv >results/result-01.csv
```

See results in the [`results`](results) directory.
