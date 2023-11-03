# Mandelbrot Set
Rust generator for the Mandelbrot set as found in Programming Rust - O'Reilly.

![image](https://github.com/PeterKaye0/MandelbrotSet/assets/143790185/3b12b345-874b-43ee-b329-8fe80ae5ab8a)


## To run locally: 

Requires an installation of Rust as found here: https://rustup.rs/

`cargo new mandelbrot`

`cd mandelbrot`

Replace `cargo.toml` and `src/main.rs` with the versions here. 

`cargo build --release`

Run: `target/release/mandelbrot mandel.png 4000x3000 -1.20,0.35 -1,0.20` For the same image as linked. 

Or adjust the arguements as desired.

Arguments: `filename, image dimensions, upperleft coordinates, lower right coordinates` 

For the whole set: `target/release/mandelbrot mandel.png 4000x3000 -2,1 0.5,0.5`


🚀
