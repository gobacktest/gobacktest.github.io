---
id: 2104280919
title: "status of the project"
---

# Status of the gobacktest project

as of version [v0.3.0][docs-v3]

## What I like

- modularity in mind
- event flow

## What I don't like

- Interface and exported API pollution
- unclear/crowded project structure
- basics of modularity but not consequential enough
- messed or mixed responsibility of modules, e.g. the Portfolio connects and controls the Orderbook
- lack of documentation

## Goals

- restructure the project into subpackages
- introduce a Domain Driven Design (DDD) approach to the project
- introduce a fully event based system - Event Sourcing

[docs-v3](https://pkg.go.dev/github.com/dirkolbrich/gobacktest@v0.3.0)
