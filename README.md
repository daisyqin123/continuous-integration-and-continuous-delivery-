# Continuous integration and continuous delivery
## Concept
### CI
+ **Basic concepts**:
Continuous integration integrates code into the trunk frequently.
Each integration is verified through automated construction (including compilation, release, and automated testing) so that integration errors can be found as soon as possible.
+ **Benefits**:
Quickly find errors. Every time a bit update is completed, it will be integrated into the backbone. Errors can be found quickly, and it is easier to locate errors
Prevent the branch from greatly deviating from the trunk.
+ **Purpose**:
Allows products to iterate quickly while maintaining high quality. Its core measure is that the code must pass automated tests before it is integrated into the backbone. If a single test case fails, it cannot be integrated. Continuous integration does not eliminate bugs but makes them very easy to find and correct.
### CD
The full name of CD is Continuous delivery. Continuous delivery is to frequently deliver new versions of the software to the quality team or users for review. If the review passes, the code goes into production.Continuous delivery can be seen as the next step of continuous integration. It emphasizes that no matter how it is updated, software can be delivered anytime, anywhere.

## Tools
+ **GitHub Action**:
GitHub runs  CI tests and provides the results of each test in the pull request, so developer can see whether the change in your branch introduces an error. When all CI tests in a workflow pass, the changes developers pushed are ready to be reviewed by a team member or merged. When a test fails, one of changes may have caused the failure.Using this tool, developers can build, deploy, and update software projects on GitHub or external systems without running the code themselves. Actions adds customizable workflow capabilities to GitHub.com so developers can build and share code Containers to run software development workflows, even across multiple clouds.

**My CI/CD example**:[My continuous integration and continuous delivery example](https://github.com/daisyqin123/continuous-integration-and-continuous-delivery-).
+ **Other tools**:
Jenkins and Azure devops.For Jenkins,it helps us compile and package the code in a unified way, and it can also be released in the tomcat container.
Through configuration, we hand over the previous process of compiling, packaging, uploading, and deploying to Tomcat to Jenkins.
