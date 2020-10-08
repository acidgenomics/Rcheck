# R check

Scripts for Dockerized continuous integration tests.

Currently designed for use primarily with [Travis CI][].

Special globals:

- `CRAN=1`: Enable additional [CRAN][] submission checks. Note that this check doesn't work well with RStudio Package Manager (RSPM) enabled.
- `RCHECK_KEEP_IT_100=1`: Enforce 100% code coverage, checked via [covr][].
- `RCHECK_SKIP_COVERAGE=1`: Skip code coverage.
- `RCHECK_SKIP_UPDATE=1`: Skip dependency update step.

[covr]: https://cran.r-project.org/package=covr
[cran]: https://cran.r-project.org/
[travis ci]: https://travis-ci.com/
