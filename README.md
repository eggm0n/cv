### James Farlow | james.farlow@gmail.com

I am an experienced software engineer and technical leader with a demonstrated history of product and platform engineering with sustainable product delivery.

I am currently a senior software engineer and Tech Lead at Mettle / NatWest Boxed.

:page_facing_up: https://www.linkedin.com/in/jamesfarlow/

### Skills

I focus on server side functional programming, DevOps, microservices, developer productivity and agile methodologies. I have significant knowledge of developing backend services for user-facing web applications and integrating systems with event-driven approaches. I am a pragmatic and supportive team leader with experience of mentoring, coaching and people management.

__Leading Teams:__ I have over 10 years experience leading teams or being the senior practitioner in Agile teams, including ensuring the team’s responsibilities are being met through facilitation, identifying valuable features, making work visible, and running planning, design discussions, retrospectives, and other team meetings.

__Line Management:__ I have significant experience managing engineers within teams. I can also coach and mentor outside of team structures and I have been a people manager for product engineers across the technical profession including analysts, developers and quality assurance. 

__Architecture:__ I have supported teams to design and build mobile, web and server-side products and APIs. I am familiar with RESTful API design, using non-blocking web frameworks, both kubernetes and serverless architecture for scaling. I have integrated systems using events to provide robust and reliable data consistency, including handling errors and retries against (non event-driven) dependencies.

__Startup:__ I have experience in a startup environment. This involves testing new product ideas for viability and building in a lean manner. I have experienced both successful and unsuccessful products.

__Tech Vision:__ I am comfortable proposing, establishing consensus around, and communicating a shared technical vision. I have represented product development and technology to Fantoo's executive team.

__Growing Teams:__ I have lots of experience interviewing candidates, establishing, sharing and improving interview practices, and helping new people integrate. I have been directly involved in growing teams of up to 15 people, and have interviewed for positions across the technical profession.

__Development:__ I am an experienced and empathetic pair programmer. I advocate test driving production code with unit tests, and pragmatic use of integration and end-to-end tests to mitigate risk. I have worked in both Scrum and Kanban and embrace lean thinking.

__DevOps:__ I am familiar with both PR and trunk based development, short lived PRs, automated tests on merge, automated deployments to various environments. I have built deployment pipelines and automation of cloud native and cloud agnostic solutions in Azure, AWS and Kubernetes using tools like Jenkins, TeamCity and GitHub actions. I have deployed, operated and monitored serverless and kubernetes workloads in production.

__Java/Scala/Kotlin:__ My core development experience is in Java, Scala and Kotlin production systems. I am comfortable with various parts of Java and Scala ecosystem including Spring, Gradle, Maven, SBT, Play, Akka.

### Employment

#### Senior Software Engineer @ Mettle / NatWest Boxed - May 2022 to present

Mettle is a digital neobank for the self-employed, sole traders and limited companies. I am the Tech Lead for the Get Paid squad, responsible for customer invoicing functionality and Open Banking. This includes maintaining and enhancing services in both Spring Boot and Micronaut using Kafka for event sourcing and CQRS architecture. I have ensured that all our Open Banking services are correctly verified using contract testing in pact and that we have a robust process for mitigating vulnerabilities raised by Snyk and that this is understood and prioritised alongside product work. Prior to this I was in the Production Engineering team - a developer enablement squad focused on improving productivity and removing impediments for other squads. We rolled out GitHub Actions as a replacement for concourse to the engineering teams, created a custom java application to automatically migrate HelmReleases to Argo Applications and used pair/mob programming and Kanban to quickly test and learn. I have written a custom GitHub actions metrics server to report on job scheduling, written custom GitHub actions (bash, javascript, python, babashka), created a PR for adding Server Side Apply to the CNCF (Cloud Native Computing Foundation) Strimzi open source project and hosted open door support sessions for the engineering departmemt.

Project highlights include:
- Continuous deployment of production microservices in AWS and kubernetes serving 100k+ banking customers.
- Implementing CI/CD pipelines in GitHub actions including build, test, pact verification, snyk scanning, and secure GitOps based deployment to Kubernetes using ArgoCD.
- Gaining a deeper understanding of Kubernetes, helm charts, Argo CD by debugging developer issues with their pipelines and services.
- Supporting critical Open Banking services, responding to incidents and fixing bugs affecting customer payments.
- Joining an established team as Tech Lead and improving team focus on throughput, lowering WIP, prioritisation and team building to encourage more consistent and reliable delivery.

#### Senior Product Engineer @ Waitrose Digital - October 2018 to May 2022

Waitrose is undertaking a digital transformation to replatform all of waitrose.com onto AWS and microservices while decomissioning on-premise services. I worked in the Buy domain, responsible for the trolley, order and checkout. I was leading the rebuilding of the trolley services that provide trolley, pricing and legal restrictions all running on AWS. This included rebuilding the trolley in Kotlin with Spring Boot WebFlux and dual running it alongside the existing trolley services in order to migrate gradually to the new service. Previous to this, I was leading the team to integrate the AWS order services with downstream order fulfilment systems. I designed and implemented an event-driven architecture connecting order update events from order fulfilment to AWS to keep order history mastered in AWS, and allow orders placed in AWS to be reliably propagated to order fulfilment. To support a phased delivery of these requirements, the architecture was designed to keep both systems in sync until the placing of orders could be fully mastered on AWS. This work allowed customers to view their order history, shop from previous orders and place new orders, with an uninterrupted service while the on-premise servers were decomissioned.

As the technical Partner in the both the trolley and integration teams, I was responsible for overseeing and reviewing the development work of contractors and offshore staff within the team. I have also taken a fundamental role in defining the technical requirements for the project based on existing business systems, working with the product owner and product manager to achieve a joint understanding of the complicated workstream. Good communication skills have been key to this and my ability to translate between technical and business requirements has been remarked on in all my peer reviews.

Project highlights include:
- Developing and deploying production microservices in AWS used by millions of customers and serving 1k+ requests per second
- Designing for different workloads in both Java and Kotlin Spring Boot services on Kubernetes, and native Java services on AWS Lambda
- Event-driven microservice architecture using AWS lambda, SNS and SQS
- Capturing order placement metrics using AWS cloudwatch and Kinesis
- Diagnosing, developing, and deploying production fixes in short timescales taking advantage of CI/CD pipelines and automated testing
- Using Java Streams, Vavr, resilience4j and other libraries and techniques to gain the benefits of functional programming in the small
- Storing incoming events from upstream systems and folding over these events recalculating current service state to handle at least once delivery and out of order messages, demonstrating the benefits of functional programming in the large

#### Technical Architect @ Fantoo - January 2016 to October 2018

As the Technical Architect at Fantoo I had responsibility for all technical solutions which support the company’s core products. This includes desktop and mobile clients, server side applications, infrastructure and CI/CD components. I was responsible for maintaining a full understanding of the high-level architecture and interactions of all the products and ensuring their commercial robustness and scalability. I made sure to keep up-to-date with the latest technologies and industry trends so that the core technology supports the engaging user experience.

I helped to develop an engineering culture of quality and maintainability using techniques such as test-driven development, CI/CD and clean code. I am always keen to share my experience and learn from others, and to promote good development practices. I am also a strong and vocal proponent of agile methodologies and worked as part of delivery teams within Fantoo in both Scrum and Kanban.

I was directly responsible for all server-side development in Scala and all operations, infrastructure and architecture in Azure. I oversaw all development work for both mobile and desktop (including low level application design and architecture) in Android (Java), iOS (Swift) and Desktop (TypeScript, Angular and Electron). This involved pair programming with team members, whiteboard design sessions and code reviews.

Project highlights include developing the core web services in Scala using Play framework and MongoDB and building a custom SaaS licensing solution based on event-sourcing and CQRS in Scala using Akka.

Technology highlights include:
- Unstructured text summarisation and calculating time-to-read based on language complexity heuristics
- Tasks API with full CRUD capability, clean architecture style, and support for customisable 3rd party applications for customers and users
- Custom WebRTC (video chat) signalling implementation using WebSockets
- Using event sourcing and CQRS design principles to ensure a full recorded history of all system events
- RESTful API in Akka HTTP; Akka, Akka Cluster and Akka Persistence for Command side actor logic and sharding; Akka and Akka Persistence Query for Query side event streaming
- MySql for journal persistence and relational data querying, protobuf for event encoding
- Shapeless for automatic conversion of Protobuf generated case classes to application level case classes, Cats for validation

All core infrastructure was automatically provisioned by using the Azure CLI. This included using ARM templates to create end-to-end infrastructure, automated deployment of new debian packages, and custom scripting using the Azure CLI to create and deploy Azure Functions and App Services.

New infrastructure was being developed based on Kubernetes with an integrated development workflow based on git. This was using open source technologies such as Forge to automatically build and deploy new docker containers direct from developer branches.

#### Senior Technical Architect @ Howdoo - (Advisory role) - April 2017 to September 2018

Howdoo is a self-governing social media platform built upon blockchain and other decentralised technologies to allow users to take full control of securing or monetising their personal data. I co-authored the technical whitepaper to elaborate upon the founder’s vision, model the digital content economy, define the target-state decentralised architecture and propose various options for the technology stack.

Technology highlights include researching and understanding blockchain technology and ecosystem, exploring different options for technology stack (comparing Ethereum and Solidity to Graphene/BitShares etc) and modelling potential system behaviours and designing proof of contribution algorithm.

#### Principal Engineer @ BAE Systems Applied Intelligence - January 2009 to December 2015

Working within the NetReveal platform engineering team on a range of user focused products for social network analysis, fraud detection and investigation. Most recently I was leading a team architecting, developing and delivering a complete rewrite of the server-side component of the flagship investigation product using modern technologies to ensure scalability and flexibility of the solution in the future. I was fundamentally involved in designing and developing this project from the ground up including requirements gathering, writing specifications and creating an initial backlog of work. I prototyped features for early demonstration to stakeholders before incorporating these into the product.

Technology highlights include:
- Fully RESTful web service using Spring MVC and JAX-RS, backed by Oracle RDBMS and custom implementation of Sesame API for querying RDF data using SPARQL.
- Designing and developing a security model using Apache Shiro with application level security (authentication and authorisation), functional security (limiting user access to functions within the application) and data security (limiting user access to collections of data, individual data items and properties therein).
- Designing and developing end-to-end solutions for data import from detection engines, and data export to elastic search.
- Full support for data versioning and 'undo' via custom data schema allowing individual data item history to be stored and queried.
- Designing and developing a task framework based on Quartz for scheduling and performing asynchronous tasks. This allows high availability of the REST layer while supporting long running queries and actions. Task results are stored into new versions of the underlying data model which can be queried once tasks are complete.

#### Associate Software Engineer @ Accenture Technology Solutions - July 2006 to June 2007

Working for two clients over a period of eleven months (plus one month training) in various technology roles (integration test analyst, performance test analyst, defect management and TIBCO support analyst) and team environments, focusing on minimising duplication of work by automating processes.

### Education

#### The University of Warwick - 2004 to 2008

BSc (hons) in Computer Science with Intercalated Year, 2.1.
Final year project in recurrent neural networks for pattern recognition.

#### Wallington County Grammar School - 1997 to 2004

A-Levels: Computing (A), German (A), Maths (B), General Studies (B)
