# beam-go
### Steps to execute

- Set up your environment , The Beam SDK for Go requires go version 1.16 or newer , download and install Go .
- Check that you have version 1.16 by running: $ go version

### Get the SDK and the examples
- $ go get -u github.com/apache/beam/sdks/v2/go/pkg/beam

Add sample.txt file
add wordcount.go file
### Run wordcount
- $ go install github.com/apache/beam/sdks/v2/go/examples/wordcount
- $ wordcount --input sample.txt --output enugala_count.txt

links to follow  : https://beam.apache.org/get-started/quickstart-go/
