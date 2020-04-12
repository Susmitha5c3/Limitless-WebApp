# High Availability WebApp using Cloud Formation

### This repo contains the entire code to deploy a web app in the cloud.

>Prerequsites:
* Upload webApp in the S3 bucket.
>Stacks
* Network Stacks
```bash
./create <stack-name> infrastructure.yml infra_params.json
```
* Server Stack
```bash
./create <stack-name> servers.yml server-params.json
```

>Outputs
* URL of Load Balancer:[	http://udaci-WebAp-1K0H79C6RZUI8-34614496.us-west-2.elb.amazonaws.com](	http://udaci-WebAp-1K0H79C6RZUI8-34614496.us-west-2.elb.amazonaws.com)