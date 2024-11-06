
> [!NOTE]
> It’s recommended to organize Rust projects within a dedicated directory, such as projects, to maintain a structured workspace.


**Practice-01:** Create a file named main.rs and include the following code:

```Rust
fn main() {
    println!("Hello, world!");
}
```

- This program defines the main function, which serves as the entry point of a Rust executable.
- The println! macro outputs the string “Hello, world!” to the console.

**Practice-02:** Use the Rust compiler `rustc` to compile the program:

```Shell
$ rustc main.rs
````

This command produces an executable file (main on Unix-like systems or main.exe on Windows) in the current directory.

**Practice-03:** Execute the compiled program by running:

```Shell
$ ./main      # On Unix-like systems
$ .\main.exe  # On Windows
```


- `fn main() { ... }` declares the main function, which is the starting point of execution for Rust programs.
- `println!("Hello, world!");` Calls the `println!` macro to print text to the console. The exclamation mark indicates that `println!` is a macro, not a regular function.
- Compiling and running are separate steps. Rust is an ahead-of-time compiled language, meaning the source code is compiled into an executable before running. This is different from interpreted languages, where code is executed directly without a separate compilation step.
- Compiling the code ensures that the program is checked for errors before execution and can be distributed as a standalone executable that doesn’t require the Rust compiler to run.