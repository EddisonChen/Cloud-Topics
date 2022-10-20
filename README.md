Topics

Cloud & DevOps
  - The cloud is the hosting and storage of data,services, or applications on external servers that are not your own, generally owned by AWS, GCP, or Azure.
  - DevOps is a methodology that focuses on continual delivery and review of software and bridges the gap between development and infrastructure by having a team be       responsible for all of developing, testing, deploying, and maintaining infrastructure. Its goal is to deliver updates and push product out to clients as early and     as often as possible by making the process of developing and deployment more efficient.
  
  - So far, we've created instances on AWS and GCP and hosted APIs and databases in the cloud. We've also created a product as an Agile team, an application that           enables uploading of Nology student profile PDFs into an S3 Bucket. This includes a React front-end that allows for searching through the profiles, sorting, and       downloading profiles en mass. Terraform and Packer are used to create the AWS environment on which the application runs, and Jenkins is used for CICD, in order to     conduct unit testing and deploy pushed changes.
  - We've also been working on using different tools for automation and deployment of infrastructure, which directly benefits the development of our applications.
  
  - The benefits of cloud is the increased reliability due to the redundancies built into these cloud servers. If a business had an on-premise server, one accident,       fire, or disaster could wipe out the entire company's data or cause their services to go down indefinitely. But with third party servers, even if one goes             down, data and services are stored in multiple locations, ensuring that both data and functionality of services are maintained. Another benefit is the                 cost, with cloud, you only pay for the amount of resources that you need.
  - The benefits of DevOps is that software is delivered and reviewed more frequently, which ensures higher quality code and promotes adaptibility, partially               because this continuous delivery means that testing happens more frequently. DevOps also brings together the development and operations/infrastrucutre teams,           which ensures that both teams are on the same page and promotes coordination, which leads to a higher quality product. The main benefit of DevOps is increased         coordination and efficiency in the development and deployment process, which allows product to be delivered sooner and more often.
    
CICD
  - CICD stands for continuous integration, continuous delivery/deployment. Continuous integration means that new code and changes are continually and regularly tested     and merged to the main branch. Continuous delivery means after changes are pushed to a main repository, they are then deployed into a live environment. This           process involves a lot of automation when testing and releasing new code or alterations to existing code.
  
  - So far, we've worked on using Jenkins to automate unit testing of our applications and deploying our application upon a push to GitHub. The cloud application that     we completed utilizes Jenkins to unit test our code and to automate deployment of the application upon push/successful unit testing.
  
  - The main benefit of CICD is efficiency. When many steps are automated, this prevents human error and ensures that code updates is being pushed regularly, without       being stuck on different parts of the process that would otherwise require attention. This entire process promotes high quality code and regular updates and helps     to ensure that different teams are coordinating and on the same page.

Jenkins
  - Jenkins is a program that is used to implement an automated CICD pipeline. Jenkins can be configured to run unit and integration tests, and deploy applications         to a live environment for more testing.
  - We've used Jenkins to automate unit testing and deployment of applications from GitHub. Jenkins is also used in our cloud projects to create a functional CICD         pipline to automate unit testing and deployment of changes.
  - The benefits of using Jenkins is similar to the benefits of having a CICD pipeline in general because Jenkins is just a tool used for CICD. The efficiency of           automating unit testing and deployment leads to better coordination and higher quality code.  
  
Provisioning
  - Provisioning is the process of setting up infrastructure and allocating resources. This can be be done manually and automatically using tools like Terraform and       Docker, which can be used to set up virtual environments or cloud instances on which applications can be deployed.
  - We have provisioned virtual environments manually using Vagrant to launch a local virtual machine and AWS to launch instances, but we have also used Terraform to       launch databases and instances in AWS and on a local server. We learned how to use Docker to create and provision containers for applications.
  - The benefits of provisioning and creating virtual environments is mainly for compatibility and repeatability. When deploying and testing applications on virtual       machines, the environments are all identical, and factors such as different specifications or operating systems don't play a role. This makes the testing process       much easier and more repeatable.
  
Networking
  - Networking is the process of and factors involved in connecting different computers or machines.
  - We've done networking when connecting different virtual machines using Vagrant, SSHing into virtual machines, and when connecting our computers to AWS/GCP             instances. We're also using Docker to connect different containers.
  - The benefits of networking is essentially just communication and transfer of data/information between machines.

Principle of Least Privilege
  - This principle means that users of a service are only granted enough access to do their jobs or what they need to do. Users aren't given access or permissions to       data/services that is not necessary for them.
  - We've done some permissions settings when using Terraform and creating databases and users for those databases. We had to set access rights for those users, to         determine if they could create, select, update, or delete, or any combination of these privileges.

IAC
  - Infrastructure as code is using code to provision and manage infrastructure, things like cloud instances, databases, etc. 3 Tools used for this are Ansible,           Terraform, and Packer.
  - We've used IAC when using Terraform to provision AWS instances and databases, and Packer to create AMIs in AWS.
  - The benefit of IAC is that it automates the provisioning of environments/infrastructure for developers and makes creating a specific environment much more             shareable via source control and reproducible. With IAC, environments can also be created and destroyed easily and quickly.

Packer and Terraform
  - Packer and Terraform are both IAC tools used to provision infrastructure. Packer is used to create images for different platforms, and terraform is used to             provision different types of infrastructure.
  - We've used Terraform to provision AWS instances and databases, and Packer to create AMIs in AWS.
  - The benefit of Packer and Terraform is the same as for IAC. These tools allow for the automating of provisioning infrastructure and increases efficiency by making     environments more reproducible and shareable.
