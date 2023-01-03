# continuous-integration-and-continuous-delivery-
continuous integration and continuous delivery 
CI
1. Basic concepts:
The full name of CI is Continuous integration. It integrates code into the trunk frequently (multiple times a day).
Each integration is verified through automated construction (including compilation, release, and automated testing) so that integration errors can be found as soon as possible.
2. Benefits
Quickly find errors. Every time a bit update is completed, it will be integrated into the backbone. Errors can be found quickly, and it is easier to locate errors
Prevent the branch from greatly deviating from the trunk. If the trunk is not integrated frequently and the trunk is constantly updated, it will make it more difficult to integrate in the future or even difficult to integrate
Release updates faster Continuous integration can help teams release and update programs faster and more aggressively. A large amount of repetitive work can be automatically completed when publishing, saving manpower
3. Purpose
Allows products to iterate quickly while maintaining high quality. Its core measure is that the code must pass automated tests before it is integrated into the backbone. If a single test case fails, it cannot be integrated. Continuous integration does not eliminate bugs but makes them very easy to find and correct.


cd
basic concept:
The full name of CD is Continuous delivery. Continuous delivery is to frequently deliver new versions of the software to the quality team or users for review. If the review passes, the code goes into production.Continuous delivery can be seen as the next step of continuous integration. It emphasizes that no matter how it is updated, software can be delivered anytime, anywhere.

Tools
CI/CD tools should make engineers' lives easier by giving them greater visibility into their pipelines, without burdening them with complicated integrations and plugin maintenance. GitLab CI/CD is designed to be simple so teams can start using it right away.
Why use GitLab
•	Easy to use
GitLab uses a YAML configuration that any developer can understand so developer can build pipelines faster.

•	Cloud native CI/CD
With its built-in container registry and Kubernetes integration, GitLab supports cloud native development.

•	Simple architecture
One integrated application with one set of permissions.

•	Fast and efficient
With autoscaling runners, developers no longer have to wait on builds, and VMs spin up or down automatically to process queues at a lower cost.

•	Everything in one place
GitLab CI/CD is already built into the same application that contains source code management, planning, monitoring, etc.

As a single application for the entire DevOps lifecycle, everything is in one conversation and visible across teams. With GitLab's out-of-the-box CI/CD, the developer can spend less time maintaining and more time creating.
