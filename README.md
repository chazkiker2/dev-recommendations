# Developer Resources for Beginners <!-- omit in toc -->

> This repository contains resources for developers who are interested in the world of coding. It contains Chaz Kiker's personal recommendations and opinions.
>
> This overview is full of opinions. Along with every other developer, these opinions have been formed based on my personal experience at the time of writing. And opinions change! None of the content within this repository is an innate fact.

## Table of Contents <!-- omit in toc -->

- [Notes of Preface](#notes-of-preface)
  - [The language/framework war](#the-languageframework-war)
- [How to enter the vast world of coding](#how-to-enter-the-vast-world-of-coding)
  - [Web Development](#web-development)
- [My Primary Languages](#my-primary-languages)
  - [In Order of "Difficulty" (Easiest to Hardest)](#in-order-of-difficulty-easiest-to-hardest)
  - [In Order of My Preference (Favorite to Least)](#in-order-of-my-preference-favorite-to-least)
  - [In Order of Popularity (Most to Least as of 2023... as far as I know)](#in-order-of-popularity-most-to-least-as-of-2023-as-far-as-i-know)
- [My Preferred IDEs](#my-preferred-ides)
- [Popular Frameworks](#popular-frameworks)
  - [JavaScript/TypeScript](#javascripttypescript)
    - [Front End](#front-end)
    - [Back End](#back-end)
  - [Python](#python)
    - [Front End](#front-end-1)
    - [Back End](#back-end-1)
  - [Java](#java)
    - [Front End](#front-end-2)
    - [Back End](#back-end-2)
  - [C#](#c)
    - [Front End](#front-end-3)
    - [Back End](#back-end-3)
  - [Rust](#rust)
    - [Front End](#front-end-4)
    - [Back End](#back-end-4)

## Notes of Preface

### The language/framework war

Once upon a time, before I truly understood the world of programming, I subscribed to the idea that some languages and frameworks were definitively better than others.

The truth is that every language have their use cases. Some intend to do A/B/C well while others aim to do X/Y/Z well. Some of them do what they aim to do, others do more, some don't hit the mark!

The more you learn about code, you'll find yourself building opinions; the longer you code, you'll find those opinions shifting and changing.

## How to enter the vast world of coding

There's a lot of areas of programming. I have spent most of my programming career in the world of Web Development—building websites across the whole stack (frontend, backend, database, etc.).

In this section, I'll point out the primary areas within web development. I'd recommend starting with one and building to the others. I will also describe the learning path that I took (which worked out quite well for me, truthfully).


### Web Development

Here are the primary categories that you'll see when people talk about web development:

- Frontend web development
  - There are truthfully two different sides of frontend work: (1) Design and (2) functionality.
  - Frontend developers are responsible for the look, feel, and interactivity of websites as non-programmers know about websites. When you click a button, does it do something? A frontend (functionality) dev wrote the code that made that button *do the thing*. When you resize your browser, does the picture adjust? A frontend (design) dev made it look that way!
- Backend web development
  - Backend devs are responsible for creating the more data-oriented side of websites. When you purchase a new tee shirt... does your card get charged? When you follow someone on instagram... do they show up in your "followed" section when you return to the app? When you make an Amazon purchase... does the item show up in your past orders? All of this is driven by data, and a lot of complex code that gives meaning to that data. A backend dev made that happen.
- Fullstack web development
  - This is simply where a developer covers both frontend and backend. It takes on a lot of different "versions". For instance, I am a fullstack developer with a backend-heavy lean. I primarily work in the backend, but I do a lot of *functional* frontend work. I am very rarely responsible for making some site look pretty... the frontend work I do is more about interacting with the backend API and shaping that data into something meaningful for the end user. (I avoid CSS and design as much as humanly possible, simply because I prefer functionality coding over design!)


## My Primary Languages

### In Order of "Difficulty" (Easiest to Hardest)

*The following list is in order of “difficulty” as far as learning the language from Square 1 is concerned*

1. Python
2. JavaScript/TypeScript
3. C#
4. Java
5. Rust

### In Order of My Preference (Favorite to Least)

*The following list is purely opinionated. The order of preference has changed over the years, and there's a lot of aspects that go into these opinions*

1. Rust
2. C#
3. Java
4. JavaScript/TypeScript
5. Python

### In Order of Popularity (Most to Least as of 2023... as far as I know)

1. JavaScript/TypeScript
2. Python
3. Rust
4. Java
5. C#

## My Preferred IDEs

*Note: some folks use VS Code for absolutely everything.*
*I personally like the more tooled-up IDEs, so I change what IDE I’m using based on the language/framework*

- JavaScript/TypeScript — VS Code
- Python — JetBrains PyCharm (Professional)
- Java — JetBrains IntelliJ (Professional)
- C# —JetBrains Rider (Professional)
- Rust — VS Code
  - JetBrains CLion is also good for Rust... but most of the Rust community uses VS Code.

## Popular Frameworks

*Frameworks are an additional layer on top of programming languages. They have become a core part of development for most areas of programming.*

*While a language provides the syntax and rules to build an application, they usually don’t include any out-of-the-box native functionality that lets you DO something with it.*

*Frameworks give developers some pre-configured tools that allow you to actually DO the thing you want to do with the code.*

*Any options that are **bolded** are what I’d recommend for starting out with for that particular language/application-type*

### JavaScript/TypeScript

#### Front End

- **React**
- **VueJS**
- Svelte
- Angular — I’d recommend not using Angular to start with

#### Back End

- **Node.js**
- Next
- Express
- Gatsby

### Python

#### Front End

- **Django**

#### Back End

- **Django**
- FastAPI
- Flask

### Java

#### Front End

*Most folks do not build frontend web apps in Java. I’d encourage beginners to follow that same trend.*

#### Back End

- **Java Spring**

### C#

*Most folks do not build frontend web apps in C#. I’d encourage beginners to follow that same trend. That said, Blazor is my personal favorite frontend web framework… but if you’re just starting out with programming it’s better to go the JS/TS route*

#### Front End

- **Blazor**

#### Back End

- **ASP.NET**

### Rust

*Most folks do not build frontend web apps in Rust. I’d encourage beginners to follow that same trend.*

*Rust is growing on frontend usage, but most people stick to backend and lower-level stuff with Rust. You can hook up pretty much any JS/TS framework to a Rust backend.*

#### Front End

- Yew

#### Back End

- **Rocket**
  - There are other frameworks, but Rocket is hands-down the biggest Rust backend framework — I’d recommend starting with that and if you want some other recommendations hit me up
