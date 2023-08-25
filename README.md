[![GitHub Build Actions][build-action-img]][actions]
[![GitHub Release Actions][release-action-img]][actions]
[![Coverage Status][cov-img]][cov]

[cov-img]: https://codecov.io/github/khulnasoft-lab/bench-common/branch/main/graph/badge.svg
[cov]: https://codecov.io/github/khulnasoft-lab/bench-common
[actions]: https://github.com/khulnasoft-lab/bench-common/actions
[build-action-img]: https://github.com/khulnasoft-lab/bench-common/workflows/build/badge.svg
[release-action-img]: https://github.com/khulnasoft-lab/bench-common/workflows/release/badge.svg

# Build and Test
## Requirement
1. Docker CE
1. Docker Compose

## Run
1. go build
1. docker-compose up

## Alternatively
1. go build
1. docker build -t khulnasoft-lab/app-bench .
1. docker run -it khulnasoft-lab/app-bench
