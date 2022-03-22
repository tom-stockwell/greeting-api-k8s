# Greeting API K8s
Contains the kubernetes resources required by the [Greeting API](https://github.com/tom-stockwell/greeting-api).
[Kustomize](https://kustomize.io) is used to configure the application for different environments.

## Layout
- `base`: contains the base kustomize configuration
- `overlays/<env>`: contains environment specific kustomize overlays

The overlay directories should be used in order to deploy the application to the appropriate 
