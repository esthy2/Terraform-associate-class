# Create Terraform Infrastructure with Docker

1. In the "Code Editor" tab, open the main.tf file.

Copy and paste the following configuration. Save your changes by clicking on the icon next to the filename above the editor window.

## Test the code : 

- In the "Terminal" tab, initialize the project, __which downloads a plugin that allows Terraform to interact with Docker.__
```
terraform init
```

2. Provision the NGINX server container with apply. When Terraform asks you to confirm, type yes and press ENTER.

```
terraform apply
```

3. Verify NGINX instance
Run docker ps to view the NGINX container running in Docker via Terraform.

```
docker ps
```

4. Destroy resources
To stop the container and destroy the resources created in this tutorial, run terraform destroy. When Terraform asks you to confirm, type yes and press ENTER.

```
terraform destroy
```

5. conclusion
You have now provisioned and destroyed an NGINX webserver with Terraform.

