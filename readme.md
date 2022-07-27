# How do we run the code in our project?

- Terminal
- Command: go
    - go build -> compiles the code
    - go run <name_of_the_file> -> compiles and executes it
    - go fmt -> formats all the code in each file in the current directory
    - go install -> compiles and "installs" a package
    - go get -> downloads the raw source code of someone else's package
    - go test -> runs any tests associated with the current project

# What does 'package main' mean?

    - package: project or a workspace
    - main: inside of go there are 2 types of packages:
        - Executable -> Generates a file that we can run. The name "main" is reserved for Executable files.
        - Reusable -> Code used as 'helpers'. Good place to put reusable logic. The rest of the files names are for reusables.
            E.g.: package calculator, package uploader

# What does 'import "ftm" mean?

    - Give me to the package main to access the package "fmt" - Format.
    - fmt is a standard lib of GO. (golang.org/pkg)

# What's that 'func' thing?

    -  func is short as function

# How is the main.go file organized?

    - Always be the same pattern:
        - Package declaration
        - Import other packages that are need
        - Declare functions, tell, Go to do things