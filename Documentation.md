# Building Cloud Computing Solutions at Scale 

### Reproducible Code

If a discussion involves code, the ability to reproduce the system significantly enhances the conversation. 
The source code that is shared or discussed must run smoothly. If not, then it could add zero or even negative value to sharing it. 
Hosted git and hosted Jupyter Notebooks are two common ways to solve this problem. 

### Hosted git

Three main versions of hosted git are: bitbucket, github and GitLab. They all provide ways to share and reproduce code. This code can be 
shared within the context of a software development project, and it can also be shared in an async based discussion like chat. On Github,
the most commonly encountered of these options. There are two main ways to share code with others. One method is to create a public repo 
and share code and/or markdown files. One nice side effect of markdown files is that they can also serve out via web pages through GitHub Pages, 
which can build pages <1 ms per page. Another powerful feature of Github is a gist. What is particularly useful about a gist is that it can
be shared with syntax highlighting and formatting.

### Hosted Jupyter Notebooks 

In theory, Jupyter Notebooks solve a massive problem in creating reproducible code, but it needs some help in practice. A fundamental limitation
of Jupyter is the Python packaging environment. It is a helpless victim to the untamed complexity of the underlying operating system. Fortunately,
there is an easy solution. Jupyter notebooks that have a portable runtime are the reproducible ones. Portable runtimes include docker and colab. 
Docker format files can specify what the runtime should be like, including the passages that need for installation. One example of a hosted runtime
can be in this project: Container Microservices project. For a user to recreate the code and run it locally. This approach is optimized for deployment 
and has some advantages for communication focused on deploying software. A second approach is the colab approach .In this colab example the notebook 
note only has the complete code, but with a click of the “Open in Colab” button, a user can completely reproduce what was shared

### Critical Thinking 

Effective critical thinking is one of the most important skills you can learn for things like cloud computing, technology management. And the reason 
why is that there are many choices that you can make and the only way to solve between one choice and another is to use critical thinking. First, 
there's intellectual humility. What this means is that you have the ability to realize that you're not always right and that many times you could have 
a blind spot or some kind of a bias and that you're constantly looking out for when you're wrong. And this is a trait of critical thinking that's often 
missing, and you can see this probably in your own workplace. Another aspect of critical thinking is courage. So if you've gone through and done the research, 
looked at the problem, scientifically studied it, and you know that there's a particular solution, but the vast majority of people don't believe it, you have to 
have the courage to go through and fight for what it is that you believe in based on the reasoning that you've come up with. This is a really important aspect of critical thinking.


Another component of it is empathy. So can you go into the mind of someone who is disagreeing with what you're saying, intellectually and understand why is it that they're asking you to believe their viewpoint. Once you get into the mind of someone else and you have empathy for their viewpoint, it's a lot easier to come up with a maybe a compromise or a direction where both of you have some path forward. Another key component is autonomy. So, are you able to independently come up with your own ideas or are you reading social media or the news or some other viewpoint and just parroting what those viewpoints are giving to you. Or can you independently through your own reflection, solitude your own sources that you're reading, can you come up with your own viewpoint? This is a really critical aspect of critical thinking in the age that we live in. Another one is integrity. So if you want to win an argument, are you playing fairly? Are you using tricks or deliberately misinforming people? This isn't meeting critical thinking with integrity, this is using tricks to get someone to buy your view point And really this is something to be avoided. Another one is perseverance. So, do you have the ability to, let's say you know that there is a right solution for something and we can bring this to technical, there is a technical solution, that's the right solution. Do you have the perseverance to methodically go through document why this is the best solution and actually bring it to fruition. A lot of times it's easy to say, well, I'm right, you're wrong and maybe you are right but do you have the ability to go through and keep persevering to make sure that the company or the entity that you're dealing with, will actually go through and completely implement the solution that you've suggested. And finally, a couple last ones are the confidence in reason. So do you have the ability to really have faith in scientific facts, right? Do you have the ability to go through and know that eventually if you can, step by step, prove to people here's the facts, that the reason we'll win is really important, just philosophical viewpoint, and then finally, fair mindedness, right? So are you trying to in good faith except every different piece of criticism or compliment that you receive when you're going through to solve a problem? If you're not really accepting all of the different viewpoints, it could cause problems for management. If you're a manager, it could cause problems in evaluating the best solution. So all of these aspects of critical thinking are really important in a technical sense. They're also important in other aspects of life but this is one of the things that is really a critical component of being good at cloud computing and being good at technology is to use reason and use critical thinking to evaluate all the different solutions. It's really impossible to just blindly accept one pathway. 

### Effective Technical Teamwork

1. Elevating goal
2. Results-driven structure
3. Competent team members
4. Unified commitment
5. Collaborative climate
6. Standards of excellence
7. External support and recognition
8. Principal leadership



### Technical Project Management 

One of the ways you can do this is by building a quarterly schedule that identifies week by week what it is that you'll build. This is a great way to get your ideas out. But basically, in a technical plan for the quarter, you can say week by week what you think will happen. This doesn't mean it will happen, but it gets the ideas flowing and makes you think about what it is that you're going to build.The next thing that I would recommend is to do a weekly demo in your company. It's really easy to get lost in, I need to hit this deadline, and I want to work all night, or you kind of get caught up in the long-term or the short-term. But a cadence of weekly demos is one of the most effective ways to make progress and actually get things done. So if you can't demo every week, you're probably not going to hit your deadline. The other thing that I think is a really key aspect of project management is to look into the word DevOps. So one of the key factors of DevOps is continuous delivery. And it's about being able to always deploy your code, or your code is always in a deployable state. And this also prevents this maybe accident of, there's all these really complex things that I haven't set up. Another key aspect is automated testing. I said this earlier that if it's not automated, it's broken, and that's a really important way to think about testing in your project. 

## AWS Cloud Development

### Makefile

Make file is a recipe for building software and it's a way to make sure that your application runs the same way in any environment and it really simplifies the steps of a software project, really it's a recipe that is available on all Linux systems and you can use it for your advantage.

### Test

Tests ensure that your software works. There's a few different kinds of tests, one kind is functional, this could be, let's say, a test of a command line tool or a web application to high level, to make sure that it works. Another one is integration, there's one piece of software integrated with another, let's say the web front end and the backend. A load test is another one that is a very common form of a test and this would ensure that, let's say, 10,000 users would be able to use your application, this is really critical in the Cloud.

### Linting

In a nutshell, that's really the purpose of linting is that it can catch bugs before they even occur, and you can test it automatically. It also enhances automation and so when you use Linting you can ensure that when you use a GitHub action or build server that is running your code, that the lint step will really ensure a certain level of quality.

### GitHub Actions

It's a SaaS-based build server that's available with GitHub and allows you to do continuous integration and continuous integration, which we'll get into in a little bit, is a form of automated testing. So when you check in your code, this SaaS-based build server will automatically go and test your code and makes it very convenient if you're already using GitHub. 

## Continuous Integration

<img width="672" alt="Screenshot 2023-03-09 175914" src="https://user-images.githubusercontent.com/82685546/224197338-a66e46f3-2e0f-4efc-b095-be4f441603ea.png">

## Continuous Deployment 

<img width="670" alt="Screenshot 2023-03-09 184233" src="https://user-images.githubusercontent.com/82685546/224197324-06e57966-5d30-4bce-8824-f3c46acf7b3a.png">

## Cloud Computing 

1. Types of  cloud computing 
2. SaaS
3. PaaS
4. IaaS
5. MaaS - Run services in bare metal machines
6. Serverless

Infinite computing has infinite upgrades of cpu, ram, gpu, etc for fractions of the cost of buying this equipment with no upfront cost.

## Cloud Economics 

1. Elasticity: Scaling up or down depending of the necessity
2. Availability: Healthy response all the time that you need for the application
3. Self-service: No needed IT for so many problems 
4. Reduced Complexity: Less points of failure and stress for a company.
5. Total cost ownership: Study and reduce costs of IT personel, datacenter, bills, etc.
6. Operational resiliance: Reduce risk of failures dependig where the services work.
7. Business agility: Leveraging the cloud native resources that are constantly being developed, you can focus on really the business core strategy that your companies focused on.

## DevOps

1. Continuous Integration
2. Continuous Delivery
3. Microservices
4. Ingrastructure as a code
5. Monitoring and logging 

### Benefits

- Speed: The development of features, the delivery of software into production, the cycle that people can develop, they can create software faster.
- Delivery: Being able to deliver features, or bug fixes faster directly to your customer is a key benefit
- Reliability: Automating things and making them better, constantly improving things with testing, and monitoring, and logging, you're making your system much more reliable
- Scale: Use Infrastructure as Code to automate the Infrastructure, and also by using smaller micro-services, you're able to scale out into a bigger level
- Collaboration: Shared ownership, everybody works together to have a shared ownership and accountability
- Security: One big problem today with many software applications is leaking data, giving that data to other people accidentally. You can actually implement policy as code, and then you can define and track the compliance at scale.


## Containers 

Deploy it as a service and it's really the simplest possible way to deploy an application. Also with cloud native, there are many cloud managed Kubernetes services that can take care of things.

Docker is a particular product that's composed of both docker desktop and docker hub. There's a GUI that you can control things. It can interface with Kubernetes and you can actually launch clusters and control them inside of docker. Really it's a local development workflow. You can create your own container registry for private development and all the team can pull the images for fast and secure development.

Kubernetes is a powerful orchestration service for containers that allows you to build highly available solutions as well as solutions that can auto-scale and self heal. It started in 2014, and it was developed by Google. It's a useful tool for containerized application. So really, the idea is, it's a container orchestration system.

There are 5 simple steps for this:
1. Create a cluster
2. Deply application
3. Expose ports
4. Autimate scaling
5. Update the application and cluster

<img width="598" alt="Screenshot 2023-03-11 134343" src="https://user-images.githubusercontent.com/82685546/224506165-ae3b9f83-48e2-4632-8c85-1973c35ea1e4.png">

## Microservices 

This services are a small abstaction of a bigger project and have a lot of benefits and could also be serverless.

| **Traits**   | **Benefits** |
|--------------|--------------|
| Small        | Speed        |
| Autonomous   | Simplicity   |
| Specialized  | Map Logic    |
|              | Reliable     |

## Serverless
<img width="642" alt="Screenshot 2023-03-12 094851" src="https://user-images.githubusercontent.com/82685546/224548916-de80d7b0-4d45-4cab-b8cb-edb81c0e1847.png">

**AWS**

- **Lambda:** It is a Function as a service and just process the code that you need, no need to worry about the infrastructure.
- **Step Functions:** Multiple operation in a step by step service.

**GCP**

- **Cloud Run:** Docker container running as a service.
- **Cloud Funtions:** Funtions or code that run when a trigget is met and message an output.




