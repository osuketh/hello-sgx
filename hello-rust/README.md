# Hello intel sgx in rust
Quick tutorial of SGX programming in Rust using [Rust SGX SDK](https://github.com/baidu/rust-sgx-sdk).

## Usage
```
$ git clone git@github.com:osuketh/hello-sgx.git
$ cd hello-sgx
$ docker pull baiduxlab/sgx-rust
$ docker run -v `pwd`:/root/sgx  --rm -it baiduxlab/sgx-rust
$ cd /root/sgx
$ make
$ cd bin
$ ./app
```
