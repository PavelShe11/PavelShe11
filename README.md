```go
package main

import "strings"

var sheludyakov = Developer{
    About: About{
        Name:     "Pavel Sheludyakov",
        Role:     "Backend Developer",
        Status:   "Open to work",
        Studying: "CS at university (part-time, 3rd year)",
        Focus:    "Go · Microservices · Distributed Systems",
    },
    Bio: strings.Join([]string{
        "Worked as Android Developer @ Areal (2y7m) and Tensor.",
        "Now transitioning to Go backend.",
        "Interested in Highload, SRE, Linux, k8s.",
    }, " "),
    Backend:  []string{"Go", "gRPC", "REST", "Echo", "JWT", "Microservices", "Clean Architecture", "DDD"},
    Database: []string{"PostgreSQL", "SQLite"},
    DevOps:   []string{"Docker", "Git", "Linux"},
    Mobile:   []string{"Kotlin", "Java", "Android", "Coroutines", "Flow", "Retrofit2", "Dagger2", "Room"},
    Links: Links{
        Telegram: "t.me/PavelShe11",
    },
}
```
