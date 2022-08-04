## Using the Demo

1. Make sure that the required secrets are defined on Cloudify Manager, as follows:

   | Secret                  |Description|
-------------------------|------|-----------|
   | `aws_access_key_id`     | AWS access key |
   | `aws_secret_access_key` | AWS secret key |
   | `azure_tenant_id`       | Azure tenant ID |
   | `azure_subscription_id` | Azure subscription ID |
   | `azure_client_id`       | Azure client ID |
   | `azure_client_secret`   | Azure client secret |

2. Upload the required plugins to Cloudify Manager:

   * Terraform plugin (version 0.15.0+)

3. Download this repository, clone or upload directly from the UI.
4. Upload the blueprint
5. Create and install deployment for azure
6. Create and install deployment for aws
7. Run infracost workflow

