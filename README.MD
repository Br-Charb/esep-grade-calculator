# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```

For future developers:

The purpose of each file in this repo is:

a.	README.MD: Documentation of the project and basic information about it (description, languages, commands).
b.	go.mod: This defines the Go module and version of Go necessary.
c.	grade_calculator.go: This contains the actual code for the functioning application, like the code enabling adding grades, calculating the weighted average, and producing a letter grade.
d.	grade_calculator_test.go: Contains 3 test cases that should return a grade of A,B, or F respectively.

For testing, as mentioned above for grade_calculator_test.go, the tests simulate what should be either a A, B, or F grade by creating a grade calculator and adding assignment, essay, and exam grades that should total to each. The process to execute tests is:
```
cd grade_calculator/
go test ./...
```