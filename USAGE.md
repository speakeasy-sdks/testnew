<!-- Start SDK Example Usage -->


```go
package main

import(
	"context"
	"log"
	"github.com/speakeasy-sdks/testnew"
	"github.com/speakeasy-sdks/testnew/pkg/models/shared"
)

func main() {
    s := acmetestgo.New()

    ctx := context.Background()
    res, err := s.CreateUserv1(ctx, shared.UserInput{
        Country: "Malta",
        Email: "Micheal_Sporer@yahoo.com",
        Firstname: "Karley",
        Lastname: "Stamm",
        Nickname: "vel",
        Password: "error",
    })
    if err != nil {
        log.Fatal(err)
    }

    if res.User != nil {
        // handle response
    }
}
```
<!-- End SDK Example Usage -->