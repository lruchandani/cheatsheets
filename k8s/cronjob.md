## update a cronjob schedule
```
# - make a job run every midnight
kubectl patch cronjob <job name> -p '{"spec":{"schedule": "00 00 * * *"}}' -n <namespace>
```