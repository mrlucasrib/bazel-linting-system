# bazel-linting-rules



## Usage

Example usage with [`thundergolfer/the-one-true-bazel-monorepo`](https://github.com/thundergolfer/the-one-true-bazel-monorepo):

```
bazel build //fruit_sorting/... --aspects @linting_rules//:lint.bzl%file_count_aspect --output_groups=report
```
