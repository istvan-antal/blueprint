# Requirments

AWS Command Line tools: http://aws.amazon.com/cli/

Git

# Setup

Blueprint works with environments, for this guide, we will create an environment called: dev

Log in to the AWS console.

Go to EC2 -> Network & Security -> Key Pairs

Create a key pair named dev, download it, and put it in the ~/.blueprint directory.

Create a personal access key.

Run:

```sh
aws configure --profile dev
```

Enter the credentials created in the earlier step.

Generate an SSH key pair, add the public key to your git hosting and put the private key(named id_rsa) into the ~/.blueprint directory.

# Examples

Nginx-PHP example https://github.com/istvan-antal/blueprint-example-nginx-php

Wordpress example https://github.com/istvan-antal/blueprint-example-wordpress

Weather application example https://github.com/istvan-antal/weather-watch