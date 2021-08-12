
The main aim of this document is to implement CI (Continuous Integration) process.

**Requirments**:

*OS*: Linux / Ubuntu

*Java*: JDK1.8 or higher versions

*Cloud*: AWS

*Code Repository tool*: GitHub (server not required)

*Build Tool*: Maven (separate server is not required, will install it on Jenkins server)

*Repository Manager*: Nexus (server required - t2.micro - no cost)

*Code Quality Analysis*: SonarQube (server required - t2.medium - mimimum 4GB RAM required - it will cost around 8 to 10 INR per hour)

*CICD tools*: Jenkins (server required - t2.micro - no cost)


### Follow the below step by step process to implement CI (continuous integration) process.

**Step-1**: Create an account with https://github.com/ and push your maven/java projects to GitHub.

    Sample projects:
      Utility JAR projects: 
          https://github.com/CalculatorApps/Addition.git (branch: master)
          
          https://github.com/CalculatorApps/CalcMultiModule.git (branch: master)
          
      Web application: https://github.com/venkatasykam/DevOpsWebApp.git (branch: web)
      
      Enterprise application: https://github.com/venkatasykam/DevOpsWebApp.git (branch: ear-jboss)

**Step-2**: Install and Setup the repo manager too **Nexus** using the [document](https://github.com/DevOpsOnlineTraining-2021/Nexus/blob/master/1.Nexus-installation-with-docker.md)

**Step-3**: Install and Setup the code quality analysis tool **SonarQube** using the [document](https://github.com/DevOpsOnlineTraining-2021/Sonar/blob/main/1.sonar-setup-using-docker.md)

**Step-4**: Install and Setup the CICD tool **Jenkins** using the [document](https://github.com/DevOpsOnlineTraining-2021/Sonar/blob/main/1.sonar-setup-using-docker.md)
