

- l Rust的错误处理功能被设计为帮助你编写更加健壮的代码。
- l 使用panic!和Result/Option（是枚举类型）将会使你的代码在面对不可避免的错误时显得更加可靠。
- l 错误的处理，可以使用match，也可是使用unwrap、map、and_then、？等语法糖。
- l 若用户需要自定义错误类型，它需要同时实现 Error 与 From 两个 trait, 可以使用 thiserror和 anyhow来简化。

- https://lotabout.me/2017/rust-error-handling: 简谈 Rust 中的错误处理 | 三点水
- http://blog.honeypot.io/errors-and-exceptions-in-rust: Rust 处理错误异常的方式，介绍了不同语言处理异常的方式。
- https://news.ycombinator.com/item?id=9545647 : 关于 rust 为何不采用“异常处理”的讨论。
- http://www.infoq.com/cn/news/2012/11/go-error-handle : Go语言的错误处理机制引发争议。
- https://kaisery.github.io/trpl-zh-cn/ch09-00-error-handling.html: Rust 程序设计语言 简体中文版 错误处理

