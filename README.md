# 📦 sr25519

This Conan package builds and packages the sr25519-donna library.
The library was slightly modified to make the build working as static library. Check [TerenceGe/sr25519-donna](https://github.com/TerenceGe/sr25519-donna) for further instructions.

## Requirements

- Conan
- CMake
- A C++ compiler

## 🚀 Usage

Add this package to your project's `conanfile.txt`:

```ini
[requires]
sr25519/1.0.0@svnscha/dev

[generators]
cmake
```

## 🧪 Export the Package

To export the Conan package, navigate to the directory containing conanfile.py and run:

```sh
conan export --user svnscha --channel dev .
```

This exports the package to your local cache, usable by other projects.

## 🧪 Building the Package

For local development you could simply use

```sh
conan create .
```

or similar.
