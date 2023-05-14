# Stanalysis

This package provides an opinionated Dart linter rule set that help to keep a codebase maintainable.
Take a look at [Linter for Dart](https://dart-lang.github.io/linter/lints) to get acuanted with rules
available for Dart.

For more information, see the [complete list of options](lib/analysis_options.yaml).


## Usage

To use the lints, add a dependency in your `pubspec.yaml`:

```yaml
# It can be a dev dependency.
dev_dependencies:
  stanalysis:
    git: https://github.com/Pavel-Sulimau/stanalysis.git
```

Then, add an include in `analysis_options.yaml`:

```yaml
include: package:stanalysis/analysis_options.yaml
```
