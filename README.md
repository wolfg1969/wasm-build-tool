```
$ docker build -t wasm-build-tool .
$ cd /<source code directory>
$ docker run --rm -v `pwd`:/src wasm-build-tool sh build.sh
```
