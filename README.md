
# Aws-Terrform-IAAC
![Terrafrom picture](https://user-images.githubusercontent.com/90862957/227426615-8b63b964-ae25-4a7e-821a-c24e320b3a64.png)

### [For more info click here](https://blog.awsfundamentals.com/what-is-terraform)

```diff
- credits Tobias Schmidt 
```


## Deploy a Website with Terraform

In this project i demonstrated how to use Terraform to deploy a dynamic ecommerce application on aws. Using the Reference Architecture below, i used terraform to create the following resources; VPC with public and private subnet, Nat gateway, Security group, RDS, Application load balancer, SNS, Auto Scaling Group and Route 53.In addition to terraform, i also used DevOps tools like, Git, Github, Visual Studio Code and AWS CLI to complete this project


****
## Project Reference Architecture

![Architecture](https://user-images.githubusercontent.com/90862957/227430090-a4960b88-f0d3-417e-b611-13fefdc35651.png)


After setting up my enviroment, i created all the files needed to create all the resourses in my project file in vscode. The files can be found in my code directory.
****
# Steps
![Stepwise](https://user-images.githubusercontent.com/90862957/227430645-6299cec0-4a2d-491c-93c3-775fe27bab7a.png)

The files contains reference templates that has notes which explains what each syntax in the file does, See Screenshots below of the Vscode project files and the corresponding resourses created in AWS.

- - -

[1.Authenticating with AWS ](#authenticating-with-aws-with-a-maintf-file)

[2.Create VPC with a vpc.tf filer](https://github.com/ArcProjects/Aws-Terrform-iaac/blob/main/README.md#create-vpc-with-a-vpctf-file)

[3.Create nat gateway](#create-nat-gateway-with-a-nat-gatewaytf-file)

[4.create-security-group-with-security-grouptf-file](#create-security-group-with-security-grouptf-file)

[5.Create RDS](#Create-RDS-with-rdstf-file)

[6.Create ALB](#create-application-load-balancer-with-albtf-file)

[8.create sns topic with snstf file](#create-sns-topic-with-snstf-file)

- - -

### Authenticating with AWS with a "main.tf" file
Provide the login credentials for your account. Using this credentials the terrform will authenticate with AWS.

![main.tf](https://user-images.githubusercontent.com/90862957/227527109-b49b570c-438e-44b9-ada1-1684be450234.png)


- - -

### Create VPC with a vpc.tf file


![2 _VPC_Reference_Architecture](https://user-images.githubusercontent.com/90862957/227527465-adf28d8e-1e8b-499a-bc8f-d114683c10c5.png)
![VPC Steps](https://user-images.githubusercontent.com/90862957/227527656-3942fb27-e17d-4036-a4d5-31533c76f2fb.png)



![image](https://user-images.githubusercontent.com/90862957/227531052-729eac70-5842-4442-b794-245dedcd60ca.png)

![image](https://user-images.githubusercontent.com/90862957/227531468-cae20733-6c93-44b9-963a-4353f23c3bf7.png)

![image](https://user-images.githubusercontent.com/90862957/227531599-aa378d63-020c-4310-9ea3-36399fa11086.png)

![image](https://user-images.githubusercontent.com/90862957/227531877-4c9d6706-5417-4523-9fa2-4f8a24058ab6.png)
- - -



### Create Nat-Gateway with a nat-gateway.tf file

![3 _Nat_Gateway_Reference_Architecture](https://user-images.githubusercontent.com/115881685/226754428-bdd57e8a-4abc-47f6-9fb5-71f0709d7c4e.jpg)

![image](https://user-images.githubusercontent.com/90862957/227536397-7e9e5e29-92d7-4eea-9134-ae40b4459f6b.png)

![image](https://user-images.githubusercontent.com/90862957/227535221-96c45760-e4e7-4e1c-8a06-c2369c48de8f.png)

![image](https://user-images.githubusercontent.com/90862957/227535686-c022481e-f9ea-4af8-be87-645bc90c3090.png)

![image](https://user-images.githubusercontent.com/90862957/227535792-b81bf3d2-0984-4abb-b731-7ea2ae2b9181.png)

- - -



### Create Security Group with security-group.tf file



![image](https://user-images.githubusercontent.com/90862957/227539087-3679aabb-74d2-4e68-853e-9bc50d8e741d.png)


![image](https://user-images.githubusercontent.com/90862957/227539309-f1e73fe2-8715-4209-a158-3b4ad3f0f61a.png)
- - -



### Create RDS with rds.tf file


![image](https://user-images.githubusercontent.com/115881685/226756047-cfe8fbf0-2eeb-411c-a0ea-dd0fd18c93ba.png)


![image](https://user-images.githubusercontent.com/115881685/226756136-9ac0c2b3-6ebd-48b6-836c-291c7d833abe.png)


![image](https://user-images.githubusercontent.com/115881685/226756269-62bae8b4-6af8-4ece-ba9d-6e7515202cdc.png)
- - -



### Create Application Load Balancer with alb.tf file


![image](https://user-images.githubusercontent.com/115881685/226756595-69809979-a259-4a67-926d-17b2131d7bfe.png)

![image](https://user-images.githubusercontent.com/115881685/226756715-de9cfad4-5c93-4a83-917d-f0b6b7448855.png)

![image](https://user-images.githubusercontent.com/115881685/226756807-897aa736-67eb-4c44-9313-0b393001e0ce.png)
- - -



### Create SNS Topic with sns.tf file


![image](https://user-images.githubusercontent.com/115881685/226757096-c06d3b0a-9b37-47bd-8c9e-92eeb6b28998.png)

![image](https://user-images.githubusercontent.com/115881685/226757223-05bb3c26-eb8f-4cb5-a28e-5f4378e860dc.png)

![image](https://user-images.githubusercontent.com/115881685/226757323-0ae54868-6935-4207-94c0-2d7603a6682f.png)

![image](https://user-images.githubusercontent.com/115881685/226757414-ed0d8963-7895-43cd-828a-aa4417f3fcb7.png)
- - -
