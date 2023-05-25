Compiling C code to [WASM(Web assembly)](https://webassembly.org/) using Emscripten.

- First install [Emscripten](https://emscripten.org/docs/getting_started/downloads.html).
- Compilation `emcc hello.c -o hello.html`.
- Run the html file through HTTP server.
  -Running simple local HTTP server:
   If Python version returned above is 3.X
   On Windows, try "python -m http.server" or "py -3 -m http.server"
   `python3 -m http.server`
