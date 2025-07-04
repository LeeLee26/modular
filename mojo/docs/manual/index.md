---
title: "Mojo Manual"
sidebar_label: Introduction
description: A comprehensive guide to the Mojo programming language.
---

Welcome to the Mojo Manual, a complete guide to the Mojo🔥 programming language!

Mojo is designed to solve a variety of AI development challenges that no other
language can, because Mojo is the first programming language built from the
ground-up with [MLIR](https://mlir.llvm.org/) (a compiler infrastructure that's
ideal for heterogeneous hardware, from CPUs and GPUs, to various AI ASICs). We
also designed Mojo as the best way to extend Python because we love Python and its
community, but we couldn't realistically enhance Python to do all the things we
wanted. For a longer discussion on this topic, read [Why
Mojo](/mojo/why-mojo).

Beware that Mojo is still a very young language, so there's a lot that hasn't
been built yet. Likewise, there's a lot of documentation that hasn't been
written yet. But we're excited to share Mojo with you and [get your
feedback](https://www.modular.com/community).

## Contents

- **Get started**

  - [Why Mojo](/mojo/why-mojo)
  - [Get started with Mojo](/mojo/manual/get-started)

- **Language basics**

  - [Overview](/mojo/manual/basics)
  - [Functions](/mojo/manual/functions)
  - [Variables](/mojo/manual/variables)
  - [Types](/mojo/manual/types)
  - [Operators and expressions](/mojo/manual/operators)
  - [Control flow](/mojo/manual/control-flow)
  - [Errors and context managers](/mojo/manual/errors)
  - [Structs](/mojo/manual/structs)
  - [Modules and packages](/mojo/manual/packages)

- **Value ownership**

  - [Intro to value ownership](/mojo/manual/values/)
  - [Value semantics](/mojo/manual/values/value-semantics)
  - [Ownership](/mojo/manual/values/ownership)
  - [Lifetimes, origins, and references](/mojo/manual/values/lifetimes)

- **Value lifecycle**

  - [Intro to value lifecycle](/mojo/manual/lifecycle/)
  - [Life of a value](/mojo/manual/lifecycle/life)
  - [Death of a value](/mojo/manual/lifecycle/death)

- **Traits and parameters**

  - [Traits](/mojo/manual/traits)
  - [Parameterization: compile-time metaprogramming](/mojo/manual/parameters/)

- **Pointers**

  - [Intro to pointers](/mojo/manual/pointers/)
  - [Unsafe pointers](/mojo/manual/pointers/unsafe-pointers)

- **GPU programming**

  - [Intro to GPUs](/mojo/manual/gpu/architecture)
  - [Get started with GPU programming](/mojo/manual/gpu/intro-tutorial)
  - [GPU programming fundamentals](/mojo/manual/gpu/fundamentals)
  - [GPU basics](/mojo/manual/gpu/basics)

- **Layouts and LayoutTensor**

  - [Introduction to layouts](/mojo/manual/layout/layouts)
  - [Using LayoutTensor](/mojo/manual/layout/tensors)

- **Python**

  - [Python integration](/mojo/manual/python/)
  - [Calling Python from Mojo](/mojo/manual/python/python-from-mojo)
  - [Calling Mojo from Python](/mojo/manual/python/mojo-from-python)
  - [Python types](/mojo/manual/python/types)

- **Tools**

  - [Debugging](/mojo/tools/debugging)
  - [GPU debugging](/mojo/tools/debugging)
  - [Testing](/mojo/tools/testing)

- **Project information**

  - [Roadmap and sharp edges](/mojo/roadmap)
  - [Changelog](/mojo/changelog)
  - [FAQ](/mojo/faq)
