# tue_lint_config
Linting/formatting configurations

## Packages

### cmake
ROS2 package containing configuration files for:
- `.clang-format`: Code formatting configuration for C++ files
- `.clang-tidy`: Static analysis configuration for C++ code

These configuration files are based on ROS2 best practices and can be used by other packages in the TU/e Robotics workspace.

#### Usage
After building this package with `colcon build`, the configuration files will be installed to:
```
install/cmake/share/cmake/.clang-format
install/cmake/share/cmake/.clang-tidy
```

You can reference or copy these files to your own packages to ensure consistent code style across the TU/e Robotics workspace.
