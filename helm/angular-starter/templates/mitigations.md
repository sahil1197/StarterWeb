CVE2023-24538 : Docker image is using Go 1.18.2, which contains a critical vulnerability in the html/template package. This vulnerability is fixed in Go 1.19.8 and 1.20.3.
Since this is part of the Go standard library, there isn’t a patch we can apply manually. we need to update the Go version in your image.
