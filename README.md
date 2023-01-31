# Helm-Chart

a helm chart using production, development and QA kubernetes manifest

to run it
```xml
helm template create dev
```
to  test
```
helm template dev -f ./dev/values-dev.yaml
helm template dev -f ./dev/values-qa.yaml
helm template dev -f ./dev/values-prod.yaml
```