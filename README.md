# Provision a compute instance in GCP

This Terraform configuration provisions a compute instance in Google Cloud Platform.

## Details

By default, this configuration provisions a compute instance from the latest ubuntu-1804-lts image with machine type t2.micro in the us-east1-b zone of the us-east1 region. But the image_project, image_family, type, zone, and region can all be set with variables.

Note that you need to set provide your GCP credentials in the gcp_credentials variable.
