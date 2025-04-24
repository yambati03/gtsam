## Python Wheels

The `build-cibw.yml` action automates building and publishing GTSAM Python wheels across Linux (x86_64, aarch64) and MacOS (x86_64, arm64) using `cibuildwheel`. The `cibuildwheel` tool is officially maintained by PyPA, and is used by [a number of other open-source projects](https://cibuildwheel.pypa.io/en/stable/working-examples/), including `scikit-learn` and `numpy`. Thus, it can be seen as the canonical way of building platform-dependent wheels.

### Workaround: Build Twice

### Workaround: Overwrite `ext_modules` 