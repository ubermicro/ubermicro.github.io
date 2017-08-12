# Project Goals

* Make useful packages, tools, etc. for Go.

# Tools

* colors https://www.materialpalette.com/colors

* versioning
    - git-flow - https://danielkummer.github.io/git-flow-cheatsheet/
    - semver - http://semver.org/

* gRPC
    - preferred communication to and between tools
    - protobuf defined per project

* docker - for tools and services.
    - should prefer to FROM alpine

* Go
    - primary language
    - prefer standard library
    - configuration: https://github.com/spf13/viper
    - flags: https://github.com/spf13/pflag/
    - commands (*ctl): https://github.com/spf13/cobra
    - logging: https://github.com/sirupsen/logrus
    - gRPC: https://github.com/grpc/grpc-go
    - versioning: http://labix.org/gopkg.in
