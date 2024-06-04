# AWS CLI commands


### -> aws cli command to get shell access of the ecs container
```
aws ecs execute-command \
--region us-east-1 \
--cluster dev-<product>-<service> \
--container dev-<product>-<service>-fargate-abc \
--task 3cf9384f99384f9e3ca63f14df \
--command "/bin/bash" \
--interactive
```
