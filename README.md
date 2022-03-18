
# beam-go
## Go version
go version
## SDK
go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
## wordcount installation
go install github.com/apache/beam/sdks/v2/go/examples/wordcount
## run word count
go run wordcount.go --input input.txt --output Thota.txt
## create packages
go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0
## run word count
go run wordcount.go --input input.txt --output Thota.txt
