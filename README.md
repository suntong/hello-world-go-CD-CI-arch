# Lab :: Hello World :: Go Application
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

[![License](https://img.shields.io/github/license/odaceo/lab-hello-world-go.svg)](LICENSE)
[![Build Status](https://travis-ci.org/odaceo/lab-hello-world-go.svg)](https://travis-ci.org/odaceo/lab-hello-world-go)

## Description

A simple Go application on Linux.

## Prerequisites

[Vagrant](https://www.vagrantup.com/downloads.html) must be installed on your 
computer to mount the workbench for this project.

Open a Terminal and run the following commands:

```shell
vagrant up
vagrant ssh
cd /vagrant
```

## Compiling the application

The compile command makes a standalone binary file.

``` shell
go build -o bin/hello
```

If you need need to build a binary file for another target operating system 
and architecture use the following command:

``` shell
env GOOS=darwin GOARCH=amd64 go build -o bin/hello
```

See [the valid combinations of operating system and compilation architecture](https://golang.org/doc/install/source#environment).

Cross compilation was never be so easy!

## Running the application

To launch the application use the following command:

``` shell
./bin/hello Odaceo
```

## Reporting Issues

Issues can be reported at [https://github.com/odaceo/lab-hello-world-go/issues](https://github.com/odaceo/lab-hello-world-go/issues)

## Source code

The source code is available at [https://github.com/odaceo/lab-hello-world-go](https://github.com/odaceo/lab-hello-world-go)

## License

All the source code is distributed under [ASL 2.0](LICENSE).

## Copyright

© 2017 [Odaceo](http://odaceo.ch). All rights reserved.




## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/suntong"><img src="https://avatars.githubusercontent.com/u/422244?v=4?s=100" width="100px;" alt=""/><br /><sub><b>suntong</b></sub></a><br /><a href="https://github.com/suntong/hello-world-go-CD-CI-arch/commits?author=suntong" title="Code">💻</a> <a href="#ideas-suntong" title="Ideas, Planning, & Feedback">🤔</a> <a href="#design-suntong" title="Design">🎨</a> <a href="https://github.com/suntong/hello-world-go-CD-CI-arch/commits?author=suntong" title="Documentation">📖</a> <a href="https://github.com/suntong/hello-world-go-CD-CI-arch/commits?author=suntong" title="Tests">⚠️</a> <a href="#example-suntong" title="Examples">💡</a> <a href="#maintenance-suntong" title="Maintenance">🚧</a> <a href="#projectManagement-suntong" title="Project Management">📆</a> <a href="#question-suntong" title="Answering Questions">💬</a> <a href="#tool-suntong" title="Tools">🔧</a> <a href="#tutorial-suntong" title="Tutorials">✅</a> <a href="#infra-suntong" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!