# Closing Thoughts
This tutorial should get you started with a basic understanding of the flow of a `ratatui` program.
However, this is only *one* way to create a `ratatui` application. Because `ratatui` is relatively low level compared to other UI frameworks, almost any application model can be implemented. You can explore more of these in [Concepts: Application Patterns](./../concepts/application-patterns.md) and get some inspiration for what model will work best for your application. 

## Finished Files
Here you can find the finished project used for the tutorial.
You can test this application by yourself, but running 
```
cargo run > test.json
```
and double checking the output.

#### Main.rs
```rust,no_run,noplayground
{{#include ../../ratatui-book-tutorial-project/src/main.rs:all}}
```

#### App.rs
```rust,no_run,noplayground
{{#include ../../ratatui-book-tutorial-project/src/app.rs:all}}
```

#### UI.rs
```rust,no_run,noplayground
{{#include ../../ratatui-book-tutorial-project/src/ui.rs:all}}
```
