# Changelog

## [0.6.1](https://github.com/feeph/pypackage-template/compare/v0.6.0...v0.6.1) (2025-03-19)


### Bug Fixes

* suppress uv's progress bars in GitHub Actions ([#38](https://github.com/feeph/pypackage-template/issues/38)) ([4dc72ae](https://github.com/feeph/pypackage-template/commit/4dc72ae7b52ffbcac1a05f58d69f4a0e355e6c36))

## [0.6.0](https://github.com/feeph/pypackage-template/compare/v0.5.3...v0.6.0) (2025-03-19)


### Features

* provide a module and unittest template ([#35](https://github.com/feeph/pypackage-template/issues/35)) ([9a9b1e4](https://github.com/feeph/pypackage-template/commit/9a9b1e41b73f6f8aee71797c85199e0442a73a8c))


### Documentation

* update and improve README.md ([#37](https://github.com/feeph/pypackage-template/issues/37)) ([b0cda4c](https://github.com/feeph/pypackage-template/commit/b0cda4cd2bde866ce21a6e9db86d5f52273fe4af))

## [0.5.3](https://github.com/feeph/pypackage-template/compare/v0.5.2...v0.5.3) (2025-03-19)


### Bug Fixes

* add missing curly braces to template ([#33](https://github.com/feeph/pypackage-template/issues/33)) ([4f2acab](https://github.com/feeph/pypackage-template/commit/4f2acabbbbda48465e77743a1f80d789f9e859b1))

## [0.5.2](https://github.com/feeph/pypackage-template/compare/v0.5.1...v0.5.2) (2025-03-19)


### Bug Fixes

* copier must not be run with `uv run ...` ([#31](https://github.com/feeph/pypackage-template/issues/31)) ([7d21947](https://github.com/feeph/pypackage-template/commit/7d219470148aad1f869e30c9203d127c98502087))

## [0.5.1](https://github.com/feeph/pypackage-template/compare/v0.5.0...v0.5.1) (2025-03-19)


### Bug Fixes

* improve the template ([#29](https://github.com/feeph/pypackage-template/issues/29)) ([a90d6d2](https://github.com/feeph/pypackage-template/commit/a90d6d29a2f72a4bdcc65663d04d2e642558e2f4))

## [0.5.0](https://github.com/feeph/pypackage-template/compare/v0.4.1...v0.5.0) (2025-03-18)


### Features

* refactor the template to use 'uv' instead of 'pdm' and improve it ([#26](https://github.com/feeph/pypackage-template/issues/26)) ([2651399](https://github.com/feeph/pypackage-template/commit/26513992cdfca2bfd5d07fd3d7e4ae9b0fdf69f5))


### Documentation

* update README.md ([#28](https://github.com/feeph/pypackage-template/issues/28)) ([d23351d](https://github.com/feeph/pypackage-template/commit/d23351d7630708bda6304c444cabb522eedce47f))

## [0.4.1](https://github.com/feeph/pypackage-template/compare/v0.4.0...v0.4.1) (2024-08-22)


### Bug Fixes

* use underscore instead of dash and replace as needed ([#24](https://github.com/feeph/pypackage-template/issues/24)) ([2a783cf](https://github.com/feeph/pypackage-template/commit/2a783cfecd44965af1edaf7628d015221d171cef))

## [0.4.0](https://github.com/feeph/pypackage-template/compare/v0.3.2...v0.4.0) (2024-08-20)


### Features

* allow dash in package name ([#22](https://github.com/feeph/pypackage-template/issues/22)) ([07cde92](https://github.com/feeph/pypackage-template/commit/07cde92199bd3be1d381ef239d3a779d46ad6d7d))

## [0.3.2](https://github.com/feeph/pypackage-template/compare/v0.3.1...v0.3.2) (2024-08-13)


### Bug Fixes

* don't ask for already known config items ([#20](https://github.com/feeph/pypackage-template/issues/20)) ([3e7f6c9](https://github.com/feeph/pypackage-template/commit/3e7f6c974cfecd375e42530ca3cf1b59b7beba0d))

## [0.3.1](https://github.com/feeph/pypackage-template/compare/v0.3.0...v0.3.1) (2024-08-13)


### Bug Fixes

* add missing dependency 'coverage-lcov' ([#18](https://github.com/feeph/pypackage-template/issues/18)) ([b431d01](https://github.com/feeph/pypackage-template/commit/b431d01361cf5f1794689c52cf0422204aa554f5))

## [0.3.0](https://github.com/feeph/pypackage-template/compare/v0.2.2...v0.3.0) (2024-08-13)


### Features

* generate a code coverage badge (using coveralls.io) ([59543c5](https://github.com/feeph/pypackage-template/commit/59543c5400413c667b76d75a48e772962929a72c))
* improve template definition ([1e5de4c](https://github.com/feeph/pypackage-template/commit/1e5de4cc893da491616ac4cc65e25472f24c01e9))


### Bug Fixes

* do not generate a coverage report from tox ([585b961](https://github.com/feeph/pypackage-template/commit/585b961451bcfd96b75fce4b44a3489957e66d45))
* run code validation on pull requests, not push ([5cfae54](https://github.com/feeph/pypackage-template/commit/5cfae546c4ec9712755c6285f67f5c88a1f6f36a))


### Documentation

* update comment to explain why we run tox with --no-cov ([f988ee6](https://github.com/feeph/pypackage-template/commit/f988ee60a4661b2985928163a667520dc651dff9))

## [0.2.2](https://github.com/feeph/pypackage-template/compare/v0.2.1...v0.2.2) (2024-08-13)


### Bug Fixes

* remove trailing slash in repository_url ([#14](https://github.com/feeph/pypackage-template/issues/14)) ([5793e83](https://github.com/feeph/pypackage-template/commit/5793e83ee2d91efc91b2e242602ad4ca68a5a9bb))

## [0.2.1](https://github.com/feeph/pypackage-template/compare/v0.2.0...v0.2.1) (2024-08-13)


### Documentation

* replace 'renovate' with 'dependabot' in README.md ([6d73c2b](https://github.com/feeph/pypackage-template/commit/6d73c2bde6b498f1a5d061abaf3b4b1ecc207949))
* replace renovate with dependabot in README.md (2) ([3c4e448](https://github.com/feeph/pypackage-template/commit/3c4e448c9e5bae025c5fb6285539d31c207a0f19))

## [0.2.0](https://github.com/feeph/pypackage-template/compare/v0.1.3...v0.2.0) (2024-08-13)


### Features

* provide a script for installing the git hooks ([#10](https://github.com/feeph/pypackage-template/issues/10)) ([6b5f1f0](https://github.com/feeph/pypackage-template/commit/6b5f1f05775c181217bd8c3a9b1967bdeef14f39))
* switch back to dependabot (with custom config) ([#12](https://github.com/feeph/pypackage-template/issues/12)) ([49271bc](https://github.com/feeph/pypackage-template/commit/49271bc12f7445de016e50416c55430279dddc1d))

## [0.1.3](https://github.com/feeph/pypackage-template/compare/v0.1.2...v0.1.3) (2024-07-28)


### Bug Fixes

* fix template definitions ([f5a76c0](https://github.com/feeph/pypackage-template/commit/f5a76c02ac7f59173a833eafcae4dec199917ca9))
* tune Jinja settings ([1247253](https://github.com/feeph/pypackage-template/commit/1247253450ebd833e71df65161eaa18bba4f1ed0))

## [0.1.2](https://github.com/feeph/pypackage-template/compare/v0.1.1...v0.1.2) (2024-07-28)


### Documentation

* replace 'dependabot' with 'renovate' in README.md ([#5](https://github.com/feeph/pypackage-template/issues/5)) ([bc47352](https://github.com/feeph/pypackage-template/commit/bc47352ba76a448cf03ba5cb4090f37b7b5292b3))

## [0.1.1](https://github.com/feeph/pypackage-template/compare/v0.1.0...v0.1.1) (2024-07-28)


### Bug Fixes

* Update scripts/update_copier-templates ([#3](https://github.com/feeph/pypackage-template/issues/3)) ([4f94e0f](https://github.com/feeph/pypackage-template/commit/4f94e0fdabcd0cb5a8f351b270100709914f644f))

## 0.1.0 (2024-07-28)


### Features

* create a copier template ([#1](https://github.com/feeph/pypackage-template/issues/1)) ([fe16de5](https://github.com/feeph/pypackage-template/commit/fe16de537bda0bcafe6d06da3c1b814b71af7e33))
