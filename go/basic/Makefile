# go flags
GO_FLAGS := GOOS=linux CGO_ENALBLED=0
.PHONY: build
build:
	$(GO_FLAGS) go build -o demo main.go

.PHONY: zip
zip:
	zip demo.zip demo
