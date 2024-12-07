# Advent of Code

Welcome to my **Advent of Code** solutions in Rust!

[Advent of Code](https://adventofcode.com/) is an annual coding challenge event that runs every December, offering a new programming puzzle each day leading up to Christmas. The puzzles are designed to be fun, challenging, and a great way to sharpen your coding skills. Participants from all around the world compete to solve these puzzles as quickly as possible.

This repository is a collection of my solutions to the Advent of Code puzzles. Each folder contains my approach and code for the corresponding day's challenge.

## Progress

```shell
2015 [-------------------------] 00/25
2016 [-------------------------] 00/25
2017 [-------------------------] 00/25
2018 [-------------------------] 00/25
2019 [-------------------------] 00/25
2020 [-------------------------] 00/25
2021 [-------------------------] 00/25
2022 [-------------------------] 00/25
2023 [-------------------------] 00/25
2024 [-------------------------] 00/25
```

## Commands

Create new files for a day

```shell
just create <year> <day>
```

## Dependencies

The following

```shell
rustup default nightly
cargo install cargo-nextest cargo-generate flamegraph
apt install just tracy
```

[cargo-flamegraph]: https://github.com/flamegraph-rs/flamegraph
[tracing_tracy]: https://docs.rs/tracing-tracy/0.10.4/tracing_tracy/index.html
[tracy]: https://github.com/wolfpld/tracy
[divan]: https://github.com/nvzqz/divan
[divan-announcement]: https://nikolaivazquez.com/blog/divan/
[divan:compared-to-criterion]: https://nikolaivazquez.com/blog/divan/#compared-to-criterion
[cargo-nextest]: https://nexte.st/
[cargo-nextest-execution-model]: https://nexte.st/book/how-it-works.html
[tracing]: https://docs.rs/tracing/0.1.40/tracing/index.html
