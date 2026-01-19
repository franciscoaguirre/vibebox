# vibebox

This is my personal script to set up a sandbox for LLMs to play in.

Just `cd` into a directory you want to work in and run `vibebox`.

## Features

- Filesystem sandboxing: only the current directory is accessible within the container.
- Persistent $HOME directory within the sandbox, with the rest of the system being ephemeral.
- Ubuntu-based image, with support for C, C++, Rust, Python, Ruby, Node.js and CUDA.
- Fake root access within the container, with password-less `sudo`.
- Has Claude Code, OpenCode and Mistral Vibe preinstalled.
- Simple and easily customizable.

## License

Licensed under either of

  * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
  * MIT license ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
