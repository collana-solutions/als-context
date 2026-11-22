# @collana-solutions/als-context

## 3.2.1

### Patch Changes

- [#68](https://github.com/collana-solutions/als-context/pull/68) [`9637ece`](https://github.com/collana-solutions/als-context/commit/9637ece391431754b2b614197ad6eb2fd832be10) Thanks [@neotrow](https://github.com/neotrow)! - The package is now published as `@collana-solutions/als-context`. The API is unchanged, and the new name starts at 3.2.0 with the same code as the last `@neolution-ch/als-context` release. To migrate, replace the old package with the new one:
  
  ```shell
  npm uninstall @neolution-ch/als-context
  npm install @collana-solutions/als-context
  ```
  
  Then change every `import` and `require` of `@neolution-ch/als-context` to `@collana-solutions/als-context`, including the webpack `IgnorePlugin` pattern if you use one:
  
  ```js
  config.plugins.push(new IgnorePlugin(/^(@collana-solutions\/als-context)$/));
  ```
  
  `@neolution-ch/als-context` gets deprecated and receives no further releases.

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.2.0] - 2023-07-25

### Added

-   added generic return value for `run` method

## [3.1.3] - 2022-04-06

### Changed

-   Changed relase branch to create prs with normal commit

### Added

-   Added license file

## [3.1.2] - 2022-04-05

### Changed

-   Fixed readme
-   Updated minimist to 1.2.6 because of security issues: <https://github.com/neolution-ch/als-context/security/dependabot/2>

## [3.1.1] - 2022-04-05

-   Fixed CD pipeline action

## [3.1.0] - 2022-04-05

-   Modified github action
-   Added readme

## [3.0.1] - 2022-03-01

-   Just testing things...

## [3.0.0] - 2022-03-01

-   made package open source
-   moved packaged to github
-   oh i forgot to add this.

## [1.0.0] - 2022-01-10

### Added

-   created package :tada: 

[3.2.0]: https://github.com/neolution-ch/als-context/compare/3.1.3...3.2.0

[3.1.3]: https://github.com/neolution-ch/als-context/compare/3.1.2...3.1.3

[3.1.2]: https://github.com/neolution-ch/als-context/compare/3.1.1...3.1.2

[3.1.1]: https://github.com/neolution-ch/als-context/compare/3.1.0...3.1.1

[3.1.0]: https://github.com/neolution-ch/als-context/compare/3.0.1...3.1.0

[3.0.1]: https://github.com/neolution-ch/als-context/compare/3.0.0...3.0.1

[3.0.0]: https://github.com/neolution-ch/als-context/compare/1.0.0...3.0.0
