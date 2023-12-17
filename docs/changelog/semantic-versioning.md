# Semantic Versioning

CoRA and its APIs, modules and analytical tools follow semamtic versioning. Major framework releases are released every year, while minor and patch releases may be released as often as every month. Minor and patch releases should never contain breaking changes.

## What is Semantic Versioning? { id="what-is-semantic-versioing" }

Semantic versioning is a formal convention for determining the version number of new software releases. The standard helps software users to understand the severity of changes in each new distribution.

A project that uses semantic versioning will advertise a Major, Minor and Patch number for each release. The version string. 

> 2.1.3

indicates a major version of 2, a minor version of 1 and a patch number of 3.


Version numbers using this format are widely used by both software packages and end-user executables such as apps and games. Not every project exactly follows the standard set out by [semver].

[semver]: https://semver.org/

The specification was created to address the problems caused by inconsistent versioning practices among software packages used as dependencies. By "package" and "dependency," we're referring to a library of code that's intended to be used within another software project and is distributed by a package manager such as

```shell
npm
```
```shell
composer
```

## Major, Minor and Patch { id="major-minor-patch" }

It's important to understand the meaning of the three components involved. Together, they chart a project's development journey and relate the end-user impact of each new release.

### Major number { id="major-number" }

The major number indicates the current version of the package's public interface. This should be incremented every time you make a change that would require existing users of your package to update their own work.

### Minor number { id="minor-number" }

The minor number describes the current functional release of your software. This is incremented whenever you add a new feature but do not otherwise alter your package's interface. It communicates to users that a significant change has been made but the package remains fully backwards compatible with the previous minor number.

### Patch number { id="patch-number" }

The patch number gets incremented every time you make a minor change that neither impacts the public interface or overall functionality of your package. This is most commonly used for bug fixes. Consumers should always be able to update to the latest patch release without hesitation.

The semantic versioning release structure is best modelled as a tree. At the top, you have your public interface changes, each of which result in a new major number. Every major series has its own set of minor releases, where new functionality is added in a backwards compatible manner. Finally, minor releases may receive bug-fixing patches from time-to-time.
