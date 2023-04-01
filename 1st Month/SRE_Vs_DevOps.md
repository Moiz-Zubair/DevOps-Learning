# What is SRE?
SRE stands for Site Reliability Engineering. In a few words, SRE teams solve operational, scaling, and reliability issues. 

SRE, or Site Reliability Engineering, is a system stability approach that was developed at **Google** in the early 2000s to ensure the smooth functioning of their complex systems handling over 100 billion queries per day. SRE is essentially an operations team designed by software engineers with a focus on system stability. It is measured by the most fundamental characteristic of any product, reliability. The pyramid of reliability elements, from monitoring to reliable product launch, reflects the complexity of achieving a stable system.

## SRE principles
Let’s overview the fundamental principles of SRE:

* Creating CI/CD DevOps processes to automate infrastructure scaling;
* Operational load limit: SRE is only 50% of the routine work. At least 50% should be devoted to improving the system, not to fighting fires;
* The development team must be responsible for at least 5% of the Ops workload. If the load increases due to the developers’ fault, they deal with all unnecessary tasks;
* Creating a Service Level Agreement (SLA), Service Level Objectives (SLO), and Service Level Indicators (SLI) for your services and measuring system performance against them;
* Setting up an error budget to control the rate the changes are introduced into production based on quality;
* Implementing in-depth monitoring to see latency, congestion, traffic, and errors;
* Writing response scripts to address issues based on clear symptom-based alerts. Arranging automated runbooks that comprise each scenario and testing them regularly to keep the team’s skills at a high level;
* Performing flawless autopsies and correcting any errors found;
* Having a common recruitment pool for SRE and engineering teams. Let SRE grow into developers.

# What is DevOps?
DevOps is a set of cultural principles, approaches, and tools that improve the ability of companies to build applications and services at high speed. With DevOps, product development and optimization are faster than traditional software and infrastructure management processes.

Patrick Debois, a Belgian IT consultant, and Agile practitioner invented the term in 2009. Its main principles are similar to those of SRE: applying engineering methods to operational assignments, measurements, and using automation instead of tedious tasks. But its focus is much wider.

## Key Pillars of DevOps:
* No more silos. The idea is based on the fact that the absence of cooperation and information flow between teams decreases performance;
* Failure is okay. DevOps dictate learning from mistakes, and not wasting resources on an unreachable purpose — preclusion all collapses;
* The change must be progressive. Changes are most efficient and less risky when they are tiny and regular. This point in combination with automated testing of small packages of code and rollback of failed ones is at the heart of the concepts of ongoing integration and ongoing delivery (CI/CD);
* The more automation, the better. DevOps concentrates on automation to provide upgrades faster and save hours of monotonous work.
* Metrics are crucial. Every change should be measured to see if it delivers the desired results.

# SRE related to DevOps
SRE and DevOps are not competitors since SRE provides a hands-on approach to solving most DevOps problems. Now, let’s take a look at the way teams use SRE to implement DevOps principles and philosophy: 

1. Using Instruments and Automation:
Both DevOps and SRE use automation to make better processes and service delivery. While DevOps encourages the adoption of automation tools, SRE guarantees that every team member can access updated automation instruments and technologies. SRE allows teams to share the same tools and services through scalable application programming interfaces (APIs).

2. Implement Incremental Changes
DevOps involves slow, incremental changes to ensure continuous improvement. SRE supports this by letting teams perform small, frequent updates that decrease the changes’ influence on application availability and stability.

3. Reducing Organizational Silos
The DevOps task ensures that different software development departments/teams work harmoniously on a common goal. SRE achieves this by sharing ownership of projects between teams. With SRE, every team uses the same instruments, methods, and codebase to support uniformity and smooth cooperation.

Summing up, both can be viewed as leveraged resources. There is no 1:1 ratio in DevOps vs. software engineers or site reliability engineers. O’Reilly’s Building Safe and Reliable Systems compared to the first edition of the Google SRE book discusses the command structure that poisons SREs as consultants/experts. Creating solutions at scale requires specialized engineers to help solve issues and expand opportunities. DevOps engineers, SREs, and other experts such as application security engineers fall into specialized consultants. Google, in its SRE book, describes all the experience in several areas required to deploy and support a product like Gmail.

# SRE vs. DevOps
Both approaches enable minimal separation between development and operations teams. But we can summarize the main distinction as follows: DevOps concentrates more on cultural and philosophical shifts, while SRE is more pragmatic and practical.

In the table below, we highlighted the key distinctions in the way the concepts operate:

|   Criteria	| SRE	| DevOps|
|---|---|---|
|   Nature      |SRE was created with a concrete purpose: to build a set of methods and metrics to improve cooperation and service delivery.| DevOps is a set of philosophies that enable cultural thinking and collaboration across disparate teams.|
|   Goal        |SRE includes prescriptive ways to achieve reliability.| DevOps works like a template that guides collaboration to bridge the gap between development and operations.|
|   Focus       |SRE’s responsibility is primarily focused on improving the availability and reliability of the system.|DevOps focuses on the rapidity of development and delivery while ensuring continuity.|
|   Team structure |The team consists of site reliability engineers who have both operational and development experience.|The DevOps team includes testers, programmers, engineers, SREs, and more.|

[!SRE Vs DevOps](https://jelvix.com/wp-content/uploads/2022/04/sre-devops-diff-966x831.png)