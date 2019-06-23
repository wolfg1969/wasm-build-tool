```
$ docker build -t wasm-build-tool .
$ cd /<source code directory>
$ docker run -v `pwd`:/src wasm-build-tool sh build.sh
```
