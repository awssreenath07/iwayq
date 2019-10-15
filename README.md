# PROJECT DESCRIPTION #
#Comment added
#new comment added 

DevOps  project explains complete CI/CD pipeline view to  deploy  code  changes into tomcat container.

1. Continuous Integration
2. Continuous Deployment


### PRE-REQUISITES ###

Ensure below servers are already  setup

1. Jenkins Server
    Install Jenkins, Java, Apache Maven
2. Apache Tomcat
    Install Apache Tomcat, Java
3. Developer box
    Install Git
4. BitBucket Repository
    Create Bit Bucket Repository and keep  credentials ready

### STEPS  ### 
 
1. Configure Build Job
2. Configure Deploy Job
3. Install  required Jenkins Plugins
4. Create pipeline 

### HOW TO TEST PIPELINE ###
1. Commit  code changes to the Bit Bucket Repository 
2. Expecting that Jenkins trigger pipeline and  deploy WAR artifacts to apache tomcat container.

