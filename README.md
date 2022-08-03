
# go snippets

Golang snippets 


## Usage

keywords



**Enjoy!**
Keywords for easy working
```
        


.int =>  .(int)


start =>  package main
          
          import "fmt"
          
          func main() {
              $0
          }


pl =>  fmt.Println($0)


for =>  for i := 0; i < $1; i++ {
            $0
        }


empty-for =>  for $1 {
                  $0
              }


r =>  return $0


d =>  $1 := $0


t =>  true


f =>  false


notnil =>  != nil


isnil =>  == nil


im =>  import "$0"


imfmt =>  import "fmt"

```