# GCP-Cloud-SQL-with-Terraform

Create a directory and fetch the required Terraform scripts from the Cloud Storage bucket with:

mkdir sql-with-terraform
cd sql-with-terraform
gsutil cp -r gs://spls/gsp234/gsp234.zip .


![image](https://github.com/redjules/GCP-Cloud-SQL-with-Terraform/assets/106017493/30e7521d-7cf8-4b75-8186-895d2fbf80d6)


Unzip the downloaded content:
unzip gsp234.zip

![image](https://github.com/redjules/GCP-Cloud-SQL-with-Terraform/assets/106017493/4055dddd-3238-4865-a993-8bc83dc5967c)


Open variables.tf and modify the project and region variables to the values shown below:
project: qwiklabs-gcp-02-ef1825211b47
region: us-west1


RuN Terraform 

![image](https://github.com/redjules/GCP-Cloud-SQL-with-Terraform/assets/106017493/19e8a35b-f833-4097-ae27-39ec7c93127f)


Run terraform plan:


![image](https://github.com/redjules/GCP-Cloud-SQL-with-Terraform/assets/106017493/e96ed97e-001f-4fd5-8517-e19084f88c80)

![image](https://github.com/redjules/GCP-Cloud-SQL-with-Terraform/assets/106017493/895bc5cf-0dee-4d95-bcc7-03ebc7e1f174)

