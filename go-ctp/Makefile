build:
	go install -v -x -buildmode=shared runtime sync/atomic #构建核心基本库
	go install -v -x -buildmode=shared -linkshared #构建GO动态库

example:
	go build -v -x -linkshared _example/goctp_md_example.go
	go build -v -x -linkshared _example/goctp_trader_example.go
