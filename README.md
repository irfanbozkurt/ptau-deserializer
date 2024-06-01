Deserializes a .ptau file into a Gnark Phase1 object for bn254. This enables one to use existing phase1 ceremonies in Gnark, although they were conducted using SnarkJS. 

```bash
go run main.go convert --input <CEREMONY>.ptau --output <CEREMONY>.ph1
```
