SHELL := /bin/bash

all:
	$(MAKE) build-input

.PHONY: build-input
build-input:
	@-mkdir build
	go build -buildmode=plugin -o build/es-input.so input/input.go

