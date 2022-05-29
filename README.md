# Cloud-Design-Patterns

## Backend For Frontends

Deciding to use the same APIs for all your Frontends? DONT !!!!

At some point in time all your interfaces will

1. Look different from each other.
2. Will make different cals to the Backend.
3. Will change at their own speed.

If all your Frontends depend on a common backend service, and you make a change to one of the Frontend, the chances are that you mignt cause disruptions in the other fromtends.

Solution: Create a separate backend for each interface. It gives space for the frontends to evolve at their own pace.

Ref: https://docs.microsoft.com/en-us/azure/architecture/patterns/backends-for-frontends
