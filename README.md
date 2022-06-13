# SpringBoot-CloudNative-Training

## Objective
This is a quick reference guide to understand usages of key components & capabilities in this training that trainee may require during api design and build phase. It also contains details and references to help you to getting started with initial set-up for development environemt, IDE for coding and other tool technologies which enable you to design, develop and deploy the customer-api & policy-api. We will follow following Software/API Development LifeCycle during this training.

![Software Development Lifecycle](https://github.com/acc-trainings-org/SpringBoot-CloudNative-Training/blob/main/img/sdlc.png?raw=true)


## Training Schedule (**`2022-06-13 - 2022-06-17`**)
* Day 1. Business Context, Microservices, Use Case, [API First Development](https://github.com/acc-trainings-org/SpringBoot-CloudNative-Training/tree/1.api-first-development)
* Day 2. Spring Boot Basics, [Spring Boot Development](https://github.com/acc-trainings-org/SpringBoot-CloudNative-Training/tree/2.spring-api-development)
* Day 3. Mongo DB Basics, [Spring Boot - Maven Development](https://github.com/acc-trainings-org/SpringBoot-CloudNative-Training/tree/3.spring-mongodb-development)
* Day 4. [Microservices Communication](https://github.com/acc-trainings-org/SpringBoot-CloudNative-Training/tree/4.microservices-communication), Containerization & Orchestration & OpenShift 
* Day 5. [DevOps](https://github.com/acc-trainings-org/SpringBoot-CloudNative-Training/tree/5.DevOps-CICD)
* Day 6. [Spring boot Cloud Native using OpenShift Service Mesh](https://github.com/acc-trainings-org/SpringBoot-CloudNative-Training/tree/6.service-mesh)
* Day 7. [Reactive Programming using Spring WebFlux](https://github.com/acc-trainings-org/SpringBoot-CloudNative-Training/tree/7.Reactive-Programming)

## Use Case
**`customer-api`**
* Design customer api using swagger open API
   * Create customer
   * Get customer
* Establish contract between API specification and business need
* Generate code from API
* Build code
* Package & Deploy

**`policy-api`**
* Donwload Policy API from Github Repository
* Run the code and see the response for getPolicy.
* Now add the local Customer API call in the Policy API code (webService/API call).
* Start both API services and verify the response from getPolicy.

## Tools & Technologies
* Spring Boot, Spring Cloud
* Mongo database
* Web Services (REST)
* OpenShift Cloud
* DevOps
* Jenkins
* Reactive Development
* Visual Studio Code
* Maven

## Prerequisties

#### **`Knowledge`**
* Basic understanding of Java (or any other programming language)
* Basic understanding of data formats such as XML and JSON.
* Basic understanding of YMAL.

#### **`Mandatory Learnings`**
1.	Pluralsight online training access
    * **Enroll:** Click [here](https://mylearning.accenture.com/mylearningui/learner/coursedetail/1648947)
2. Java training
    * **My Learning:** Click [here](https://mylearning.accenture.com/mylearningui/learner/coursedetail/1752600)
    * **Plural Sight:** Click [here](https://app.pluralsight.com/channels/details/54ceb573-56a9-4c5a-85f8-e72514c46fb0)
3. Spring Framework
    * **My Learning:** Click [here](https://mylearning.accenture.com/mylearningui/learner/coursedetail/1752592)
    * **Plural Sight:** Click [here](https://app.pluralsight.com/channels/details/6d5e513e-fbc3-4818-a60b-3d14f82035b7)
    
#### **`Required Software`**
1.	Check hardware and software requirements
    * Need a Workstation with Admin rights(Accenture Machine/Personal Laptop)
2.	Teams Access
    * [Teams channel](https://teams.microsoft.com/l/team/19%3a812369d073a741c3a3ccbba976f3697f%40thread.tacv2/conversations?groupId=f9510dd1-3e7e-40c1-bbaf-6fe8dc467c40&tenantId=e0793d39-0939-496d-b129-198edd916feb) will be used for collaboration/communication.    
3.	Check system compatibility with platform software.
4.	Install JDK Version **11.0.10_9** from [here](https://github.com/AdoptOpenJDK/openjdk11-binaries/releases/download/jdk-11.0.10+9/OpenJDK11U-dk_x64_mac_hotspot_11.0.10_9.pkg)
5.	Download Visual Studio Code from following URL
    * **Download:** Click [here](https://code.visualstudio.com/Download) 
    * **Geeting Started:** Click [here](https://code.visualstudio.com/docs/java/java-spring-boot)
6.	GitHub Desktop - [Download](https://desktop.github.com/)    
7.  Postman - [Download](https://www.postman.com/downloads/)
    
#### **`Visual Studio Code Required Plugins`**
Few of the extensions should be pre-installed when you install Visual Studio Code. If you can't see then install from extension tab.
* [Spring Boot Extension Pack](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-boot-dev-pack)
* [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
* [Maven for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven)
* [OpenAPI Preview](https://marketplace.visualstudio.com/items?itemName=zoellner.openapi-preview)
* [Swagger Viwer](https://marketplace.visualstudio.com/items?itemName=Arjun.swagger-viewer)
* [openapi-lint](https://marketplace.visualstudio.com/items?itemName=mermade.openapi-lint)
* [Java Code Generator](https://marketplace.visualstudio.com/items?itemName=sohibe.java-generate-setters-getters)
* [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

#### **`Steps for installation`**
* Click on Extension tab from right panel on Visual Studio Code IDE.
* Search above mentioned extensions and click on install.

![Visual Studio Code Extension](https://github.com/acc-trainings-org/SpringBoot-CloudNative-Training/blob/main/img/vscode_extension.png?raw=true)

