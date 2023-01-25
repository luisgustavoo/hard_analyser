# Hard Analyser

[![pub package](https://img.shields.io/pub/v/hard_analyser?style=flat-square)](https://pub.dev/packages/hard_analyser)

An analysis_options inspired by [strict](https://pub.dev/packages/strict) rules. Sometimes being [flutter_lints](https://pub.dev/packages/flutter_lints) isn't enough.

### Usage

Add this package to your `dev_dependencies` in your `pubspec.yaml`:

```yaml
dev_dependencies:
  hard_analyser: ^1.1.0
```

and the following to your `analysis_options.yaml` (create one in the root of your project if you don't
have it yet):

```yaml
  include: package:hard_analyser/analysis_options.yaml
```