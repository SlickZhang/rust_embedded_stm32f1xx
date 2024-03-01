1. environment

[Rust Embedded开发环境搭建（Windows） - Slickzz - 博客园 (cnblogs.com)](https://www.cnblogs.com/slickzz/p/17232251.html)

1. build
```
cargo build
```

1. gdb
```
openocd -f interface/stlink-v2.cfg -f target/stm32f1x.cfg
```

1. flash
```
cargo run
```