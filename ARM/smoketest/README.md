# arm_smoketest

Very simply test to verify working Azure credentials.  This will create a resource group, `arm_smoketest`. Be sure that there is a properly configured `~/.azure/credentials` file.

# quick start

- cd to the `terraforms/ARM/smoketest` directory. Source the `azure_credentials.sh` (symlinked):

```
cd terraform/arm_smoketest
source ./azure_credentials.sh
```

- Run Terraform:

```
terraform plan
terraform apply
```
