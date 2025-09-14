1. Azure Location Codes. https://gist.github.com/ausfestivus/04e55c7d80229069bf3bc75870630ec8
2. Read about the Terraform configuration language in the Terraform documentation. https://developer.hashicorp.com/terraform/language
3. Learn more about Terraform providers. https://developer.hashicorp.com/terraform/language/providers
4. Review usage examples of the Terraform Azure provider from Terraform provider engineers. https://github.com/terraform-providers/terraform-provider-azurerm/tree/main/examples
5. Azure Build with Azur. https://developer.hashicorp.com/terraform/tutorials/azure-get-started/azure-build
6. After your main.tf is ready run the following command to create the infrastructure

``` Terraform Commands
terraform init
terraform fmt
terraform validate
terraform plan
terraform apply
terraform show
terraform state list
```

7. Terraform has created a lock file .terraform.lock.hcl to record the provider selections it made. Include this file in your version control repository so that Terraform can guarantee to make the same selections by default when you run "terraform init" in the future.

8. Get the zip & extract the zip content https://developer.hashicorp.com/terraform and https://developer.hashicorp.com/terraform/install#windows
9. Download Azure CLI on Windows https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest&pivots=winget