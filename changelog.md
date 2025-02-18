# Changelog

## [v0.6.5](https://github.com/devlooped/dotnet-retest/tree/v0.6.5) (2025-02-18)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.6.4...v0.6.5)

:sparkles: Implemented enhancements:

- Bring changes from trx new verbosity levels [\#64](https://github.com/devlooped/dotnet-retest/pull/64) (@kzu)

:bug: Fixed bugs:

- Fix broken verbose reporting of successful tests [\#70](https://github.com/devlooped/dotnet-retest/pull/70) (@kzu)

:twisted_rightwards_arrows: Merged:

- Showcase that we can run/render 1k+ tests [\#71](https://github.com/devlooped/dotnet-retest/pull/71) (@kzu)
- Remove confusing and duplicate -v for version [\#67](https://github.com/devlooped/dotnet-retest/pull/67) (@kzu)

## [v0.6.4](https://github.com/devlooped/dotnet-retest/tree/v0.6.4) (2025-02-18)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.6.3...v0.6.4)

:bug: Fixed bugs:

- Avoid extra noise in log for CI builds [\#58](https://github.com/devlooped/dotnet-retest/issues/58)
- Column width inside Azure DevOps pipeline [\#54](https://github.com/devlooped/dotnet-retest/issues/54)
- Retry attempts are not working anymore in 0.6.X [\#48](https://github.com/devlooped/dotnet-retest/issues/48)
- Make retry logic more resilient to changes in xunit/vstest output [\#62](https://github.com/devlooped/dotnet-retest/pull/62) (@kzu)

:twisted_rightwards_arrows: Merged:

- Avoid noise in auto-update of progress [\#59](https://github.com/devlooped/dotnet-retest/pull/59) (@Tasteful)
- Send output directly to System.Console to avoid line breaks [\#55](https://github.com/devlooped/dotnet-retest/pull/55) (@Tasteful)

## [v0.6.3](https://github.com/devlooped/dotnet-retest/tree/v0.6.3) (2024-09-02)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.6.2...v0.6.3)

:sparkles: Implemented enhancements:

- Add a way to opt-out of the summary [\#31](https://github.com/devlooped/dotnet-retest/pull/31) (@kzu)

:hammer: Other:

- Command option to disable trx output [\#29](https://github.com/devlooped/dotnet-retest/issues/29)

:twisted_rightwards_arrows: Merged:

- Ensure readme is encoded in UTF-8 [\#33](https://github.com/devlooped/dotnet-retest/pull/33) (@kzu)
- Improve style disable when NO\_COLOR [\#30](https://github.com/devlooped/dotnet-retest/pull/30) (@kzu)

## [v0.6.2](https://github.com/devlooped/dotnet-retest/tree/v0.6.2) (2024-08-24)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.6.1...v0.6.2)

:bug: Fixed bugs:

- Fix issue when filename has \[ or \] characters [\#27](https://github.com/devlooped/dotnet-retest/pull/27) (@kzu)

## [v0.6.1](https://github.com/devlooped/dotnet-retest/tree/v0.6.1) (2024-08-08)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.6.0...v0.6.1)

## [v0.6.0](https://github.com/devlooped/dotnet-retest/tree/v0.6.0) (2024-08-07)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.5.0...v0.6.0)

:sparkles: Implemented enhancements:

- Rename attempts to retries [\#19](https://github.com/devlooped/dotnet-retest/pull/19) (@kzu)

## [v0.5.0](https://github.com/devlooped/dotnet-retest/tree/v0.5.0) (2024-08-07)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.4.1...v0.5.0)

:sparkles: Implemented enhancements:

- Add ouctome column and screenshots [\#18](https://github.com/devlooped/dotnet-retest/pull/18) (@kzu)

## [v0.4.1](https://github.com/devlooped/dotnet-retest/tree/v0.4.1) (2024-08-07)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.4.0...v0.4.1)

:sparkles: Implemented enhancements:

- Don't allow non-trx logger on non-Windows OS [\#17](https://github.com/devlooped/dotnet-retest/pull/17) (@kzu)
- Make progress description column multiline [\#16](https://github.com/devlooped/dotnet-retest/pull/16) (@kzu)
- Increase console verbosity to get better progress [\#15](https://github.com/devlooped/dotnet-retest/pull/15) (@kzu)

## [v0.4.0](https://github.com/devlooped/dotnet-retest/tree/v0.4.0) (2024-08-06)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.3.0...v0.4.0)

:sparkles: Implemented enhancements:

- Allow for extra loggers in addition to trx [\#14](https://github.com/devlooped/dotnet-retest/pull/14) (@kzu)
- Improve progress reporting by showing output [\#13](https://github.com/devlooped/dotnet-retest/pull/13) (@kzu)

## [v0.3.0](https://github.com/devlooped/dotnet-retest/tree/v0.3.0) (2024-07-31)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.2.3...v0.3.0)

## [v0.2.3](https://github.com/devlooped/dotnet-retest/tree/v0.2.3) (2024-07-29)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.2.2...v0.2.3)

## [v0.2.2](https://github.com/devlooped/dotnet-retest/tree/v0.2.2) (2024-07-29)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.2.1...v0.2.2)

:sparkles: Implemented enhancements:

- Bring fix for test error markup rendering [\#10](https://github.com/devlooped/dotnet-retest/pull/10) (@kzu)

## [v0.2.1](https://github.com/devlooped/dotnet-retest/tree/v0.2.1) (2024-07-29)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.2.0...v0.2.1)

## [v0.2.0](https://github.com/devlooped/dotnet-retest/tree/v0.2.0) (2024-07-21)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/v0.1.0...v0.2.0)

:sparkles: Implemented enhancements:

- Take into account duplicate FQN from theories [\#6](https://github.com/devlooped/dotnet-retest/pull/6) (@kzu)

## [v0.1.0](https://github.com/devlooped/dotnet-retest/tree/v0.1.0) (2024-07-21)

[Full Changelog](https://github.com/devlooped/dotnet-retest/compare/cc678481a604157a20545f0a37a4fe7e119a77b3...v0.1.0)

:sparkles: Implemented enhancements:

- Don't prefix trx report options unnecessarily [\#5](https://github.com/devlooped/dotnet-retest/pull/5) (@kzu)
- Run retest with sample on all platforms [\#3](https://github.com/devlooped/dotnet-retest/pull/3) (@kzu)

:twisted_rightwards_arrows: Merged:

- Showcase CI runs [\#4](https://github.com/devlooped/dotnet-retest/pull/4) (@kzu)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
