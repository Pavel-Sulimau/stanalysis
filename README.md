# Stanalysis

This package provides an opinionated Dart linter rule set that help to keep a codebase maintainable.
The rules provided by this package listed in [lib/analysis_options.yaml](lib/analysis_options.yaml).

Take a look at [Linter for Dart](https://dart-lang.github.io/linter/lints) to get acquainted with
all the rules available for Dart.


## Usage

To use the lints, add a dev dependency in your `pubspec.yaml`:

```yaml
dev_dependencies:
  stanalysis:
    git: https://github.com/Pavel-Sulimau/stanalysis.git
```

Then, add an include in `analysis_options.yaml`:

```yaml
include: package:stanalysis/analysis_options.yaml
```
