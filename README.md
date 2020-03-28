## j-evm 执行
#### https://docs.google.com/document/d/1u2kuRWxJ7RL8o4Ir9CBQKfjc3pn9IDQqneE_ht_q_T0/edit#
#### 编译运行
执行以下的几步操作即可：
Copy至gopath目录
```
/Users/junsong/mywork/golang/src/evm  
```
执行代码：
```
go run *.go
```   
或者编译执行  
```
go build .
```  
```
./demo
```
#### 运行结果
```  
Execute OP:  PUSH1
Execute OP:  PUSH1
Execute OP:  MSTORE
Execute OP:  PUSH1
Execute OP:  DUP1
Execute OP:  PUSH1
Execute OP:  PUSH1
Execute OP:  CODECOPY
Execute OP:  PUSH1
Execute OP:  RETURN
[96 96 96 64 82 96 8 86 91 0]
```