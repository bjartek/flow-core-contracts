.PHONY: test
test:
	go test ./...

.PHONY: check-tidy
check-tidy:
	go mod tidy
	git diff --exit-code

.PHONY: ci
ci: check-tidy test
