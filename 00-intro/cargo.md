- Cargo is Rust’s build system and package manager, streamlining tasks like building code, managing dependencies, and creating distributable packages.
- Use `cargo new project_name` to generate a new Rust project. This command creates a directory named `project_name` containing a `Cargo.toml` file and a `src` directory with a `main.rs` file.
    
    **Practice-01:** Create a new Rust project with the following code:

    ```Shell
    $ cargo new hello_cargo
    ```
- The `Cargo.toml` file is the manifest for the project, specifying metadata like the package name, version, edition, and dependencies.
- Cargo organizes code within the `src` directory, keeping the top-level directory for configuration, files and metadata.
- Run `cargo build` to compile the project. The compiled executable is placed in the `target/debug directory`.
    
    **Practice-02:** Build your project using Cargo with the following code:

    ```Shell
    $ cargo build
    ```
- Use `cargo run` to build and execute the project in a single step, simplifying the development workflow.
    
    **Practice-03:** Build and run your project using Cargo with the following code:

    ```Shell
    $ cargo run
    ```
- The `cargo check` command quickly checks the code for compilation errors without producing an executable, offering a faster feedback loop during development.
    
    **Practice-04:** Check your project using Cargo with the following code:

    ```Shell
    $ cargo check
    ```
- For optimized, production-ready executables, use `cargo build --release`. This command compiles the project with optimizations and places the output in the `target/release` directory.
Cargo commands are consistent across different operating systems, providing a unified development experience.
    
    **Practice-05:** Build a release of your project using Cargo with the following code:

    ```Shell
    $ cargo build --release
    ```
- Even for simple projects, Cargo offers benefits like standardized project structure, dependency management, and streamlined build processes, making it a valuable tool for Rust developers.

## References
- [Rust Documentation](https://doc.rust-lang.org/stable/book/ch01-03-hello-cargo.html)