# XYZ Delivery Executive Summary

XYZ Company is currently facing challenges with their development process which include difficulty starting new product environments, long lead times, and lack of consistency between the different product environments. In order to alleviate these challenges, XYZ Company has engaged Liatrio's services to help up-skill their development team on modern development practices, as well as migrate their products from an on-premises infrastructure to a cloud environment (AWS). 

Within this repository you will find relevant information about the solution Liatrio proposes in order to achieve the goal set out by XYZ Company. It contains the following:

- [Primary Goal](#primary-goal-of-this-engagement) and [Objectives](#objectives) of this program
- [Program delivery structure](#program-delivery-phase)
- [Personas that would most benefit from participating in this program](#entry-personas) *(hereafter referred to as **students**)*
- [A preliminary schedule for the program delivery](#preliminary-schedule)
- [Tools that will be utilized during the delivery of the program](#tools)
- [A description of how the program will be scaled](#scaling-the-program)
- [Slide deck presentation highlighting key information](XYZ%20Devops%20Transformation.pptx)

## Primary Goal

> The primary goal of this engagement is to move XYZ's on-premises product suite to a cloud-based solution while also improving the sustainability of XYZ's products. 

Every resource, time, personnel, artifact, and discussion dedicated to this program is aimed at achieving the set goal. This includes fostering a culture of continuous improvement, promoting collaboration, and enhancing the overall efficiency of the program. However, all elements, with the exception of the goal itself, are flexible and can be adjusted based on client needs and feedback obtained through iterative discovery. This approach ensures that the program remains dynamic, adaptable, and client-centric while maintaining its core objective.

## Objectives

Achieving the primary goal will require several key objectives to be met. These objectives are designed to target specific areas of DevOps and will be prioritized based on the needs of XYZ. Below are the initial objectives and milestones that are intended to be achieved during the delivery of this program based on observations made from other similar engagements:

- Up-skill students on a Continuous Integration and Continuous Delivery mindset
- Implement a CI/CD pipeline for automated code validation and shorter lead times to deploy
- Improve coding standards using a Linter
- Utilize containerization as a tool to make infrastructure more modular
- Start deploying code to the cloud to simplify provisioning new environments
- Up-skill students on TDD and ATDD to provide a more sustainable code base
- Implement DORA metrics to measure the change in performance of the development process
- Establish a DevOps culture to improve collaboration between teams

## Delivery Structure

Below you will find a general overview of the delivery structure for this program. This structure is designed to provide a solid foundation for the program while also allowing for flexibility and adaptability. This ensures that the program remains client-centric and can be adjusted to meet the needs of XYZ.

### Pilot Cohort

The implementation of a pilot cohort offers a multitude of benefits. It not only helps in controlling initial expenses but also minimizes the risk of unproductive development efforts. Furthermore, it provides an opportunity to collect valuable feedback that can predict the success of the program. In addition, a pilot cohort allows for real-world testing and refinement of the program before full-scale implementation. This can lead to improved user experience, increased adoption rates, and ultimately, a more successful program. It also facilitates the identification and resolution of potential issues early on, thereby reducing long-term costs and ensuring a smoother rollout.

To ensure the success of the pilot cohort, we will execute the following phases:

### Observational Phase

In the initial phase, a duo of Liatrio experts will interact with the pre-selected students attending a pilot version of the training. This observational phase serves multiple purposes. It allows the Liatrio team to familiarize themselves with the students, understand their various working domains, and gather detailed information about the challenges they commonly encounter. This information will enable the experts to prioritize the skills and tools that will be most beneficial to the attendees. 

Moreover, this approach provides an opportunity for early identification of potential issues, enabling proactive solutions and adjustments. It also fosters a collaborative learning environment where students feel seen and heard, which can lead to increased engagement and success in the program. Ultimately, this methodical and inclusive approach ensures a more effective and impactful training experience. 

### Program Development Phase

In the program development phase, a dedicated team of Liatrio experts will meticulously curate and compile learning materials. This will involve the careful selection of pre-existing content and the creation of new content where necessary. This approach ensures that the training is tailored to the specific needs and challenges identified during the observational phase. 

The timeline for this phase will be determined following the completion of the observational phase, but it will not exceed 2 months unless otherwise discussed. This structured approach allows for a thorough and thoughtful development process, ensuring that the training program is comprehensive, relevant, and effective. 

Moreover, this method allows for flexibility and adaptability, ensuring that any changes or adjustments can be made in a timely manner. This ultimately leads to a more successful training program that meets the needs of the participants and achieves the desired outcomes.

### Program Delivery Phase

During the program delivery phase, the Liatrio DevOps team, comprised of subject matter experts, will commence the training of the pilot cohort. Each day will start with a brief lecture to introduce the day's topic and set objectives for the morning exercise. This will be followed by a Dojo session in the afternoon for hands-on training, where students will work directly with production code. Both morning and afternoon sessions will incorporate pair and mob programming, with instructors actively engaging with groups to reinforce learned concepts. The week will conclude with retrospectives to assess the effectiveness of the learned practices. Regular check-ins with product owners and stakeholders will also be conducted weekly to ensure transparent communication of progress. More specifics about this phase can be found in the ["Preliminary Schedule"](#preliminary-schedule) section below.

### End of Pilot

After the program delivery is complete, Liatrio will implement the Kirkpatrick model to evaluate the effectiveness of the training. This model consists of four levels of evaluation:

- Level 1: Reaction - How did the students react to the training?
- Level 2: Learning - How much did the students learn?
- Level 3: Behavior - How much did the students change their behavior?
- Level 4: Results - How much did the training impact the business?

The Kirkpatrick model will be used to evaluate the effectiveness of the training at each level. The results of this evaluation will be used to determine the next steps for the program. 

## Entry Personas

The inaugural pilot cohort will primarily consist of software developers who are actively involved in both the coding and deployment processes. This strategic selection is designed to provide the delivery team with pertinent feedback regarding the adoption of new coding practices and development tools, thereby enhancing the effectiveness of the program.

Upon completion of the pilot cohort, feedback from participants and stakeholders will be meticulously analyzed. This invaluable input will guide the evaluation of additional personnel types for inclusion in future cohorts. This iterative approach ensures continuous improvement and adaptation of the program to meet diverse needs, ultimately leading to a more robust and successful training initiative.

## Preliminary Schedule

The daily schedule will be divided into two sessions, separated by a one-hour lunch break. The morning sessions will focus on introducing new concepts, providing a solid theoretical foundation, and exercises within sandboxed environments to allow for practice and experimentation. The afternoon sessions, on the other hand, will be dedicated to practical application in a Dojo environment. This hands-on approach allows students to apply what they've learned to their own code base, fostering a deeper understanding and mastery of the material. 

Immediate feedback from the Liatrio team during these practice sessions further enhances the learning experience. It not only helps students correct mistakes in real-time but also provides them with personalized guidance and support. This structured yet flexible learning environment promotes active engagement, encourages problem-solving, and ultimately leads to more effective skill acquisition and application.

The initial four weeks of the training will be dedicated to a set of prioritized topics, providing a structured learning path. The final week will be utilized for revisiting previous topics based on the progress and needs of the students, and addressing any additional topics deemed important by Liatrio's team of trainers. This approach ensures a comprehensive review and reinforcement of learned concepts, thereby enhancing the effectiveness of the training. Additionally, it allows for customization of the curriculum to better meet the needs of the students, leading to improved outcomes and greater student satisfaction.

The following is a preliminary schedule for the delivery of the program and is subject to change:

| Day | Morning Session | Afternoon Session |
| --- | --------------- | ----------------- |
| 1   | Introduction to DevOps and DevOps Culture | Dojo |
| 2   | Docker | Dojo |
| 3   | Kubernetes | Dojo |
| 4   | AWS Core Services | Dojo |
| 5   | Retrospective | Dojo |
| 6   | AWS ECR for Container Image Management | Dojo |
| 7   | AWS EKS for Container Orchestration | Dojo |
| 8   | AWS CodeCommit for Source Control Management | Dojo |
| 9   | AWS CodePipeline for Continuous Integration | Dojo |
| 10  | Retrospective | Dojo |
| 11  | AWS CodeBuild for Building and Testing Code | Dojo |
| 12  | AWS CodeDeploy for Continuous Delivery | Dojo |
| 13  | AWS CloudFormation for Infrastructure as Code | Dojo |
| 14  | AWS CloudWatch for Logging and Monitoring | Dojo |
| 15  | Retrospective | Dojo |
| 16  | AWS X-Ray for Tracing | Dojo |
| 17  | Test Driven Development | Dojo |
| 18  | Acceptance Test Driven Development | Dojo |
| 19  | DORA Metrics | Dojo |
| 20  | Retrospective | Dojo |
| 21  | Review | Dojo |
| 22  | TBD | Dojo |
| 23  | TBD | Dojo |
| 24  | TBD | Dojo |
| 25  | TBD | Dojo |

## Tools

To ensure the best possible outcomes we recommend the following tools be utilized during the course of this program:

- Conference room with large monitor, desks, and chairs for group discussions
- Laptops with Windows, Linux, or MacOS operating systems
- Visual Studio Code to provide a modern and consistent development environment
- ESLint for a consistent coding style
- Zoom for virtual video conferencing when necessary
- Docker for containerization
- Kubernetes for orchestration of containers
- Amazon Web Services (AWS) for cloud infrastructure
- Git and AWS CodeCommit for source control management
- AWS CodePipeline for Continuous Integration
- AWS ECR for container registry
- AWS EKS for container orchestration
- AWS CloudFormation for Infrastructure as Code
- AWS CloudWatch for logging and monitoring
- AWS X-Ray for tracing
- AWS CodeBuild for building and testing code
- AWS CodeDeploy for Continuous Delivery
- AWS CodeStar for project management

We are suggesting a close alignment with AWS for the cloud infrastructure because of the following reasons:

- AWS is the most widely used cloud provider
- AWS provides a wide range of services that can be used to build a robust cloud infrastructure, including compute, storage, networking, databases, and security
- AWS provides a free tier that can be used for training purposes, thereby reducing costs
- AWS provides a wide range of training materials and certifications that can be used to up-skill students that can be leveraged post delivery of the program
- AWS provides a wide range of tools that can be used to build a robust CI/CD pipeline, including source control management, continuous integration, continuous delivery, and infrastructure as code


## Scaling the Program

Once the pilot cohort has been successfully completed, the program will be scaled to include additional teams and personnel. This will be accomplished by utilizing the same delivery structure and schedule as the pilot cohort. However, the content of the training will be adjusted based on the feedback obtained from the pilot cohort. This iterative approach ensures that the program remains dynamic and adaptable, thereby increasing the likelihood of success.

