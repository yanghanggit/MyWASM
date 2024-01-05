# MyWASM
wasm 空工程，试一试

编译C代码到WebAssembly：使用Emscripten编译器将C代码编译成WebAssembly。在终端中运行：
emcc hello.c -s WASM=1 -o hello.html
这会生成hello.html，hello.js和hello.wasm文件。

步骤三：运行WebAssembly代码
在本地服务器上运行：由于安全原因，您不能直接从文件系统运行Wasm文件，需要通过HTTP服务器。您可以使用Node.js安装一个简单的HTTP服务器：

npm install -g http-server

http-server
