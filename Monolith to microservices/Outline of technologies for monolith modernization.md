### Synopsis

An existing Java EE application designed for a retail webshop. The current version of the webshop is a Java EE application built for Oracle Weblogic Application Server. As part of a modernization strategy you’ve decided to move this application to JBoss EAP, containerize it, and run it on a Kubernetes platform with OpenShift.

#### Red Hat OpenShift 
You’ll use one or more projects (Kubernetes namespaces) that are your own and are isolated from other workshop students.<br>
https://www.redhat.com/en/technologies/cloud-computing/openshift

#### Red Hat CodeReady Workspaces
Based on Eclipse Che, it’s a cloud-based, in-browser IDE (similar to IntelliJ IDEA, VSCode, Eclipse IDE). You’ve been provisioned your own personal workspace for use with this workshop. You’ll write, test, and deploy code from here.<br>
https://developers.redhat.com/products/openshift-dev-spaces/overview

#### Red Hat Application Migration Toolkit 
You’ll use this to migrate an existing application<br>
https://developers.redhat.com/products/mta/overview

#### Red Hat Runtimes
A collection of cloud-native runtimes like Spring Boot, Node.js, and Quarkus<br>
https://www.redhat.com/en/products/runtimes

#### Red Hat AMQ Streams 
Streaming data platform based on Apache Kafka<br>
https://www.redhat.com/en/technologies/jboss-middleware/amq

#### Red Hat SSO 
For authentication / authorization - based on Keycloak<br>
https://access.redhat.com/products/red-hat-single-sign-on

#### Other open source projects like Knative (for serverless apps), Jenkins and Tekton (CI/CD pipelines), Prometheus and Grafana (monitoring apps).
https://knative.dev/docs/<br>
https://www.jenkins.io/<br>
https://cloud.google.com/tekton/<br>
https://prometheus.io/<br>
https://grafana.com/<br>

#### Migration Toolkit for Applications (MTA) 
An extensible and customizable rule-based tool that helps simplify migration of Java applications.

It is used by organizations for:
<ul>
    <li>Planning and work estimation
    <li>Identifying migration issues and providing solutions
    <li>Detailed reporting
    <li>Built-in rules and migration paths
    <li>Rule extensibility and customization
    <li>Ability to analyze source code or application archives
</ul>

Read more about it in the MTA documentation<br>
https://access.redhat.com/documentation/en-us/migration_toolkit_for_applications/5.3

#### Quarkus
Quarkus is a Kubernetes-native Java framework tailored for JVM and native compilation, crafted from best-of-breed Java libraries and standards. Quarkus provides an effective solution for running Java applications that deal in serverless, microservices, containers, Kubernetes, FaaS, or the cloud because it has been designed with these in mind.<br>
https://access.redhat.com/products/quarkus

You will create the catalog service and the catalog service will call the inventory service. When you are ready, you will change the route to tie the UI calls to new service.

To implement this, we are going to use Red Hat support for Spring Boot. The reason for using Spring for this service is to introduce you to Spring Boot development, and how Red Hat Runtimes helps to make Spring development on Kubernetes easy. In real life, the reason for choosing Spring Boot vs. others mostly depends on personal preferences, like existing knowledge, etc. At the core, Spring and Java EE are very similar.<br>
https://access.redhat.com/products/spring-boot<br>
https://www.redhat.com/en/products/runtimes
