# CS110L Spring 2020: Safety in Systems Programming

## 课程简介
CS110L将带领我们学习 **Rust** ，这是一门注重 **安全、性能、工程** 的语言。

1. Why Rust？
    1. 我的浅显理解是：Rust 被设计出来旨在解决目前系统编程的困难，其特征 **“安全、性能、工程”** 也是应系统编程的需求而来。在事实上挑战了 C 的地位，Rust 试图在拥有媲美 C 的性能的同时改善 C 在安全、工程上的不足。
    2. [更详细的回答1（by Rust语言圣经）](https://course.rs/into-rust.html)
    3. [更详细的回答2（by Rust程序设计语言）](https://doc.rust-lang.org/stable/book/foreword.html)

2. For Who？
    + For everyone. 别质疑，先学习！

## 参考资料
1. [2020版本 课程官网](https://reberhardt.com/cs110l/spring-2020/)
2. [2022版本 课程官网](https://web.stanford.edu/class/cs110l/)
3. [Rust 程序设计语言](https://rustwiki.org/zh-CN/book/title-page.html)
4. [Rust 语言圣经](https://course.rs/about-book.html)
5. [Rust 异步编程](https://huangjj27.github.io/async-book/index.html)
6. [PKUFlyingPig 代码实现](https://github.com/PKUFlyingPig/CS110L)

## 作业&项目
1. [Exercises 1: Hello world](https://github.com/fung-hwang/CS110L-2020spr/tree/main/week1)
2. [Exercises 2: Ownership and structs](https://github.com/fung-hwang/CS110L-2020spr/tree/main/week2)
3. [Exercises 3: Error handling, I/O, and traits](https://github.com/fung-hwang/CS110L-2020spr/tree/main/week3)
4. [Exercises 4: Farm meets multithreading](https://github.com/fung-hwang/CS110L-2020spr/tree/main/week5)
5. [Exercises 5: Sharing Data by Communicating](https://github.com/fung-hwang/CS110L-2020spr/tree/main/week6)
6. [Project 1: The DEET Debugger](https://github.com/fung-hwang/CS110L-2020spr/tree/main/proj-1)
7. [Project 2: Balancebeam](https://github.com/fung-hwang/CS110L-2020spr/tree/main/proj-2)

## 一些说明
1. 当我2022年11月计划学习 Rust 并从 [CS自学指南](https://csdiy.wiki/) 发现本课程时，Thea Rossman 的 [2022版本CS110L](https://web.stanford.edu/class/cs110l/assignments/week-1-exercises/) 似乎把代码库设为仅选修该课程的本校同学可见，并且没有公开课程视频。所以我们仍关注 Ryan Eberhardt & Armin Namavari 的 [2020版本CS110L](https://reberhardt.com/cs110l/spring-2020/) 。二者稍有区别但对 Rust 学习不会产生实质影响：
    + 课程内容稍有改动，涉及课程讲义、作业和项目，但仅是细节处的优化。二者可对比参照。
    + Rust 在近几年快速演进，2020版本的项目所使用的库可能过于老旧而不再支持。可以预见的是 Rust 及 Rust 库会持续更新，如果 CS110L 继续闭源，是时可参考 [Project-1 适配说明](https://github.com/fung-hwang/CS110L-2020spr/blob/main/proj-1/README.md) 和 [Project-2 适配说明](https://github.com/fung-hwang/CS110L-2020spr/blob/main/proj-2/README.md) 而自行适配。
    + 感谢 [@ridethepig](https://github.com/ridethepig) 于2023.03.08所做的[适配工作](https://github.com/fung-hwang/CS110L-2020spr/pull/2)，补全了 project-1 在之前未能适配的部分。
2. Rust库适配过程本质上是API查阅的过程，我通常的做法是：
    1. `cargo check/cargo build` 查看并分析错误（ Rust 编译器也是重要的学习工具）
    2. 在 [lib.rs](lib.rs) 或 [crates.io](crates.io) 上搜索库并查看版本更新、库简介、使用说明、库特征等。
    3. 在API文档中查找所需要的API，并可以与旧版API进行比较（不由得感叹 Rust 的文档用起来太舒服了~）。

## 写在最后
1. Rust以学习曲线陡峭著称，不可否认，但也不必担心。我想，除了语言开发团队在语言的各种特性上的取舍与平衡，我们使用者也在付出和获得间取得平衡——更多的付出与更好的代码。
2. [“Linux合入Rust代码”](https://en.wikipedia.org/wiki/Rust_for_Linux)已证明其能力，拭目以待 Rust 生态的发展 :)

