<div align="center">
    <a href="https://www.rust-lang.org/">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/Original_Ferris.svg">
    </a>
    <h1>rust</h1>
    <span>Trying to learn rust with examples</span>
</div>

## Introduction

I'm documenting my journey of learning rust. You can go through the examples and learn with me. This journal is not meant to be a tutorial, but rather a collection of examples that I found to be useful and educational and it will be updated as I learn more.

Each example will be in a separate folder with an empty script file. The content of the file will be empty by default. This is to encourage you to write the code yourself and not just copy-paste it. So, this is more of a learn-by-doing approach.

Here's a list with some of the resources I'm using to learn rust:
- [The Rust Programming Language](https://doc.rust-lang.org/book/)
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/)
- [Rust Book Experiment](https://rust-book.cs.brown.edu/)

---

## 1: Installation
First step is to install the rustup toolchain manager. Use the following script to officially install rustup:
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

> From [rustup.rs](https://rustup.rs/)

---

## 2: Hello World
Sigh, let's get over with it.

`~/hello_world.rs`
```
fn main(){
    println!("Hello, world!");
}
```

Compile the script with `rustc` and run the executable:
```
$ rustc hello_world.rs
$ ./hello_world
----------------------
Hello, world!
```

---