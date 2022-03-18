# beam-go
## Go to your Documents/44-517 folder. We want to create a new project folder under 44-517. 
## Make new directory beam-go (no spaces - for the easiest life, never leave spaces in folder/file names!)
## Change directory into beam-go. This will be our root project folder for the quick start.
## In your folder, run go mod init github.com/NVGSSAI/beam-go (use your github profile name)
## Use code . to open VS Code here.
## Create the sample hello.go file in your new modules. Customize it. We'll be able to import your hello app from GitHub.
## When done, use go run . to execute the default file in the folder. 
## 
## Install GoLang and check for the Version
`go version`

## Get the SDK and the examples
`go get -u github.com/apache/beam/sdks/v2/go/pkg/beam`

## Run wordcount (the below command didn't work for me)
`go install github.com/apache/beam/sdks/v2/go/examples/wordcount`

##  So, I used the following command to run
 `go run wordcount.go --input sample.txt --output nallapati_count.txt`

 ## After running the above command, it asked me to get the following
 `go get github.com/apache/beam/sdks/v2/go/pkg/beam/runners/dataflow/dataflowlib@v2.37.0`
 ` go get github.com/apache/beam/sdks/v2/go/pkg/beam/io/filesystem/gcs@v2.37.0`

 ##  Now, Run the Word Count
 `go run wordcount.go --input sample.txt --output nallapati_count.txt`