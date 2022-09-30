# Go


## IDEA 识别不了 GO 版本
1. 进入go sdk的`src/runtime/internal/sys`目录

2. 编辑 `zversion.go` 文件
    ```go
    // Code generated by go tool dist; DO NOT EDIT.
    package sys
     
    const StackGuardMultiplierDefault = 1
    const TheVersion = `go1.17`
    ```



go test -v lkqueue.go lkqueue_test.go