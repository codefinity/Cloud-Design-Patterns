# Cloud-Design-Patterns

**This is the repository of all my LinkedIn Post on Cloud Design Patterns**

You can follow me on: https://www.linkedin.com/in/nikhilpat/

## Table of Contents

[1. Backend For Frontends](#1-Backend-For-Frontends)


## 1. Backend For Frontends

Planning to use the same APIs for all your Front-ends? DON'T !!!!

At some point in time, all your interfaces will

1. Look different from each other.

2. Will make different calls to the Back-end.

3. Will change at their own speed.


If all your Front-ends depend on a common backend service, and you change one of the Frontend, the chances are that you might cause disruptions in the other front-ends.

Solution: Create a separate backend for each interface. It gives space for the frontend to evolve at their own pace.


Ref: https://docs.microsoft.com/en-us/azure/architecture/patterns/backends-for-frontends

<img src="/BackendForFrontEnd/CloudDesignPatterns-BFF.png" width="800">
