# TODO
- add init option for [backend config](https://developer.hashicorp.com/terraform/language/settings/backends/configuration#partial-configuration)
- add ability to skip init, fmt and validation steps (make them skippable)
- add ability to run apply not based on prepared plan, but on-the-fly
- add ability to configure workspace in run. Maybe withing split alias onto project and env - `./tc run runner_STG destroy -var-file=nonprod.tfvars -target=module.privileged_gitlab_runner_cluster`
- handle AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY env vars within the AWS_PROFILE
