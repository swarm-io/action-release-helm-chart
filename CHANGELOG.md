## [1.0.2](https://github.com/swarm-io/action-release-helm-chart/compare/v1.0.1...v1.0.2) (2021-12-19)


### Bug Fixes

* Removed existence check, always delete alpha with soft fail if ref is main, always recreate alpha is ref is main. ([#4](https://github.com/swarm-io/action-release-helm-chart/issues/4)) ([cd85f1c](https://github.com/swarm-io/action-release-helm-chart/commit/cd85f1c561348846dcf027426617992801c26f46))

## [1.0.1](https://github.com/swarm-io/action-release-helm-chart/compare/v1.0.0...v1.0.1) (2021-12-19)


### Bug Fixes

* Add input to toggle include admins. ([#3](https://github.com/swarm-io/action-release-helm-chart/issues/3)) ([26c7d8a](https://github.com/swarm-io/action-release-helm-chart/commit/26c7d8a432074f2b70150da03cc7568f67071f1b))
* Remove redundent ref on checkout. Use the passed in token on checkout, which will allow bypassing PR requirements if a PAT is passed in. ([#2](https://github.com/swarm-io/action-release-helm-chart/issues/2)) ([fb6e544](https://github.com/swarm-io/action-release-helm-chart/commit/fb6e544cbc96f2f752f7c7488ff7c79e9b869a23))

# 1.0.0 (2021-12-18)


### Bug Fixes

* Created helm release action ([3321965](https://github.com/swarm-io/action-release-helm-chart/commit/3321965dddd3f8de369dcc77e1af916ca9db2685))
* fix checkout indent ([79911c3](https://github.com/swarm-io/action-release-helm-chart/commit/79911c38667135e2a0fb777af764a30d14e10688))
* fix checkout indent ([28007d4](https://github.com/swarm-io/action-release-helm-chart/commit/28007d4580186e527672dfad53f8ae07e377e372))
* fix checkout indent ([498f857](https://github.com/swarm-io/action-release-helm-chart/commit/498f857d032e03a74540719f5eb5a785171fba61))
* Initial release ([0d98cc7](https://github.com/swarm-io/action-release-helm-chart/commit/0d98cc7fcc4f92eda1ff9f6f123adf73de8dac77))
