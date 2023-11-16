## **Documentation for Project 14**

### Configuring our Ansible Project For Jenkins Deployment using Blue Ocean Jenkins Plugin

### Jenkins Blue Ocean Plugin Installation

![Blue-Ocean-Installation](./Images/blue-ocean-jenkins-plugin-installation-success.png)

![Blue-Ocean-Installation-success](./Images/jenkins-blue-ocean-for-pipeline-creation.png)

### Setting up a deploy Directory in our Ansible Project and creating a jenkins file in it which will be used by jenkins for building our project

![setting-up-a-deploy-directory](./Images/setting-up-a-deploy-directory.png)

### Inserting our Shell script code snippet into our Jenkins file to Trigger our build process

![Code-snippet](./Images/build-stage-code-snippet.png)

### Specifying the Location of our Jenkins file under our Project config on Jenkins

![specifying-Jenkinsfile-location](./Images/specifying-Jenkinsfile-location.png)

### First successful Build

![specifying-Jenkinsfile-location](./Images/first-successful-build.png)

### Our Pipeline CI Environment build Console Output

![console-output-1](./Images/console-output-1.png)
![console-output-2](./Images/console-output-2.png)
![console-output-3](./Images/console-output-3.png)

### Triggering Build for a Multibranch Pipeline

### Creating a new Git Branch under our Ansible Config Project

![new-branch-created-for-our-pipeline](./Images/new-branch-created-for-our-pipeline.png)

### Creating a new Git Branch under our Ansible Config Project

![new-branch-created-for-our-pipeline](./Images/new-branch-created-for-our-pipeline.png)

### New Stage Added to our pipeline build script

![new-branch-created-for-our-pipeline](./Images/new-stage-added-to-build-script.png)

### Pushing our Changes to github

![pushing-changes-to-github-branch](./Images/pushing-changes-to-github-branch.png)

### Scanning our Repository on Jenkins and Launching a new build for the new stage(Test) in our Jenkins file script

![new-branch-active](./Images/new-branch-active-on-Jenkins.png)

### New stage (Test) successful build

![new-branch-active](./Images/test-stage-successful-build.png)

### Quick Task Execution

### Pulling the latest change to main branch
![pulling-our-change-to-main](./Images/pulling-our-change-to-main-branch.png)

### New git branch Created for new stages

![new-branch-created-for-new-stages](./Images/new-branch-created-for-new-stages.png)

### New stages updated in Jenkinsfile build script

![Jenkinsfile-build-script-updated](./Images/Jenkinsfile-build-script-updated-with-new-stages.png)

### Changes pushed to github Branch

![pushing-changes-for-P-D-C-stages-to-github-branch](./Images/pushing-changes-for-P-D-C-stages-to-github-branch.png)

### Scanning our Repository on Jenkins to Launch a new build for our new stages (package, deploy and cleanup) in our Jenkins file script on a new Branch

![repository-scanned-for-new-branch-updated-with-new-stages](./Images/repository-scanned-for-new-branch.png)

### Successful Pipeline build for our stages in blue Ocean (Stage view in Blue Ocean)

![stage-view-in-blue-ocean](./Images/stage-view-in-blue-ocean.png)

### Successful Pipeline build for our stages in Jenkins (Stage view in Jenkins)

![stage-view-in-Jenkins](./Images/stage-view-in-jenkins.png)