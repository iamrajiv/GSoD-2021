<div align="center">
<img src="assets/gsod-2021-1.svg" height="auto" width="400" />
<br />
<img src="assets/gsod-2021-2.svg" height="auto" width="400" />
<br />
<h1>Wechaty</h1>
<h3>
Improve the gRPC and OpenAPI ecosystem
<br />
Project Proposal
</h3>
</div>

## About me

I considered myself a Polymath. I believe in rigorous and intuitive learning. Spend the majority of the time exploring different types of algorithms and contributing to open source. My interest lies in the fields of Algorithms, Computational Science, and Distributed Computing.

I have completed Google Season of Docs 2020 with [gRPC-Gateway](https://grpc-ecosystem.github.io/grpc-gateway/), and my project was on **Refactoring the Existing Docs Site of gRPC-Gateway** of gRPC-Gateway.

My Google Season of Docs 2020 work summary can be found in this repository [https://github.com/iamrajiv/GSoD-2020](https://github.com/iamrajiv/GSoD-2020).

## Introduction

This is the project proposal for **Improve the gRPC and OpenAPI ecosystem** on which I will be working as a part of Google Season of Docs 2021. I have proposed my timeline to complete this work during a span of **9 weeks**.

The user docs site is designed to assist end-users in using a product or service. The excellent user docs site is significant because it provides an avenue for users to learn how to use the software, its features, tips, tricks, and resolve common problems encountered when using the software. It also reduces support costs and is part of the corporate identity of the product. The excellent user docs site is a sign of the healthiness of the product, the developer team. Without a good user docs site, a user may not know how to do the above things effectively and efficiently. User docs site can play a pivotal role in ensuring a product's success because excellent communication is and will always be at the heart of any business or development. Fantastic documentation takes that communication and puts it in a manageable framework that everyone can access for success.

Wechaty has two subsystems for providing the gRPC support: one is [wechaty/wechaty-grpc](https://github.com/wechaty/grpc) and the other is [wechaty/openapi](https://github.com/wechaty/openapi). The related docs page is mainly at [Polyglot/OpenAPI](http://wechaty.js.org/docs/polyglot/openapi/) as well as other pages that have some OpenAPI associated docs.

However, the Wechaty user documentation for gRPC and OpenAPI is currently outdated and incomplete. Therefore, there should be an improvement in both code and documentation.

## Project Goals

- Improving [Polyglot/OpenAPI](http://wechaty.js.org/docs/polyglot/openapi/) documentation in [Wechaty docs website](https://wechaty.js.org/docs/):

  - Improving Wechaty OpenAPI docs.
  - Adding a blog about both gRPC and OpenAPI.
  - Updating the History section and fetching all contents of the `CHANGELOG.md` file from [wechaty/openapi](https://github.com/wechaty/openapi) repository using a script.
  - Adding learning resources section.

- Improving repository documentation for both [wechaty/wechaty-grpc](https://github.com/wechaty/grpc) and [wechaty/openapi](https://github.com/wechaty/openapi):

  - Generating and adding `CHANGELOG.md` file for both [wechaty/wechaty-grpc](https://github.com/wechaty/grpc) and [wechaty/openapi](https://github.com/wechaty/openapi) repository.
  - Removing the `HISTORY` section part from README for both [wechaty/wechaty-grpc](https://github.com/wechaty/grpc) and [wechaty/openapi](https://github.com/wechaty/openapi) repository.
  - Adding issue and pull request templates for [wechaty/wechaty-grpc](https://github.com/wechaty/grpc) and [wechaty/openapi](https://github.com/wechaty/openapi) repositories.
  - Adding `CONTRIBUTING.md` file for both [wechaty/wechaty-grpc](https://github.com/wechaty/grpc) and [wechaty/openapi](https://github.com/wechaty/openapi) repository.
  - Improving contributing guidelines of [wechaty.js.org](https://wechaty.js.org/).
  - Adding and organizing learning resources section about third parties library and frameworks like gRPC, gRPC-Gateway, and Protocol Buffers, etc in both [wechaty/wechaty-grpc](https://github.com/wechaty/grpc) and [wechaty/openapi](https://github.com/wechaty/openapi) repository.
  - Creating logo for [wechaty/wechaty-grpc](https://github.com/wechaty/grpc) repository.
  - Refactoring and breaking the READMEs for both [wechaty/wechaty-grpc](https://github.com/wechaty/grpc) and [wechaty/openapi](https://github.com/wechaty/openapi) repository into sub-section like Usage, Installation, Contributing, and Resources, etc.

- Miscellaneous:

  - Adding Open Graph image metadata in the Docusaurus site of [wechaty.js.org](https://wechaty.js.org/).
  - Adding Progressive Web Application support for the Docusaurus site and Jekyll blog.
  - Adding Swagger UI to Express Route by default in [wechaty/openapi](https://github.com/wechaty/openapi) repository.
  - Format files that are necessary using [Prettier](https://prettier.io) for both [wechaty/wechaty-grpc](https://github.com/wechaty/grpc) and [wechaty/openapi](https://github.com/wechaty/openapi) repository.
  - Checking and fixing indentations, grammatical errors, typographical errors, and broken links across all the files, including previous and new documentations.
