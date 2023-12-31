<div align="center">

### Integrating SonarQube with Jenkins

![myproject](https://user-images.githubusercontent.com/58173938/206842934-179f422c-fc4f-4e5c-96ae-71ddeefe3d1f.png)

</div>

SonarQube and Jenkins are both tools used for continuous integration and continuous delivery (CI/CD) of software projects. SonarQube is a static code analysis tool that can be used to find bugs, vulnerabilities, and code smells in the source code of a software project. Jenkins, on the other hand, is a automation server that can be used to automate various tasks related to building, testing, and deploying software.

While SonarQube can be used independently of Jenkins, it is often used in combination with Jenkins to provide automated code analysis as part of the CI/CD pipeline. In this setup, Jenkins is responsible for building, testing, and deploying the software, This allows developers to quickly identify and fix any issues in their code, ensuring that the software is of high quality and free of defects.

### Sonarqube access (username and password by default as admin)

![1 sonarqube access (username and password by default as admin)](https://user-images.githubusercontent.com/58173938/206843031-b68f6614-6842-4ded-ae59-0c824bf523ea.png)

### Change into new password

![2 change into new password](https://user-images.githubusercontent.com/58173938/206843077-c359c2e7-c291-4012-a2ce-f7f9e96026d4.png)

### homepage project-create

![3 homepage project-create](https://user-images.githubusercontent.com/58173938/206843098-d0ed3ba6-507f-43e7-95dd-536a6af3173d.png)

### Here after jenkins succesfully build completed

![4 here after jenkins succesfully build completed](https://user-images.githubusercontent.com/58173938/206843149-14db3962-a566-4d56-89a7-5ee6f52f01f7.png)

### Click on Administration

![5 Click on Administration](https://user-images.githubusercontent.com/58173938/206843182-19ff7842-8c16-4fe9-92e1-680e619240a3.png)

### Click on webhooks under configuration

![6 Click on webhooks under configuration](https://user-images.githubusercontent.com/58173938/206843218-4b06d83f-1ae7-4488-a9d4-7bcb0032f884.png)


### Create Webhook, Give a meaningfull name, give the url as yours and dump the `sonarqube` webhook

![7 Create Webhook, Give a meaningfull name, give the url as yours and dump the `sonarqube` webhook](https://user-images.githubusercontent.com/58173938/206844561-650e26a5-6932-4acf-80bc-4a4f1cb8d772.png)

### Quality gate check

![8 quality gate check](https://user-images.githubusercontent.com/58173938/206844642-a3481ba3-9f3a-4d89-bf01-d19ca107ba51.png)


## ❤ Show your support

Give a ⭐️ if this project helped you, Happy learning!


