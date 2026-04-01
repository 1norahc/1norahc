# Rajan Bor (1norahc)

```go
type rajan_bor struct {
    Role        Role
    GitHub      GitHub
    Email       Email
    Website     Website
    X           X
    Company     Company
    Philosophy  string
    Interests   []string
    TechStack   []Technology
    Learning    string
}

func (r *rajan_bor) New() *rajan_bor {
    return &rajan_bor{
        Role:       Role.FULL_STACK_DEVELOPER_AND_FOUNDER,
        GitHub:     GitHub{"github.com/1norahc"},
        Email:      Email{"rajanbor@rajanbor.com"},
        Website:    Website{"rajanbor.com"},
        X:          X{"x.com/rajanbor"},
        Company:    Company{"boringcode.com"},
        Philosophy: "boring code > clever code",
        Interests:  []string{"hobbyist ai researcher"},
        TechStack:  []Technology{
            "Python", "TypeScript", "JavaScript", "Rust",
        },
        Learning: "Go, more Rust",
    }
}
```
