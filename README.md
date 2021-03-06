[![Build Status](https://travis-ci.org/mhmoudgmal/pdcli.svg?branch=master)](https://travis-ci.org/mhmoudgmal/pdcli)
[![Go Report Card](https://goreportcard.com/badge/github.com/mhmoudgmal/pdcli)](https://goreportcard.com/report/github.com/mhmoudgmal/pdcli)
[![Generic badge](https://img.shields.io/badge/editor-vim-yellowgreen.svg)](https://github.com/mhmoudgmal//pdcli)

PagerDuty CLI **(Under development)**

> A command line interface for Pagerduty. Interact with incidents with commands (e.g. C-k, C-r) while naviagting them via (j, k).

## Development
- clone the project `git clone git@github.com:mhmoudgmal/pdcli`
- install go dep tool `go get -u github.com/golang/dep/cmd/dep`
- run `dep ensure`

## Tests
This project uses ginkgo BDD framework https://github.com/onsi/ginkgo

- run `go test ./...`
- or install ginkgo and run `ginkgo -r --randomizeAllSpecs --randomizeSuites  --race --trace`

## Run the app
- `go build`
- `./pdcli -email=your_email@registerd.pd -token=pd_token`
