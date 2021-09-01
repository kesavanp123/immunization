## Immunization sample starter project for open-saber rc
``
Deploy app
``

```
kubectl -n <NAMESPACE> create secret generic  schema-config --from-file=Hospital.json --from-file=Address.json --from-file=Child.json --from-file=Practitioner.json --from-file=Common.json --from-file=VaccineMaster.json

kubectl -n <NAMESPACE> apply -f registry-deployment.yaml

kubectl -n <NAMESPACE> apply -f claim-ms-deployment.yaml

```
