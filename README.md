# Stanalysis

This package provides Dart linter rules that help to keep a code base maintainable. For more information, see the [complete list of options](lib/analysis_options.yaml).

## Usage

To use the lints, add a dependency in your `pubspec.yaml`:

```yaml
# It can be a dev dependency.
dev_dependencies:
  ah_compact_analysis:
    path: packages/stanalysis
```

Then, add an include in `analysis_options.yaml`:

```yaml
include: package:stanalysis/analysis_options.yaml
```
