# Mandelbrot Set
Rust generator for the Mandelbrot set as found in Programming Rust - O'Reilly.


Requires an installation of Rust as found here: https://rustup.rs/

To run locally: 

`cargo new mandelbrot`

`cd mandelbrot`

Replace `cargo.toml` and `src/main.rs` with the versions here. 

Run: `time target/release/mandelbrot mandel.png 4000x3000 -1.20,0.35 -1,0.20`

For the same image as linked. 

Or adjust the arguements as desired.

Arguments: `filename, image dimensions, upperleft coordinates, lower right coordinates` 

🚀
