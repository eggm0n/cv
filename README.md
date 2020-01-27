### James Farlow | james.farlow@gmail.com

I am an experienced Software Engineer and Technical Architect with a demonstrated history of platform engineering, product delivery and technical leadership.

I focus on server side functional programming, DevOps, microservices, and agile methodologies. I have significant experience developing backend services for user-facing web applications and integrating systems with event-driven approaches. I am a pragmatic and supportive team leader.

I am a strong engineering professional with a BSc (hons) in Computer Science from the University of Warwick.

I am currently a Senior Software Engineer at Waitrose Digital migrating core checkout functionality of waitrose.com to microservices in AWS.

:octocat: https://github.com/eggm0n

:page_facing_up: https://www.linkedin.com/in/jamesfarlow/

### Skills

- Software development practices and agile methodologies
- Server side and functional programming in Scala and Java
- DevOps and infrastructure

__Leading Teams:__ I have over 6 years experience leading teams or being the senior practitioner in Agile teams (servant leadership).  This involves ensuring the team’s responsibilities are being met through facilitation, identifying valuable features, making work visible, and running planning, design discussions, retrospectives, and other team meetings.

__Technical Architect:__ I have supported teams to design and build mobile, web and server-side products and APIs.

__Startup:__ I have experience in a startup environment. This involves testing new product ideas for viability and building in a lean manner. I have experienced both successful and unsuccessful products.

__Management:__ I have represented product development and technology to Fantoo's executive team.

__Tech Vision:__ I am comfortable proposing, establishing consensus around, and communicating a shared technical vision.

__Growing Teams:__ I have lots of experience interviewing candidates, establishing, sharing and improving interview practices, and helping new people integrate. I have been directly involved in growing teams of up to 15 people.

__Pair Programming:__ I am an experienced and empathetic pair programmer.

__TDD:__ I advocate test driving production code with unit tests, and pragmatic use of integration and end-to-end tests to mitigate risk.

__CI & CD:__ I am familiar with both git flow and trunk based development, short lived PRs, automated tests on merge, automated deployments to various environments.

__Infrastructure & Ops:__ I have built deployment pipelines and automation of cloud native and cloud agnostic solutions in Azure.

__Web Architecture:__ I am familiar with RESTful (and hypermedia) design including non-blocking web frameworks and stateless architecture for scaling.

__Event-driven Architecture:__ I have integrated systems using events to provide robust and reliable data consistency, including handling errors and retries against (non event-driven) dependencies.

__Java & Scala:__ My core development experience is in both Java and Scala production systems. I am comfortable with various parts of Java and Scala ecosystem including Spring, Maven, SBT, Play, Akka.

__Agile:__ I have worked in both Scrum and Kanban and embrace lean thinking.

### Employment

#### Senior Software Engineer @ Waitrose Digital - October 2018 to present

Waitrose is undertaking a digital transformation to replatform all of waitrose.com onto AWS and microservices while decomissioning on-premise services. I work in the Buy domain, responsible for the order and checkout process, and am leading the team to integrate the AWS order services with downstream order fulfilment systems. I have designed and implemented an event-driven architecture connecting order update events from order fulfilment to AWS to keep order history mastered in AWS, and allow orders placed in AWS to be reliably propagated to order fulfilment. To support a phased delivery of these requirements, the architecture has been designed to keep both systems in sync until the placing of orders can be fully mastered on AWS. This work will allow customers to view their order history, shop from previous orders and place new orders, with an uninterrupted service when the on-premise servers are decomissioned.

As the technical Partner in the integration team, I am responsible for overseeing and reviewing the development work of contractors and offshore staff within the team. I have also taken a fundamental role in defining the technical requirements for the project based on existing business systems, working with the product owner and product manager to achieve a joint understanding of the complicated workstream. Good communication skills have been key to this and my ability to translate between technical and business requirements has been remarked on in all my peer reviews.

Project highlights include:
- Developing and deploying production microservices in AWS used by millions of customers
- Designing microservices for different workloads in both Spring Boot on Kubernetes, and Java services on AWS Lambda
- Event-driven microservice architecture using AWS lambda, SNS and SQS
- Capturing order placement metrics using AWS cloudwatch and Kinesis
- Diagnosing, developing, and deploying production fixes in short timescales taking advantage of CI/CD pipelines and automated testing
- Using Java Streams, Vavr, resilience4j and other libraries and techniques to promote the benefits of functional programming in the small
- Storing incoming events from upstream systems and folding over these events recalculating current service state to handle at least once delivery and out of order messages, demonstrating the benefits of functional programming in the large

#### Technical Architect @ Fantoo - January 2016 to October 2018

As the Technical Architect at Fantoo I had responsibility for all technical solutions which support the company’s core products. This includes desktop and mobile clients, server side applications, infrastructure and CI/CD components. I was responsible for maintaining a full understanding of the high-level architecture and interactions of all the products and ensuring their commercial robustness and scalability. I made sure to keep up-to-date with the latest technologies and industry trends so that the core technology supports the engaging user experience.

I helped to develop an engineering culture of quality and maintainability using techniques such as test-driven development, CI/CD and clean code. I am always keen to share my experience and learn from others, and to promote good development practices. I am also a strong and vocal proponent of agile methodologies and worked as part of delivery teams within Fantoo in both Scrum and Kanban.

I was directly responsible for all server-side development in Scala and all operations, infrastructure and architecture in Azure. I oversaw all development work for both mobile and desktop (including low level application design and architecture) in Android (Java), iOS (Swift) and Desktop (TypeScript, Angular and Electron). This involved pair programming with team members, whiteboard design sessions and code reviews.

Project highlights include developing the core web services in Scala using Play framework and MongoDB and building a custom SaaS licensing solution based on event-sourcing and CQRS in Scala using Akka.

Technology highlights include:
- Unstructured text summarisation and calculating time to read based on language complexity heuristics
- Tasks API with full CRUD capability, clean architecture style, and support for customisable 3rd party applications for customers and users
- Custom WebRTC (video chat) signalling implementation using WebSockets
- Using event sourcing and CQRS design principles to ensure a full recorded history of all system events
- RESTful API in Akka HTTP; Akka, Akka Cluster and Akka Persistence for Command side actor logic and sharding; Akka and Akka Persistence Query for Query side event streaming
- MySql for journal persistence and relational data querying, protobuf for event encoding
- Shapeless for automatic conversion of Protobuf generated case classes to application level case classes, Cats for validation

All core infrastructure was automatically provisioned by using the Azure CLI. This included using ARM templates to create end-to-end infrastructure, automated deployment of new debian packages, and custom scripting using the Azure CLI to create and deploy Azure Functions and App Services.

New infrastructure was being developed based on Kubernetes with an integrated development workflow based on git. This was using open source technologies such as Forge to automatically build and deploy new docker containers direct from developer branches.

#### Senior Technical Architect @ Howdoo - (Advisory role) - April 2017 to September 2018

Howdoo is a self-governing social media platform built upon blockchain and other decentralised technologies to allow users to take full control of securing or monetising their personal data. I co-authored the technical whitepaper to elaborate upon the founder’s vision, model the digital content economy, define the target-state decentralised architecture and propose various options for the technology stack. I have continued to provide technical guidance to the development team during the project.

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
