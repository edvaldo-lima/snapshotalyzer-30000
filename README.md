# snapshotalyzer-30000
Demo project to manage AWS EC2 instance snapshots.

## About

this project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty uses the configuration file created by the AWS cli. e.g.

`aws configure --profile shotty`

#Running

`pipenv run python shott/shotty.py <command>
<--project=PROJECT>`

*command* is list, start, or stop
*project* is optional