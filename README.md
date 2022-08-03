## Using the Demo

1. Make sure that the required secrets are defined on Cloudify Manager, as follows:

   | Secret                  |Description|
-------------------------|------|-----------|
   | `aws_access_key_id`     | AWS access key |
   | `aws_secret_access_key` | AWS secret key |
   | `aws_region`            | AWS region |
   | `aws_zone`              | AWS zone |
   | `azure_tenant_id`       | Azure tenant ID |
   | `azure_subscription_id` | Azure subscription ID |
   | `azure_client_id`       | Azure client ID |
   | `azure_client_secret`   | Azure client secret |
   | `azure_location`        | Azure location |
   | `public_key_content`    | The SSH public key (the actual contents) for the keypair specified by `aws_keypair` |
   | `private_key_content`   | The SSH private key (the actual contents) for the keypair specified by `aws_keypair` |

2. Upload the required plugins to Cloudify Manager:

   * AWS plugin (version 2.5.6+)
   * Azure plugin (version 3.0.10+)
   * Terraform plugin (version 0.15.0+)

3. Download this repository, clone or upload directly from the UI.
4. Upload the blueprint
5. Create and install deployment for azure
6. Create and install deployment for aws
7. Run infracost workflow

