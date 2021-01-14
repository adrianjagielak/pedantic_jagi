# How to use the package

To use the lints add a dev dependency in your `pubspec.yaml`:

```yaml
dev_dependencies:
  pedantic_jagi: ^0.0.1
```

Then add an include in your `analysis_options.yaml` file:

```yaml
include: package:pedantic_jagi/analysis_options.yaml
```

If you using e.g. continuous builds,
they will likely fail whenever a new version of `package:pedantic_jagi`
is released.
To avoid this, specify a version of a dev dependency in your `pubspec.yaml`:

```yaml
dev_dependencies:
  pedantic_jagi: 0.0.1
```