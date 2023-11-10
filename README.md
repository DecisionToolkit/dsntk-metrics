**DSNTK** | Decision Toolkit

# Metrics

[![MIT licensed][mit-badge]][mit-url]
[![Apache 2.0 licensed][apache-badge]][apache-url]
[![Contributor Covenant][cc-badge]][cc-url]

[mit-badge]: https://img.shields.io/badge/License-MIT-blue.svg
[mit-url]: LICENSE-MIT
[apache-badge]: https://img.shields.io/badge/License-Apache%202.0-blue.svg
[apache-url]: LICENSE-APACHE
[cc-badge]: https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg
[cc-url]: CODE_OF_CONDUCT.md

## Overview

Metrics presented in this repository are intended to provide objective measures
of [**Decision Toolkit**](https://github.com/dsntk/dsntk-rs)'s maturity,
based on a range of performance and reliability criteria.

To assess **Decision Toolkit**'s maturity, the following metrics has been adopted:
- [Number of passing compatibility tests](./compatibility/README.md)
- [Percentage of source code coverage](./coverage/README.md)
- [Time of decision model evaluation](./performance/README.md)

## Adopted approach

Edwards W. Deming said:

*"It is wrong to suppose that if you can’t measure it, you can’t manage it – a costly myth."*

Although it could be possible to manage a project like **Decision Toolkit** without any measurements,
it is essential to track such key indicators like compatibility testing, code coverage,
and model execution time, to maintain a high level of quality that meets user expectations.

The first goal is reaching the full DMN™ standard conformance on level 3.
Successfully passing compatibility tests provides a high level of confidence
that the project is on track to achieve this goal.
Surely, until [Technology Compatibility Kit for the Decision Model and Notation (DMN) standard](https://github.com/dmn-tck/tck)
does not provide the complete compatibility testing suite, it can't be assured, that this conformance level is achieved in 100%.
Supporting the development of compatibility tests is one of key priorities.

The second goal is to be able to optimize and refactor the code base without the risk
of spoiling the existing functionality. Large set of unit tests provides a high level of code coverage,
which means, that when something goes wrong, the failing test will raise an alert.

The third goal is the excellent performance. Performance optimization is easier, when all business
functionality is implemented, code coverage is high and extensive testing points out the performance bottlenecks.
This way the focus can be on performance improvements without the risk of spoiling functionalities users already love.

## Metrics summary

| version | date | compatibility<br/>tests | lines<br/>coverage | functions<br/>coverage | perf<br/>90% | perf<br/>99% |
|---------|:----:|:-----------------------:|:------------------:|:----------------------:|:------------:|:------------:|
|         |      |                         |                    |                        |              |              |

## License

Licensed under either of

- [MIT license](https://opensource.org/licenses/MIT) ([LICENSE-MIT][mit-url]) or
- [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0) ([LICENSE-APACHE][apache-url])

at your option.

## Contribution

Any contributions are greatly appreciated.
If you would like to get involved, please don't hesitate to reach out to us.
All contributions intentionally submitted for inclusion in the work by you,
shall be dual licensed as above, without any additional terms or conditions.
