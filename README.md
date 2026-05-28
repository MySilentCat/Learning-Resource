# Rust Learning Resources

## Rust for game

1. 丰富的入门资源，包括教程、书籍、示例：`https://arewegameyet.rs/#resources`

### 小型示例仓库

1. A multiplayer physics playground, written in rust. `https://github.com/Descrout/rust-multiplayer-physics`
2. An example websocket game server written in rust. `https://github.com/Descrout/rust-multiplayer-physics`
   - An example websocket game client. `https://github.com/Descrout/game-client`
3. a simple game in Rust and Piston with a Camera for 3D rendering. `https://github.com/Descrout/rust-multiplayer-physics`
4. A Tetris example written in Rust using Piston. `https://github.com/da-x/tetris-demo`

## Rust for Desktop app

1. A minimal Electron + WebAssembly (WASM) + Rust example. `https://github.com/anderejd/electron-wasm-rust-example`
2. 

## Rust code for Handbook

1. Packt `https://github.com/PacktPublishing?q=rust&type=all&language=&sort=`
   - Asynchronous-Programming-in-Rust
   - Practical-Data-Structures-and-Algos-in-Rust
   - Design-Patterns-and-Best-Practices-in-Rust
   - Rust-Web-Programming-3E
   - Distributed-Observability-For-Rust-Developers
   - Rust-Programming-Master-Class-from-Beginner-to-Expert
   - ...
2. Apress `https://github.com/Apress?q=rust&type=all&language=&sort=`
  - Deep-Learning-with-Rust
  - Practical-Rust-Projects-2nd-ed.
  - practical-rust-web-projects
  - practical-rust-projects
  - ...
3. ...

### Publisher

| 出版商 / 品牌                                | 常见源码位置                                             | 特点                                                                                                                                                                                                           |
| --------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Apress**                              | GitHub：`github.com/Apress`；官网也有 source-code 页面     | Apress 有官方 GitHub 组织，说明其仓库是“books published by Apress”的源码集合；很多仓库 README 会写明“accompanies 某书”，并提供 zip/clone 方式。([GitHub][1])                                                                                   |
| **Manning Publications**                | Manning 图书页面 / source-code 页面；大量作者或项目组织的 GitHub 仓库 | Manning 官方说明源码下载链接通常在图书产品页或用户 bookshelf 中；不少书也有公开 GitHub 仓库，例如 *Rust in Action*、*Istio in Action*、*Terraform in Action*。([Manning Publications][2])                                                          |
| **O’Reilly Media**                      | GitHub：`github.com/oreillymedia`；也常见作者个人仓库         | O’Reilly 有官方 GitHub 组织；部分书的示例代码直接在官方组织下，例如 *Using SVG* 仓库包含书中示例、截图、图示源码和额外资料。([GitHub][3])                                                                                                                   |
| **No Starch Press**                     | 作者 GitHub / 作者网站 / No Starch 图书资源 zip              | No Starch 不像 Apress 那样集中在一个统一官方 GitHub 组织下，常见模式是作者维护仓库或资源页。例如 *Python Crash Course* 有专门资源站，*Network Programming with Go*、*The Recursive Book of Recursion* 等有 GitHub 仓库或出版社资源 zip。([ehmatthes.github.io][4]) |
| **Pragmatic Bookshelf**                 | 图书页面、作者 GitHub、DevTalk/论坛中链接                       | Pragmatic Bookshelf 的源码分布较分散，很多书会在图书页面或书中给出仓库；例如论坛讨论中提到某书配套 GitHub 项目。它没有像 Packt/Apress 那样明显的统一源码组织。([Devtalk][5])                                                                                           |
| **Wiley / Wrox**                        | Wrox/Wiley 下载页、图书页面、作者 GitHub                      | Wrox/Wiley 传统上常通过官网提供源码下载；例如 Wiley Online Library 的书前言提到源码可从 `wrox.com` 下载。也有作者将 Wiley 图书代码放 GitHub。([Wiley Online Library][6])                                                                              |
| **Pearson / Addison-Wesley / InformIT** | InformIT 图书页面、作者 GitHub、历史 CD/zip 下载               | Addison-Wesley/Pearson 的源码常在 InformIT、作者站点或作者 GitHub。例如 *Effective Debugging*、*Machine Learning with Python for Everyone* 的源码在 GitHub；InformIT 页面也会提供配套源码下载。([GitHub][7])                                    |

[1]: https://github.com/apress?utm_source=chatgpt.com "Apress"
[2]: https://www.manning.com/source-code?utm_source=chatgpt.com "Source Code"
[3]: https://github.com/oreillymedia?utm_source=chatgpt.com "O'Reilly Media, Inc."
[4]: https://ehmatthes.github.io/pcc_3e/?utm_source=chatgpt.com "Python Crash Course, Third Edition"
[5]: https://forum.devtalk.com/t/distributed-services-with-go-chapter-1-suggestions/6979?utm_source=chatgpt.com "Distributed Services with Go: Chapter 1 Suggestions"
[6]: https://onlinelibrary.wiley.com/doi/chapter-epub/10.1002/9781119549147.fmatter?utm_source=chatgpt.com "professional c# 7 and .net core 2.0"
[7]: https://github.com/dspinellis/effective-debugging/?utm_source=chatgpt.com "dspinellis/effective-debugging: Code examples used in ..."


### Github Search Keyword

```text
site:github.com "published by Apress" "Source Code"
site:github.com "published by Manning" "source code"
site:github.com "published by No Starch Press" "code repository"
site:github.com "O'Reilly Media" "book examples"
site:github.com "Addison-Wesley" "source code"
site:github.com "Wiley book" "example code"
site:github.com "Wrox" "source code"
```

如果你的目标是找大量可用于学习、实验、数据集构建的技术书源码，优先顺序我建议是：

Packt → Apress → Manning → O’Reilly → No Starch Press → Pragmatic Bookshelf → Wiley/Wrox → Pearson/Addison-Wesley/InformIT

其中 Apress 和 Packt 最集中；Manning、No Starch、O’Reilly 更依赖具体作者或具体书；Wiley/Wrox、Addison-Wesley/Pearson 则经常是官网下载 zip 或作者个人 GitHub。

## Rust for Web

1.   Curated examples using the Actix ecosystem. `https://github.com/actix/examples`
2.   An Example Rust Application. `https://github.com/KodrAus/rust-web-app`

## Rust for Design

1. Rust 🦀 examples for all 23 classic GoF design patterns. `https://github.com/fadeevab/design-patterns-rust`

## Simple Example

1. Rust Domain Driven Design Example. ``
2. A repository to gather example codes from tutorial and other documentations. `https://github.com/eliovir/rust-examples`
3. A small Rust CLI example. `https://github.com/alfredodeza/rust-cli-example`
