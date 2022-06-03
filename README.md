# oas2envoy
Generates matcher configuration for routing in oas2envoy

## Get started
```bash
npm i
./oas2envoy -o petstore.yaml
```

Then take the output of that command and use it update your envoy route config

** NOTE ** you'll still need to add the appropriate routes.

## To do
We should either rely on the default path and dynamically create a cluster and add the route or optionally support an OAS-extension (to be named) to grab that and use it for the targets
