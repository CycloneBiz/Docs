---
description: How Chroma works and how it is integrated
cover: >-
  https://images.unsplash.com/photo-1618601208313-0284d72da02c?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw0fHxsYXNlcnN8ZW58MHx8fHwxNjk2ODcwMTczfDA&ixlib=rb-4.0.3&q=85
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 💾 Software

## Backend Engine

Chroma is powered by Kotlin, a programming language that compiles into JVM bytecode like Java but provides greater security and a stable and performant coroutine API. This means that Chroma uses WPILib (just like your robot!) and has native AprilTag and NetworkTables support, with no external libraries. We also use KTOR that allows for native and reliant WebSockets and a fast HTTP server with Kotlin's coroutine system.

## Frontend UI

Chroma's UI is powered by SvelteKit and uses a modified version of the Carbon Component Library by IBM as well as Carbon's Icons and D3 Wrapper. Chroma also has a IDE for configuring pipelines with JSON and launching them on your coprocessor. That means that if your OS corrupts (It should not if you make the OS unwritable!) you can instantly load your config instead of spending time tuning for ages.
