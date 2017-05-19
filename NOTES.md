# Project Goals

* Make small microservices that can be used:
    - in a docker container
    - in kubernetes
    - package can be embedded 

# Tools

* colors https://www.materialpalette.com/colors

* versioning
    - git-flow - https://danielkummer.github.io/git-flow-cheatsheet/
    - semver - http://semver.org/

* gRPC
    - preferred communication to and between microservices
    - protobuf defined per project

* docker
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
