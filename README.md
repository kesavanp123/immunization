## Immunization sample starter project for open-saber rc


```
kubectl -n divoc create secret generic  schema-config --from-file=Hospital.json --from-file=Address.json --from-file=Child.json --from-file=Practitioner.json --from-file=Common.json --from-file=VaccineMaster.json

kubectl apply -f immunization-deployment.yaml

```
