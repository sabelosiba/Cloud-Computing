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

 
  
</details>

<details>
<summary> Charpter 1 : Defining Data Governance </summary>
<br>
 
  
</details>

<details>
<summary> Charpter 1 : Defining Data Governance </summary>
<br>
 
  
</details>

<details>
<summary> Charpter 1 : Defining Data Governance </summary>
<br>
 
  
</details>
