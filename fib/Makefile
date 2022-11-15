build-fib:
	emcc fib.c -o build/fib.js -s WASM=1 -s EXPORTED_FUNCTIONS='["_fib"]' -s EXPORTED_RUNTIME_METHODS='["cwrap"]'
build-all:
	emcc fib.c -o build/fib.js -s WASM=1 -s EXPORTED_FUNCTIONS='["_fib", "_main"]' -s EXPORTED_RUNTIME_METHODS='["cwrap"]'
