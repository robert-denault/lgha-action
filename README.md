# lgha-action
Custom action to print a Hello World and Date 

# Environment Variables
- None

# Arguments
- None

# Examples
Here's an example workflow that uses the the action.  

```
name: Hello world - RJD

on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v1
    - uses: robert-denault/lgha-action@master
```

