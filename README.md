# go-adp-bridge
A Golang bridge adapter.

This kind of adapter act like a bridge between topics, subscribing in one or N topics, transforming data and publishing it into another topic(s). Optionally, it can call http clients to enrich the original data.

# requirements
    - [x] consume topics
    - [x] publish on topics
    - [x] call http clients
    - [ ] expose por 3000 to check health
    - [ ] use in data models:
        - [x] strings
        - [ ] int
        - [ ] bool
        - [ ] dates
        - [ ] floats
        - [x] slice
    - [ ] tests with coverage
