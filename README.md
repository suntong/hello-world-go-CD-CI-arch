# Lab :: Hello World :: Go Application

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
hello Odaceo
```

## Reporting Issues

Issues can be reported at [https://github.com/odaceo/lab-hello-world-go/issues](https://github.com/odaceo/lab-hello-world-go/issues)

## Source code

The source code is available at [https://github.com/odaceo/lab-hello-world-go](https://github.com/odaceo/lab-hello-world-go)

## License

All the source code is distributed under [ASL 2.0](LICENSE).

## Copyright

© 2017 [Odaceo](http://odaceo.ch). All rights reserved.



