# ESEP Grade Calculator

This library is a simple utility to calculate your grades. Input your average grades for your exams, assignments, and essays. Assignments are weighted at 50% of the overall course grade, exams are worth 35%, and essays are worth 15%.

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