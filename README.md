# SCUT Social Practice Form

A Typst template for student social-practice registration forms.

## Use as a template

Choose this package in the Typst Universe template gallery, then fill in the
values in `template/main.typ`.

## Use as a package

Once this package has been accepted into Typst Universe, import it with:

```typst
#import "@preview/scut-social-practice-form:0.1.0": social_practice_form

#social_practice_form(
  name: [张三],
  political-status: [共青团员],
  hometown: [广东省广州市],
  college: [软件学院],
  major: [软件工程],
  grade: [2024 级],
  practice-unit: [华南理工大学],
)
```

All content parameters are optional. Pass content in square brackets, which
also supports multiple paragraphs for long-form fields.

## Publishing

Before submitting a release, set the `repository` field in `typst.toml` to the
public source repository URL. Submit the complete package directory to
[`typst/packages`](https://github.com/typst/packages) under
`packages/preview/scut-social-practice-form/0.1.0`.

Confirm that you are authorized to publish the form design and any associated
institutional names or marks before distribution.

## License

MIT.
