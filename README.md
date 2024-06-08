We create a rust repo differently than we usually do (create repo on github, then git clone locally).
Instead of this, we go to our development folder, open a terminal in it, and run "cargo new repo_name", then on vscode you can publish it to your github as a public/private repo easily.

In rust, we keep dependencies in the Cargo.toml file, similar to requirements.txt in python.

In order to debug, you need the launch.json and tasks.json in the .vscode folder, and the Rust Analyser and LLDB DAP extensions.

You compile the code with cargo build, then there will be an executable in target/debug that you can run in the terminal to execute your program.

