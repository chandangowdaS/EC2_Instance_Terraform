# EC2_Instance_Terraform_EXSISTING_KEY_PAIR

Creating EC2 instance with the help of HCL script which will be able to create and launch an EC2 instance with exsisting key pair in AWS using two blocks they are resource and provider

HashiCorp Configuration Language (HCL), which is employed in Terraform for the purpose of automating various tasks in a more efficient manner compared to the traditional console methods. The project was developed using just two fundamental components: Resources and Providers from the Terraform ecosystem. The Provider, a particularly potent tool within Terraform, serves as a cornerstone for generating assets within the realm of IT, ensuring proper authorization and authentication throughout the process.

Before Initialising Terraform need to give access os aws secret key with the hlp of aws configure command

Later by using these 3 commands terraform init, terraform plan, terraform apply instance will create and able to see in AWS accound and Instance is created in the name "EC2_moba"

After creating an instance, I was able to access the instance using IP 52.27.227.18 and creeated two files in it

Later give terraform destroy command it will delete the instance and security group that was created