# mandelbrot
Animation of the Mandelbrot fractal using AVX and OpenMP

I compile with

    gcc -O3 -Wall -Wextra -std=c11 -Wa,-q -mavx -march=native -mtune=native -fopenmp -framework SDL2 mandelbrot.c -o mandelbrot

but details may differ on a given system.
The important thing is enabling Advanced Vector Extensions (AVX), OpenMP and including SDL2.

![Screenshot of generated Mandelbrot fractal](https://raw.githubusercontent.com/andreasfrom/mandelbrot/master/screenshot.png)
