# Terraform-custom-provider

Build provider

Run the following command to build the provider
$ go build -o terraform-provider-ansh

Test sample configuration

First, build and install the provider.
$ make install

Then, navigate to the examples directory.
$ cd examples

Run the following command to initialize the workspace and apply the sample configuration.
$ terraform init && terraform apply
