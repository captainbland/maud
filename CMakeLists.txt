cmake_minimum_required(VERSION 3.12)
project(maud)

set(CMAKE_CXX_STANDARD 14)

add_executable(maud
    benchmarks/benches/askama.rs
    benchmarks/benches/complicated_maud.rs
    benchmarks/benches/handlebars.rs
    benchmarks/benches/horrorshow.rs
    benchmarks/benches/liquid.rs
    benchmarks/benches/maud.rs
    benchmarks/benches/tera.rs
    benchmarks/src/main.rs
    benchmarks/Cargo.lock
    benchmarks/Cargo.toml
    maud/src/lib.rs
    maud/tests/basic_syntax.rs
    maud/tests/control_structures.rs
    maud/tests/misc.rs
    maud/tests/splices.rs
    maud/Cargo.toml
    maud_extras/Cargo.toml
    maud_extras/lib.rs
    maud_extras/README.md
    maud_htmlescape/Cargo.toml
    maud_htmlescape/lib.rs
    maud_macros/src/ast.rs
    maud_macros/src/generate.rs
    maud_macros/src/lib.rs
    maud_macros/src/parse.rs
    maud_macros/Cargo.toml
    Cargo.toml
    CHANGELOG.md
    CONTRIBUTING.md
    LICENSE-APACHE
    LICENSE-MIT
    maud.png
    README.md
    rust-toolchain)
