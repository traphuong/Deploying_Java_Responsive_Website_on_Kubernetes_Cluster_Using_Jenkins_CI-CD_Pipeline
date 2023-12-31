<div align=center>
  
  ## Creating Docker hosted repository in Nexus and pushing the docker image through Jenkins
  
  ![myproject](https://user-images.githubusercontent.com/58173938/206851411-ea744639-53fd-42ca-af97-8bf0869fb361.png)
  
  </div>
  
  A hosted repository through Jenkins on a Nexus private registry is a way to manage and store Docker images for use in a Jenkins build pipeline. A Nexus private registry is a place where we can store and manage our Docker images, so that they are accessible to our Jenkins build pipeline. we can then configure Jenkins to push built Docker images to our Nexus registry, and to pull them from the registry as needed during the build process.

To set up a hosted repository through Jenkins on a Nexus private registry, we will first need to set up the Nexus registry and configure it to work with Jenkins. Once this is done, we can create a Jenkins pipeline that uses Docker to build and test our software. The pipeline can be configured to push the built Docker images to our Nexus registry, and to pull any required images from the registry as part of the build process.

Overall, using a hosted repository through Jenkins on a Nexus private registry can help streamline our software development and deployment process, by making it easier to manage and deploy Docker images.

### Generate secret pass to hide the nexus password

![1 Generate secret pass to hide the nexus password](https://user-images.githubusercontent.com/58173938/206851465-e087134a-260f-4458-a6a6-adef9d143706.png)

### Docker build and docker push stage

![2 Create  `docker build and docker push stage`](https://user-images.githubusercontent.com/58173938/206851478-58744433-d66f-417f-819e-a0653310a9ec.png)

###  Build was successfull

![3 Build was successfull](https://user-images.githubusercontent.com/58173938/206851491-703252c5-582f-49b9-99ff-ff332eb023d3.png)

### Go to nexus

![4 Go to nexus](https://user-images.githubusercontent.com/58173938/206851515-78a6fdf3-e67e-4d45-ace0-feb0e28e92ff.png)

###  Tap on browse and select your hosted repo

![5 Tap on browse and select your hosted repo](https://user-images.githubusercontent.com/58173938/206851540-ce7cfef8-ac7a-4d10-b138-5cd1932bf21b.png)

### As we can see we have the repo updated with the Build ID

![6 As we can see we have the repo updated with the Build ID](https://user-images.githubusercontent.com/58173938/206851567-432be5b7-a474-49c0-826a-9b93d6dbd2aa.png)

## ❤ Show your support

Give a ⭐️ if this project helped you, Happy learning!
