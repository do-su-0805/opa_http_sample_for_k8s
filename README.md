# what is this?

- [opa sample for HTTP AUTH](https://www.openpolicyagent.org/docs/http-api-authorization.html) for k8s

# for use

1. make deployment

- `kubectl apply -f deployment/opa-deployment.yaml`
- `kubectl apply -f deployment/frontend-deployment.yaml`

2. make service

- `kubectl apply -f service/frontend-service.yaml`
- `kubectl apply -f service/opa-service.yaml`

3. Load a policy into OPA.

- please read head sample.
