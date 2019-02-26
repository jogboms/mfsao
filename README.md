# MFSAO

This package builds on the work from [Pedantic](https://github.com/dart-lang/pedantic) but tailored to my own needs.

## Enabled Lints

The currently enabled lints can be found in the sample
[analysis_options.yaml](https://github.com/jogboms/mfsao/blob/master/lib/analysis_options.yaml).

To use those lints you can add a dependency in your `pubspec.yaml`:

```yaml
dev_dependencies:
  mfsao: "0.1.0"
```

and add an include in your `analysis_options.yaml`:

```yaml
include: package:mfsao/analysis_options.yaml
```

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: https://github.com/jogboms/mfsao/issues
