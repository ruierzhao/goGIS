# goGIS
Go library for GIS tools. 


# usage
## installation
```sh
go get -u https://github.com/ruierzhao/goGIS
```

## Importing
```go
import "github.com/ruierzhao/goGIS/shapefile"
```

## Example
```go
package main
import (
  "fmt"

  "github.com/ruierzhao/goGIS/shapefile"
)

func main(){
  var path string = "your-shapefile.shp"
  src = shp.Open(path)
  fmt.Println(src)
}
```
