# Rust vs Go
Which is better, Rust or Go? Which language should you choose for your next project, and why? How do the two compare in areas like performance, simplicity, safety, features, scale, and concurrency? What do they have in common, and where do they fundamentally differ? Let's find out, in this friendly and even-handed comparison of Rust and Golang, from the author of the For the Love of Go book series.

## Rust and Go are both awesome
First, it's really important to say that both Go and Rust are absolutely excellent programming languages. They're modern, powerful, widely-adopted, and offer excellent performance. You may have read articles and blog posts aiming to convince you that Go is better than Rust, or vice versa. But that really makes no sense; every programming language represents a set of trade-offs. Each language is optimised for different things, so your choice of language should be determined by what suits you and the problems you want to solve with it.

In this article, I'll try to give a brief overview of where I think Go is the ideal choice, and where I think Rust is a better alternative. I'll also try to give a flavour of the essential nature of both languages (the Tao of Go and Rust, if you like).

While they're very different in syntax and style, both Rust and Go are first-class tools for building software. With that said, let's take a closer look at the two languages.

## The similarities
Rust and Go have a lot in common, which is one reason you often hear them mentioned together. What are some of the common goals of both languages?

>Rust is a low-level statically-typed multi-paradigm programming language that’s focused on safety and performance.
>—Gints Dreimanis
>Go is an open source programming language that makes it easy to build simple, reliable, and efficient software.
>—Golang.org

## Memory safety

Both Go and Rust belong to the group of modern programming languages whose priority is memory safety. It's become clear over many decades of using older languages such as C and C++ that one of the biggest causes of bugs and security vulnerabilities is accessing memory unsafely or incorrectly. Rust and Go deal with this problem in different ways, but both aim to be smarter and safer than other languages about managing memory, and to help you write correct and performant programs.
// todo
# Rust vs Go
 Rust 和 Go 哪个更好？ 你应该选择何种语言作为你的下一门语言，且为什么选择它？Rust 和 Go 怎样在 性能、 简易性、安全性、特性、规模、并发性等方面比较？他们有什么共同点和根本的不同？让我们从《 For the Love of Go》丛书的作者对 Rust 和 Golang 的友好而公正的比较中找出答案。

## Rust and Go 都是极好的
 首先，重要的是Go 和 Rust 都是十分卓越的编程语言。它们是现代的、功能强大的、被广泛采用的，并提供卓越的性能。您可能已经阅读了旨在说服您 Go 比 Rust 更好的文章和博客文章，反之亦然。但这真的没有意义；每种编程语言都代表了一组权衡。每种语言都针对不同的事物进行了优化，因此您选择的语言应取决于适合您的语言以及您想用它解决的问题。

 在本文中，我将尝试简要概述我认为 Go 是理想选择的地方，以及我认为 Rust 是更好选择的地方。我还将尝试介绍两种语言的本质（Go 和 Rust 之道，如果您愿意的话）。

 虽然它们在语法和风格上非常不同，但 Rust 和 Go 都是用于构建软件的一流工具。话虽如此，让我们仔细看看这两种语言。

## 简易性
Rust 和 Go 有很多共同点，这就是你经常听到他们一起提到的原因之一。两种语言的共同目标是什么？

>Rust 是一种接近底层静态类型多范式编程语言，专注于安全性和性能
>—Gints Dreimanis
>Go 是一种开源编程语言，可以轻松构建简单、可靠和高效的软件。
>—Golang.org

## 内存安全
Go 和 Rust 都属于优先考虑内存安全的现代编程语言组。在使用 C 和 C++ 等旧语言的几十年中，很明显，错误和安全漏洞的最大原因之一是不安全或不正确地访问内存。Rust 和 Go 以不同的方式处理这个问题，但两者都旨在在管理内存方面比其他语言更智能、更安全，并帮助您编写正确和高性能的程序。