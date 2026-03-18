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
        "Started programming at 12 with robotics.",
        "Worked as Android Developer @ Areal (2y7m) and Tensor.",
        "Now transitioning to Go backend.",
        "Interested in Highload, SRE, Linux, k8s.",
    }, " "),
    Backend:  []string{"Go", "gRPC", "REST", "Echo", "JWT", "Microservices", "Clean Architecture", "DDD"},
    Database: []string{"PostgreSQL", "SQLite", "Room"},
    DevOps:   []string{"Docker", "Git", "Linux"},
    Mobile:   []string{"Kotlin", "Java", "Android", "Coroutines", "Flow", "Retrofit2", "Dagger2"},
    Links: Links{
        Telegram: "t.me/PavelSheludyakov",
    },
}
```
