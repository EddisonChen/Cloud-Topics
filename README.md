Topics

Cloud & DevOps
  - The cloud is the hosting and storage of data and services or applications on external servers that are not your own, generally owned by AWS, GCP, or Azure.
  - DevOps is a methodology that focuses on continual delivery and review of software and bridges the gap between development and infrastructure.
  
  - So far, we've created instances on AWS and GCP and hosted APIs and databases in the cloud. Currently, we're working on a project that centers around uploading         trainee profiles as PDFs into a database hosted in AWS. The entire application will also be deployed in AWS.
  - We've also been working on using different tools for automation and deployment of infrastructure, which directly benefits the development of our applications.
  
  - The benefits of cloud is the increased reliability due to the redundancies built into these cloud servers. If a business had an on-premise server, one accident,       fire, or disaster could wipe out the entire company's data or cause their services to go down indefinitely. But with third party servers, even if one goes             down, data and services are stored in multiple locations, ensuring that both data and functionality of services are maintained. Another benefit is the                 cost, with cloud, you only pay for the amount of resources that you need.
  - The benefits of DevOps is that software is delivered and reviewed more frequently, which ensures higher quality code and promotes adaptibility, partially               because this continuous delivery means that testing happens more frequently. DevOps also brings together the development and operations/infrastrucutre teams,           which ensures that both teams are on the same page and promotes coordination, which leads to a higher quality product. 
    
CICD
  - CICD stands for continuous integration, continuous delivery/deployment. Continuous integration means that new code and changes are continually and regularly tested     and merged to the main branch. Continuous delivery means after changes are pushed to a main repository, they are then deployed into a live environment. This           process involves a lot of automation when testing and releasing new code or alterations to existing code.
  
  - So far, we've worked on using Jenkins to automate unit testing of our applications and deploying our application upon a push to GitHub. The cloud project that we       are currently working on will utilize Jenkins to implement a CICD pipline for our application.
  
  - The main benefit of CICD is efficiency. When many steps are automated, this prevents human error and ensures that code updates is being pushed regularly, without       being stuck on different parts of the process that would otherwise require attention. This entire process promotes high quality code and regular updates and helps     to ensure that different teams are coordinating and on the same page.

Jenkins
  - Jenkins is a program that is used to implement an automated CICD pipeline. Jenkins can be configured to run unit and integration tests, and deploy applications         to a live environment for more testing.
  - We've used Jenkins to automate unit testing and deployment of applications from GitHub. Jenkins will also be used in our cloud projects to create a functional CICD     pipline.
  - The benefits of using Jenkins is similar to the benefits of having a CICD pipeline in general because Jenkins is just a tool used for CICD. The efficiency of           automating unit testing and deployment leads to better coordination and higher quality code.  
  
Provisioning
  - Provisioning is the process of setting up infrastructure and allocating resources. This can be be done manually and automatically using tools like Terraform and       Docker, which can be used to set up virtual environments or cloud instances on which applications can be deployed.
  - We have provisioned virtual environments manually using Vagrant to launch a local virtual machine and AWS to launch instances, but we have also used Terraform to       launch databases and instances in AWS and on a local server. We learned how to use Docker to create and provision containers for applications.
  - The benefits of provisioning and creating virtual environments is mainly for compatibility and repeatability. When deploying and testing applications on virtual       machines, the environments are all identical, and factors such as different specifications or operating systems don't play a role. This makes the testing process       much easier and more repeatable.
  
Networking

Principle of Least Privilege

IAC

Packer and Terraform
