---
layout: default
---

## A end-to-end, functional-first stack for cloud-ready web development that emphasises type safe programming.

### What is SAFE?
SAFE is a technology stack that brings together several technologies into a single, coherent stack for typesafe, flexible end-to-end web-enabled applications that are written entirely in F#.

The default stack consists of the following core components

![](images/stack.png)

#### Suave IO
> Suave is a lightweight, non-blocking web server. The non-blocking I/O model is efficient and suitable for building fast, scalable network applications. In fact, Suave is written in a completely non-blocking fashion throughout. Suave runs on Linux, OS X and Windows flawlessly.

#### Azure
> Microsoft Azure is a growing collection of integrated cloud services that developers and IT professionals use to build, deploy, and manage applications through our global network of datacenters. With Azure, you get the freedom to build and deploy wherever you want, using the tools, applications, and frameworks of your choice.

#### Fable
> Fable brings all the power of F# to the JavaScript ecosystem. Enjoy advanced language features like static typing with type inference, exhaustive pattern matching, immutability by default, structural equality or units of measure, and let the compiler catch the bugs for you before they ever get into runtime.

#### Elmish
> Elmish implements core abstractions that can be used to build Fable applications following the “model view update” style of architecture, as made famous by Elm.

### Why SAFE?
The SAFE stack provides developers who are already enjoying the benefits with functional programming, and in particular F#, with a flexible stack that provides complete end-to-end solutions for your web-enabled applications using popular and widely-used technologies.

For those developers who are not familiar with functional programming, or are .NET developers who have not taken the leap to F#, SAFE provides a coherent stack that will get you up and running as quickly as possible whilst leaving you safe in the knowledge that there's a community out there that can support you whilst you upskill.

### A flexible stack to suit your needs
Whilst the SAFE stacks recommends a number of specific technologies for you to use, it does not lock you in to any of them.

#### A Pluggable Stack

Here's an example system architecture that could make use of the SAFE stack.

![](images/safe-architecture-1.png)

* Hosting Platform - provides the hosting environment for all services and data.
* Storage - some standard data storage mechanism
* Other services - includes messaging, logging or any other PAAS offered by the hosting platform.
* Server-side web - the application servicing HTTP requests, favouring a functional-first approach.
* Client-side web - application logic written in F# but cross-compiled into Javascript.
* UI rendering - the application framework that handles UI interaction.

A typical SAFE implementation *might* look like this. However, as you can see, there are multiple alternatives that can be employed 

| | SAFE | Alternative |
|-|-|-|
| Hosting Platform | Microsoft Azure | AWS, GCP |
| Storage | SQL Azure, Azure Storage, Document DB | Dynamo DB etc. |
| Other Services | Service Bus, App Insights, Event Hub | SQS etc. |
| Server-side | Suave | Giraffe, WebSharper, Freya |
| Client-side | Fable | WebSharper |
| UI Rendering | Elmish | HTML + JQuery, AngularJS etc. |

#### Mix with your existing stack
Since SAFE doesn't force you to write your entire stack with it, you can easily work with an existing stack and port parts of your application as needed. Working with an external team that manage your client-side code? No problem - just use Suave and Azure for your back-end services. Already using ASP .NET Web API for your service side components? No worries - because Fable boils down to high quality Javascript, it works just fine with that, too!

### How do I get started?

### Who can I turn to for guidance?