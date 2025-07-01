# 🌐 Cross-Platform Open Source C++ Header Libraries

## ⚙️ General Utilities

- **[Boost](https://www.boost.org/)**
  - Massive set of libraries (many header-only).
  - Includes `Boost.Asio`, `Boost.Filesystem`, `Boost.SmartPtr`, `Boost.Optional`, etc.
  - Header example: `<boost/optional.hpp>`

- **[fmt](https://github.com/fmtlib/fmt)**
  - Modern string formatting library (C++20's `std::format` is based on it).
  - Header: `#include <fmt/core.h>`

- **[Catch2](https://github.com/catchorg/Catch2)**
  - Unit testing framework, header-only.
  - Header: `#include <catch2/catch.hpp>`

- **[doctest](https://github.com/doctest/doctest)**
  - Lightweight testing framework, header-only.
  - Header: `#include <doctest/doctest.h>`

---

## 📖 Math / Geometry

- **[Eigen](https://eigen.tuxfamily.org/)**
  - Linear algebra (matrices, vectors), header-only.
  - Header: `#include <Eigen/Dense>`

- **[glm](https://github.com/g-truc/glm)**
  - OpenGL Mathematics, header-only.
  - Header: `#include <glm/glm.hpp>`

- **[xtensor](https://github.com/xtensor-stack/xtensor)**
  - N-dimensional arrays, NumPy-like syntax in C++.

---

## 🧵 Threading / Concurrency / Networking

- **[Asio](https://think-async.com/)**
  - Asynchronous networking and I/O.
  - Header-only version available: `#include <asio.hpp>`

- **[libuv](https://libuv.org/)**
  - Not header-only, but portable async I/O, used in Node.js.

- **[Taskflow](https://github.com/taskflow/taskflow)**
  - Parallel & heterogeneous task graphs (header-only).
  - Header: `#include <taskflow/taskflow.hpp>`

---

## 📁 Serialization / File I/O

- **[nlohmann/json](https://github.com/nlohmann/json)**
  - JSON parsing and serialization, header-only.
  - Header: `#include <nlohmann/json.hpp>`

- **[cereal](https://github.com/USCiLab/cereal)**
  - C++11 serialization library.
  - Header: `#include <cereal/archives/json.hpp>`

---

## 🖼️ Graphics / GUI

- **[Dear ImGui](https://github.com/ocornut/imgui)`**
  - Immediate mode GUI, partially header-only.
  - Header: `#include "imgui.h"`

- **[raylib](https://www.raylib.com/)**
  - Simple C library for games, but C++-friendly.
  - Not header-only but cross-platform.

- **[GLFW](https://www.glfw.org/)**
  - An openGL library
  - Header: `#include <GLFW/glfw3.h>`

---

## 🗿 Extras

- **[spdlog](https://github.com/gabime/spdlog)**
  - Fast logging library (uses `fmt`).
  - Header: `#include <spdlog/spdlog.h>`

- **[CLI11](https://github.com/CLIUtils/CLI11)`**
  - Command-line argument parser.
  - Header: `#include <CLI/CLI.hpp>`

- **[toml++](https://github.com/marzer/tomlplusplus)**
  - TOML config parser, C++17 and 20 compatible.
  - Header: `#include <toml++/toml.h>`

- **[cJSON](https://github.com/DaveGamble/cJSON)**
  - Json file parser.
  - Header: `#include <cJSON.h>`
