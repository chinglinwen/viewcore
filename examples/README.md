# Example usage

```
go build -o bin/viewcore cmd/viewcore/*.go
```

```
bin/viewcore $corefile --exe $binfile objgraph output.dot
dot -Tsvg output.dot >output.svg

# or png
dot -Tpng output.dot >output.png
```


