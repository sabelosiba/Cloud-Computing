 # Cloud-Computing


<details>
<summary> Charpter 1 : Cloud Computing </summary>
<br>

## Understanding the cloud
### What is the cloud?
- The cloud is a global network of servers around the world acting as one massive hard drive.
- The five characteristics for basic understanding of what cloud computing means:
  1. On demand self-service - Users of cloud services can set up and use services whenever they need them, without having to directly contact the cloud service provider.
  2. Broad network access - Devices like computers and regular server setups can connect to resources stored in the cloud through the network.
  3. Resource pooling - The cloud service provider combines resources for multiple users and adjusts how much each user gets whenever they need it.
  4. Rapid Elasticity - In cloud computing, resources are adjusted based on changes in demand.
  5. Measured service - Cloud service providers keep track of how much resources users use, control it, and charge users accordingly.

### Cloud computing ecosystem
- The ecosystem 3 categories :
  - Consumers of services - everyday end-users that use cloud services in day-to-day business activities. e.g. Microsoft OneDrive, Google Drive and iCloud
  - Provider of services - cloud providers offer a variety of functions ranging from infrastructure services to applications and tools. e.g. Amazon Web System (AWS), Microsoft Azure, Google Cloud Platform (GCP) and IBM Cloud.
  - Designer of services - companies build applications and tools. e.g. Accenture, Deloitte, IBM and PricewaterhouseCoopers (PwC).
 
### Understanding cloud concepts
- *Cloud computing* offers shared resources like applications, storage, and networking over the internet.
- *Standardization* means using consistent methods and interfaces to provide services.
- Cloud services rely on *automation* to carry out tasks based on rules, resource availability, and security needs. This automation is crucial for allowing users to provision services themselves and for efficiently managing resources.
  
## Understanding cloud deployment models
### Cloud components and clients
- In a cloud services setup, there are three main parts:
  - the device you use to access the cloud,
  - the place where the cloud services are stored (data center),
  - and the connection that links them together.
 
  ![image](https://github.com/sabelosiba/Cloud-Computing/assets/88839789/4b2615d5-dd25-4bfc-84c3-ae8800ea9db5)

  - Leading cloud service providers like Microsoft and Amazon have extensive networks of data centers worldwide. These centers are built with redundancy to ensure reliable power, internet connectivity, and physical security.
  - Cloud services are used by individuals and businesses across different platforms. They include storage, email, e-commerce, office tools, and development environments. Users can access these services from devices like phones, tablets, computers, IoT devices, and servers, running on operating systems like Windows, macOS, Linux, iOS, and Android.
 
- 

- Cloud infrastructure can be managed in different ways:

  1. Public Cloud: A cloud service provider (CSP) owns and manages the cloud resources, serving multiple external customers who share these resources.
  2. Private Cloud: Services are exclusively provided to a single organization, which owns and manages its own cloud infrastructure.
  3. Hybrid Cloud: This combines elements of both public and private clouds. Organizations can use a mix of their own private cloud resources and public cloud services from CSPs, or even community cloud deployments, which are shared among organizations with common interests or requirements.

![image](https://github.com/sabelosiba/Cloud-Computing/assets/88839789/eaac594a-df1d-44c9-bb12-90254675fdb9)
- Imagine a company toolbox with many different tools, each being really good for a specific job. A multicloud environment is like that toolbox, but instead of physical tools, it has different cloud services from various companies.
- This way, different teams in the company can pick the best service for their needs, and the company itself has more choices and flexibility.

## Cloud Delivery Models
- Imagine you're renting an apartment (the cloud service). Here's what you get with each option:
  
### Infrastructure as a Service (IaaS)
- You rent the bare space (hardware) and plumbing (networking). You're responsible for everything else, like furniture (operating system), appliances (applications), and decorations (data).
- There are two options:
  - Public IaaS: This is like renting a computer from a company like Amazon or Microsoft. You pay as you go and can easily scale up or down your resources (like renting a computer by the hour and adding more RAM if needed).
  - Private IaaS: This is like having your own internal IT department create a computer system for you to use within your company. You might have more control but less flexibility.

- IaaS examples: AWS EC2, Microsoft Azure, Rackspace, Digital Ocean
- Target audience: IT administrators
- IaaS is a good option for IT professionals who want to build their own custom systems on a rented infrastructure.

### Platform as a Service
- You rent a furnished apartment (pre-configured hardware and software). You can move your furniture in (applications) and decorate (data), but you can't change the layout (operating system).
- PaaS is a good option for developers who want to quickly build and deploy applications without worrying about the underlying infrastructure.
- PaaS examples: Google App Engine, Heroku, AWS ElasticBeanstalk, Salesforce
- Target audience: Developers, DBAs

### Software as a Service
- With SaaS, you access the software over the internet, like using Gmail or Netflix.
- You don't need to install or maintain the software yourself - the provider takes care of everything.
- You typically pay a monthly or yearly subscription fee per user.
- SaaS applications are great for everyday tasks like email, document editing, or project management.

- SaaS examples: Microsoft Office 365, Google Apps, WebEx, Dropbox, Netflix
- Target audience: End users

Think of it this way:
- IaaS is like renting a computer.
- PaaS is like renting a computer with pre-installed software for development.
- SaaS is like renting software that's ready to use, like renting a car instead of buying and maintaining one yourself.

## The Computing Resources Life Cycle
### Understanding Self-Service Provisioning and Elasticity
- Cloud users can use a website online to pick and buy cloud services, set them up, and start using them in the cloud.
- Elasticity means that when cloud resources are nearing their capacity, they can increase their size automatically without manual intervention.

### Establishing a Dynamic Life Cycle across Workloads and Data
- The cloud isn't one giant computer, but a collection of resources spread out across different locations.
- Think of it like a team, where each member (workload) has a specific job.
- Some jobs need to stay in-house (private cloud) for now, while others can be outsourced (public cloud).
- The best strategy uses a mix of both (multicloud) to find the perfect fit for each job.
- This way, data and tasks can move around to different cloud providers or locations depending on what's needed.
- It's important to consider factors like customer location, workload growth, and even switching cloud providers to get the best performance and value.

### Management Services
- No matter how you set up your cloud (private, public, or mixed), you need management services to keep things running smoothly for everyone using it (customers, employees, partners).
- These services include monitoring the network, applications, and security to make sure everything is working well and to catch any problems before they happen.

## The Changing Role of the Data Center
- Even with hybrid clouds, data centers aren't disappearing:
  - Many companies rely on them for core functions like accounting and inventory.
  - These data centers are often complex and expensive to maintain.
  - Virtualization has helped improve efficiency, but cloud computing offers more possibilities.
  - Companies are re-evaluating their data center use in light of cloud options.
  - The best approach considers both traditional data centers and various cloud environments.
 
### Evolution of the Data Centre into a Private Cloud
- It organizations found its more effiecient and eefective to creare private cloud services for developers to create new applications andservices.

</details>



<details>
<summary> Charpter 2 : Embracing the Business Imperative </summary>
<br>

## Escaping the IT Legacy Trap


## Preparing for cloud

## Building for Innovation
- The cloud is like a bridge that connects companies with their partners, suppliers, and customers. This is important because success depends on good communication and working together.
  - Benefits of better connections:
    - Supply chains work smoother when everyone shares information.
    - Companies can quickly test new ideas with partners without spending a lot of money.
  - The cloud makes connections easier:
    - Standard tools (APIs) help connect different systems together.
    - Companies don't need to build everything from scratch anymore.

## The business imperatives
- The business world used to move slowly, with companies building systems that lasted for years. Now, things are different because of the cloud:
  - Startups can use cloud services to quickly build new features and compete with established businesses.
  - Established businesses need to keep their technology up-to-date (cloud strategy) to avoid losing customers to these quicker competitors.
  - This means working together across the company to decide what to move to the cloud and what to keep in-house.
 
## Optimizing your existing business

## Morden development and deployment strategies
- Established businesses need a new approach to software development to keep up with the fast-paced cloud world. Here's what they can do:
  - DevOps: This combines development and deployment into one thing.
    Focus on customer needs: Develop features that customers actually want and can use easily.
  - Be flexible: Make applications that can adapt to change and work with other businesses' tools.
  - Fast updates: Release new features quickly, not just in big batches every few months.

## 
</details>

<details>
<summary> Charpter 3 : Cloud architecture considerations </summary>
<br>

## Type of constituents 
- Two constituents that are part of cloud ecosystem :
  - Cloud consumers use services offered by others (like renting computing power). They just need to pick the right service and connect it to what they need.
  - Cloud service providers create and offer cloud services (like your company offering a photo storage app). They need to design the entire system and make sure it works well for all their customers.

- The NIST Cloud Reference Model illustrates how these different cloud services and users fit together to support businesses. It shows that both cloud consumers and cloud service providers are crucial parts of the cloud ecosystem. The model emphasizes the importance of managing and orchestrating services so they work together seamlessly, whether they're used internally or provided commercially to customers.

## Planning for deployment

## Navigating the choices in a hybrid world
- The best cloud strategy uses a mix of different services (hybrid cloud) to fit your specific needs. Here's how to choose:
  - Think about your business needs first. What features are most important (speed, uptime, ease of use)?
  - Match those needs to the cloud service. Some services are better for specific needs. For instance, if you need super-fast performance, you might choose a private cloud service.
  - Consider how different services will work together. Some services need to connect with each other, while others can be separate.
  - The goal is to create a system that perfectly fits your customer needs.
 
## Optimizing for workloads
- One of the key ideas behind hybrid cloud design is being able to move jobs (workloads) around to different places (environments). This helps make sure everything runs smoothly for your customers. Here's how it works:
  - Different cloud environments (public, private) need to be able to talk to each other (federation). This is like having a common language between different computer systems.
  -Even if they aren't directly connected, there needs to be a way to easily access data and services across these different cloud locations. This way, jobs can be moved around to wherever they work best.

## Supporting a dynamic life cycle
- The cloud is different from traditional computer systems because it's designed to be flexible and constantly changing. Here's how:
  - Focus on services, not separate tools: The cloud treats everything like services that can be connected together. This makes it easier to build and change applications.
  - Designed for change: The cloud can handle growing numbers of users, new applications, and different workloads.
  - Faster development and deployment: By connecting development and deployment in the cloud, things can move quicker and smoother.
  - Easier to add new features or users: Adding more capacity or users (like through an acquisition) is simpler in the cloud.
  - Security as a service: Security updates and changes are easier to manage in the cloud.
- To take advantage of this flexibility, consider these things when planning your cloud environment:
  - Break down separate systems into services: This makes it easier to connect them and make changes.
  - Avoid creating connections that limit future options: Keep things flexible so you can add new cloud services later.
  - Focus on performance for a good customer experience: Make sure everything runs well for the people using your cloud applications.
  - Create a secure and reliable environment: Your cloud system should be safe and stable in the long run.


</details>

<details>
<summary> Charpter 4 : Managing a Hybrid and Multicloud Environment </summary>
<br>

## Managing SaaS Aplicatrions
- Businesses are using more and more software from the internet (SaaS) but this can be a challenge for IT departments to manage. Here's why:
  - Easy to sign up for: Anyone can start using a SaaS application, even if it's not the best choice for the company. This can lead to security risks and a lack of control.
  - Not all SaaS applications are created equal: Some are designed for businesses and offer features for IT to track and manage their use. Others are simpler and might not be secure or connect well with other systems.
- For these reasons, it's important for IT to have some oversight over SaaS applications:
  - Shadow IT: In the past, business units might have used software without IT knowing (shadow IT). The cloud makes this easier to do.
  - Working together: The best solution is for IT and business units to work together. IT can create a "library" of approved SaaS applications that are secure and meet business needs.
  - Employee self-service: Employees can then choose the tools they need from this library, instead of finding their own.
- Even though IT departments aren't responsible for fixing SaaS application outages, they are still on the hook for making sure users have a good experience. Here's why:
  - Users don't care who's responsible: If a SaaS application goes down, users will blame IT regardless of who caused the problem.
  - IT as the advocate: IT's job is to act on behalf of the users and work with the SaaS vendor to get the problem fixed quickly.
- Cloud Access Management (CAM) is like a gatekeeper for your cloud applications. It helps control who can access what, and how:
  - Permissions for users: CAM can give specific users access to certain applications, and limit access to others.
  - Data access control: CAM can also control what information users can see within those applications. For example, in an HR app, CAM could allow employees to see their own information, but not other people's.
  - Benefits for IT:
    - IT can track which apps are being used and by how many people. This helps them negotiate better deals with vendors.
    - IT can also see if there are opportunities to improve by using different tools or integrating existing ones.

## Managing Ecternal cloud resources
- Businesses use a lot of different cloud resources, like virtual machines, storage, and databases. These resources need to be managed carefully.Here's how:
  - Who's responsible? The development or IT team is usually in charge of managing cloud resources. They know what's needed to build the applications the company uses.
  - Visibility and control: Just like with SaaS applications, it's important to be able to see and control how cloud resources are being used.
  - Choosing the right resources: It's important to pick the best cloud resources for the job. Once you've chosen one and invested time in learning it, you shouldn't switch to something else unless absolutely necessary.
  - The process: There's a general process for choosing, testing, and using cloud resources:
    1. Figure out what your application needs.
    2. Look for matching resources from cloud providers your company already uses. If nothing works, look at other providers.
    3. Test the resources to make sure they work well.
    4. If the tests go well, get a license to use the resource.
    5. Teach everyone who needs to know about the new resource.
    6. Regularly review the resources you're using to make sure they're still the best choice.
- Self-service: The ideal situation is to have a catalog of approved resources that developers can choose from. This makes it easier for them to find what they need and reduces the risk of them using unapproved resources. The key is to make sure this catalog is up-to-date and has everything developers need.

## Service level agreeements (SLAs)
- Cloud services come with agreements called SLAs (Service Level Agreements) that say what the service provider will do and what you,the customer, are responsible for. These agreements cover things like how available the service will be, how fast it will respond, and how secure it will be.
  - SLAs don't cover everything: The provider might not be responsible for outages caused by things like floods or problems with other companies' equipment.
  - SLAs may not cover everything you lose: An SLA might just give you money back for the time the service was down, but it might not cover lost business. You might need separate insurance for that.
 
### Addressing poor cloud and computing behaviors
- Even though cloud providers try to make their systems secure, people can still do things that put information at risk. Here are a few examples:
  - Weak passwords: Using passwords that are easy to guess makes it easier for hackers to steal information or damage systems.
  - Unsecured personal devices: Using personal devices for work can be risky if they are not properly secured.
  - Sharing information on social media

## Managing internal cloud resources

## Managing a hydrid cloud environment
- Businesses are using a mix of private (controlled by the company) and public clouds for their internal needs. This gives them more flexibility, scalability, and performance.
- Even though public clouds are secure, companies with private or hybrid clouds might have even stricter security requirements. This means carefully choosing and approving resources.
- In a private or hybrid cloud, companies can create a "self-service" library of approved resources that employees can easily access for their work. These resources will be secure and meet the company's specific needs.

### Understanding the role of internal SLAs
- SLAs (Service Level Agreements):
  - SLAs are agreements that define what level of service (performance, uptime, etc.) users can expect from cloud resources. Having clear SLAs helps avoid confusion and ensures everyone is on the same page.
  - Who's responsible for monitoring SLAs depends on whether you're using a public or private cloud:
    - Public cloud: The public cloud provider is responsible, but they might have many customers and take longer to respond to issues.
    - Private cloud: The company's IT department is responsible for monitoring SLAs since they are the "cloud provider" for their own employees.

## Managing Internal Services
- Users and Expectations:
  - Businesses are moving more applications to the cloud (private, public, or hybrid).
  - Users don't care where the applications run, they just expect them to be reliable, secure, and well-supported, just like any other business application.

### Supporting cloud costomers
- Support for these cloud applications can come from the IT department or a company call center.
- Whoever provides support needs to have easy access to the cloud environment to diagnose and fix problems quickly.
- For applications developed in-house, the development team should work closely with the support team to create user-friendly applications with fewer problems.
- This can help reduce the number of support calls.

### Monitoring Resources imported from Public Cloud
- If you're using a hybrid cloud (mix of private and public cloud), you need to monitor the performance of the public cloud resources you're using.
- There are a few ways to do this:
  - Run test software: You can run test software in the public cloud to see how well the resources perform. This might not perfectly reflect how your applications will perform, but it can give you a general idea.
  - Monitor resource dashboards: If the public cloud resources you're using have dashboards or other monitoring tools, you can use those to track performance.
  - Monitor the applications themselves: The most accurate way to monitor performance is to track how the resources are actually performing within your applications. This can be done with minimal impact on the application's performance.
 
## Monitoring apllications and services
- Cloud applications can collect a lot of data about how users interact with them. This data is useful for different teams:
  - Support: Support staff can use this data to see what users are doing and identify common problems. This helps them give better advice to users who call for help.
  - Development and IT: This data can help developers and IT staff find bugs, improve the user interface, and make the application run more smoothly.
 
 - All this data can be overwhelming, so businesses often create dashboards. Dashboards are like visual summaries that show key information in an easy-to-understand way. Different dashboards can be created for different teams, showing them the data they care about most.

## Managing external services
- Multiple services:
  - storing rarely used data
  - Others might be complex applications you develop and run in the public cloud.

### DevOps and Deployment to Public Clouds:
- DevOps is a popular approach to developing software for the cloud. It combines development and operations teams for faster development and deployment.
- This also helps create more robust applications because developers are more involved in how the application runs.
- Once deployed, DevOps engineers continue to monitor the application and can quickly fix problems or redeploy the application with updates.

### Monitoring External Systems (For Applications Used by Other Companies):
- Since you can't easily ask external customers questions about how your application is working, it's even more important to monitor its performance.
- You also need to keep external customers informed about any issues, since they may be less patient with problems than internal users.

### Building Public Cloud Applications:
- Public cloud applications need to be extra reliable and available, because there's less tolerance for outages and problems. Here are some things to consider:
  - Upgrades: Upgrades should be done without taking the application offline and interrupting users.
  - Failovers: The application should be designed to handle failures with minimal disruption to users. Data loss should be avoided completely.
 
 ## The future of multicloud management

</details>

<details>
<summary> Charpter 5 : Standards in a multicloud world </summary>
<br>

 ## What are standards?
 - Standards are like agreed-upon ways of doing things. They are important because they:
   - Allow different systems to work together smoothly.
   - Reduce costs by creating competition between different vendors.
   - Give users more choices.
 - Standards also help with security and prevent vendor lock-in (being stuck with one provider).

### Evolution of standards
- Standards can be created by different groups:
  - International organizations (ISO) - These take a long time to create standards but are very official.
  - Industry consortiums (The Apache Software Foundation) - These are groups of companies that work together to create standards for specific industries.
  - Ad hoc groups (open-source projects) - These are less formal groups that can create standards quickly but may not be as widely accepted.
  - De facto standards - These become standards simply because they are widely used.
 
## Categories of cloud-related standards

## The impact of standards on the multicloud
- Multicloud security: Standards help reduce security risks in complex, multicloud environments where data and applications are spread across different providers.
- Flexibility: Standards allow you to easily move your cloud resources (applications, data) between different cloud providers. This gives you more flexibility and avoids vendor lock-in (being stuck with one provider).
- Integration: Standards make it easier to connect your on-premises data center with private and public cloud environments. This saves time and money compared to dealing with proprietary systems from each cloud provider.
- Choice: By avoiding vendor lock-in, standards give you more choices when selecting cloud providers.
</details>

<details>
<summary> Charpter 6 : Cloud services </summary>
<br>

## The Importance of modularity
- Cloud applications should be built from independent, self-contained pieces (like building blocks) rather than one giant program.
- Benefits of modularity:
  - Easier to develop and update by small teams
  - More flexible, cost and scalable
  - Easier to move between different cloud providers
- These modular pieces are called "services" and they can be reused in different applications.
- Organizations aiming for robust, flexible systems and faster deployment are adopting a service-oriented mindset. This shift is crucial for leveraging Platform as a Service (PaaS) environments, where applications interact primarily through services.
- Containerizing applications has led to simpler ways to manage workloads in PaaS setups. This includes handling APIs more effectively, which are key for defining and accessing services within applications.
- Standardization is key: Since cloud services can run on different cloud providers, there needs to be some consistency across them.
- Cloud native is best: The best cloud applications are designed specifically for the cloud environment to take full advantage of its flexibility, agility and modularity.

 ## Explaining microservices
 - cloud-enable appliacations are designed:
   - modular, distributed, deployed and and managed automatically.
 - Microservices are tiny, independent programs that each perform a specific task within a larger application.
- Think of them as specialized tools in a toolbox, each with a specific job.
-Microservices communicate with each other using clear instructions (APIs).
- Benefits of microservices:
  - Faster development: Smaller teams can work on microservices independently.
  - Easier updates: Changes to one microservice won't affect others.
  - Scalability: You can easily add or remove microservices as needed.
  - Reusable code: Microservices can be used in different applications.

 ### The imperative to manage microservices
 - Microservices are designed to be packaged in containers, which abstract applications from their operating environments. Orchestration services manage these containers, handling both the processes and logic, as well as data services. They decide how and where logic is deployed and managed, reducing concerns about versioning and application-specific configurations.


## Containers
- Docker, CRI-O, Containerd, and frakti are four of the most common container run times.
- It holds everything an application needs to run (code, libraries, settings).
- This "container" can be shipped anywhere (different cloud providers, computers) and still work the same way.
- container runtimes package up your code along with everything it needs to run (like libraries, settings). This is called encapsulation.
- Benefits for developers:
  - No more worrying about different computer setups or configurations.
  - Code written on a laptop will run the same way in the cloud.
  - Developers can focus on writing the application itself, not wrestling with different environments.
  - Container runtimes (like Docker) are the tools that manage these "containers."

## Defining cloud native applications
- Cloud-native applications approach:
  - Microservices: They are built from tiny, independent programs that each perform a specific task.
  - Containers: Each microservice is packaged in a container, like a shipping container, that holds everything it needs to run. This makes them portable and easy to move around.
  - Orchestration: A tool manages all the microservices, making sure they work together smoothly.
  - Continuous delivery: Updates to the application can be made frequently and automatically.
- The idea of cloud native was codified by The Cloud Native Computing Foundation (CNCF), an organization founded in 2015 under the auspices of the Linux Foundation.
- The CNCF definition of cloud native:
  - Containerized: The application is broken down into small, independent pieces that are easy to move around.
  - Dynamically managed: These pieces can be easily started, stopped, and scaled up or down as needed.
  - Microservices-oriented: The application is built from small, independent services that work together.

- Virtual Machines (VMs):
  - These were the original way to create cloud services. They act like separate computers running on a single system, but they can be slow and complex to manage.
- Cloud-native applications are the future of cloud computing. They are faster, more flexible, and easier to manage than traditional virtual machines.

### Differentiating Cloud native applications
- Beyond cost savings: While saving money is nice, cloud-native applications are about more than just that. They help businesses:
  - Build applications faster: Get new features and functionality to customers quicker.
  - Be more competitive: Offer unique value propositions to stand out from the competition.
- Resilient and predictable: Cloud-native applications are built to handle changes and unexpected situations.
- Scalable and performant: They can easily grow or shrink as needed and run smoothly.
- Easier to develop and deploy: Developers can focus on writing the application itself, not wrestling with the underlying infrastructure.
- Automatic and self-balancing: Cloud-native applications can manage their own resources and prevent outages.

## Communicationg using APIs
- Microservices need to talk to each other: Just like people working together need to communicate, different parts of a cloud application (microservices) need a way to talk to each other.
- APIs are the language: APIs are like a common language that microservices can use to exchange information and work together.
- APIs in different cloud layers:
  - They are used to connect applications and resources within a single cloud provider (IaaS and SaaS).
  - They are even more important in connecting applications across different cloud providers (multicloud).
 
 - Think of APIs like Lego instructions: Just like Legos have instructions that tell you how to put the pieces together, APIs tell microservices how to communicate and exchange information.
- Google Maps publishes an API that allows organizations to embed a Google Map into their own web and mobile applications or onto a website.


## Setting the stage for cloud-Enables applications
- 
</details>








<details>
<summary> Charpter 1 : Defining Data Governance </summary>
<br>
 
  Chapter 1: Cloud Computing

    Can you explain the difference between the three main cloud deployment models (IaaS, PaaS, SaaS) and give an example of when you might use each one?
    What are some of the benefits of using cloud computing for businesses?
    How can companies ensure they are choosing a secure and reliable cloud provider?

Chapter 2: Embracing the Business Imperative

    Why is it important for businesses to consider a cloud strategy in today's world?
    What are some of the challenges that businesses might face when migrating to the cloud?
    How can businesses ensure that their cloud strategy aligns with their overall business goals?

Chapter 3: Cloud Architecture Considerations

    What are some of the key factors to consider when designing a hybrid cloud architecture?
    How can businesses ensure that their cloud applications are flexible and scalable to meet changing needs?
    What are some of the security considerations that businesses need to address when using cloud computing?

Chapter 4: Managing a Hybrid and Multicloud Environment

    How can businesses ensure that they are effectively managing their SaaS applications?
    What are some of the challenges associated with monitoring and managing resources in a hybrid cloud environment?
    How can businesses ensure that their cloud deployments meet the required service levels (SLAs)?

Chapter 5: Standards in a Multicloud World

    Why are standards important for cloud computing, especially in a multicloud environment?
    What are some of the different types of cloud standards, and who creates them?
    How can standards help businesses avoid vendor lock-in and increase their flexibility in the cloud?

Chapter 6: Cloud Services

    What are the benefits of building cloud-native applications using microservices and containers?
    How do APIs play a role in communication between different parts of a cloud application?
    What are some of the key characteristics that differentiate cloud-native applications from traditional virtual machines?
</details>
