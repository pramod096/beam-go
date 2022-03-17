# go-beam - Pramod Reddy Gonegari

## Instructions to get the word count

**1.** Download and Install go from [Go](https://go.dev/learn/)

**2.** Verify go is installed successfully:
```
go version
```
**3.** Get the SDK:
 ```
 go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
 ```
    
**4.** Install the wordcount example:
```
go install github.com/apache/beam/sdks/v2/go/examples/wordcount
```
    
**5.** Create a wordcount.go file and add the code from [wordcount example](https://github.com/apache/beam/tree/master/sdks/go/examples/wordcount)

**6.** Run the wordcount:
```
    go run wordcount.go --input <input file> --output <output file>
```
    
**7.** Incase of any errors, run this command and rerun Step 6:
```
go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0
```

