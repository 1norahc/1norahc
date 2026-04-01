```go
type rajan_bor struct {
    Role        Role
    GitHub      GitHub
    Website     Website
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
        Website:    Website{"rajanbor.com"},
        Company:    Company{"boringcode.com"},
        Philosophy: "boring code > clever code",
        Interests:  []string{"hobbyist ai researcher"},
        TechStack:  []Technology{
            "Python", "TypeScript", "JavaScript", "Rust",
        },
        Learning:    "Go, more Rust"
    }
}
```
