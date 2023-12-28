## **Documentation for Project 14**

### Configuring our Ansible Project For Jenkins Deployment using Blue Ocean Jenkins Plugin

### Jenkins Blue Ocean Plugin Installation

![Blue-Ocean-Installation](./Images/blue-ocean-jenkins-plugin-installation-success.png)

![Blue-Ocean-Installation-success](./Images/jenkins-blue-ocean-for-pipeline-creation.png)

### Creating a new pipeline in blue Ocean

![creating-a-new-pipeline-with-blue-ocean](./Images/creating-a-new-pipeline-in-blue-ocean.png)

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

## Deploying with Ansible by Running Ansible Playbook From Jenkins

### Ansible Installation on Jenkins CI Server

![stage-view-in-Jenkins](./Images/ansible-installation-on-jenkins.png)

### Ansible plugin installation on Jenkins UI

![ansible-plugin-installation-on-Jenkins-ui](./Images/ansible-plugin-installation-on-Jenkins-ui.png)

### Adding our Credentials on Jenkins so that it will be able to run our play book

![adding-ssh-credentials-for-jenkins-to-run-ansible-playbook](./Images/adding-ssh-credentials-for-jenkins.png)

### Specifying the path to our ansible interpreter on jenkins so it can build project

![specifying-ansible-interpreter-path-to-jenkins](./Images/specifying-ansible-interpreter-path-to-jenkins-for-building-project.png)

### Generating Pipeline script to run ansible playbook from Jenkins

![generating-pipeline-script](./Images/generating-pipeline-script.png)

### Defining a global ansible config for jenkins

![global-ansible-config-file-for-jenkins](./Images/global-ansible-config-file-for-jenkins.png)

### Running Playbook from Jenkins

![playbook-run-from-jenkins-A](./Images/playbook-run-from-jenkins-A.png)

![playbook-run-from-jenkins-B](./Images/playbook-run-from-jenkins-B.png)

### Parameterizing our Jenkins file to make our CI Environment Dynamic by removing the hardcoded value for our inventory and making the inventory variable dynamic

![parameterizing-our-jenkins-file](./Images/parameterizing-our-jenkins-file.png)

![building-with-parameter](./Images/building-with-parameter.png)

## Pipeline for Todo Application

### Deploying Todo Applications Onto Servers using Artifactory

#### Forking ToDo Application into our Github account or on our Jenkins Server

`git clone https://github.com/darey-devops/php-todo.git`

![cloning-php-Todo-Application](./Images/cloning-php-Todo-Application.png)

### Installing the necessary Dependencies to successfully deploy our Php Application and omposer tool.

`sudo yum module reset php -y`
`sudo yum install -y php php-common php-mbstring php-opcache php-intl php-xml php-gd php-curl php-mysqlnd php-fpm php-json`
`sudo dnf install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm`
`sudo dnf module install php:remi-7.4`
`sudo dnf --enablerepo=remi install php-phpunit -phploc`
`sudo wget -O phpunit https://phar.phpunit.de/phpunit-7.phar`
`chmod +x phpunit`
`sudo yum install php-xdebug`
`sudo yum install zip`

### php Composer
`sudo curl -sS https://getcomposer.org/installer | php`
`sudo mv composer.phar /usr/bin/composer`

![Installing-php-dependencies](./Images/Installing-php-dependencies.png)

### Installing Plot Plugin and Artifactory Plugin on Jenkins

![plot-and-artifactory-plugin-installation](./Images/plot-and-artifactory-plugin-installation.png)

### Installing artifactory on an artifactory server using ansible playbook role

![artifactory-installation-via-playbook](./Images/artifactory-installation-via-playbook.png)

### Jfrog Live on port 8081
![artifactory-live-on-port-8082](./Images/artifactory-live-on-port-8082.png)

### Configuring Jfrog Artifactory in jenkins UI via installed Artifactory Plugin

![artifactory-configuration-in-jenkins](./Images/artifactory-configuration-in-jenkins.png)

### Integrating Artifactory repository with Jenkins

### Creating a dummy Jenkins file in Phptodo Repo

![creating-a-dummy-Jenkinsfile-in-phptodo-repo](./Images/creating-a-dummy-Jenkinsfile-in-phptodo-repo.png)

### Creating a Database and User on DB server using ansible playbook mysql role

![database-and-database-user-created](./Images/database-and-database-user-created.png)

![database-and-database-user-created](./Images/Database-created.png)

### Creating a Multi-Branch Jenkins Pipeline Using Blue Ocean

![multi-branch-pipeline-created](./Images/multi-branch-pipeline-created.png)

### Prepare Dependency stage Script from our Jenkinsfile in our our phptodo app using 'mv .env.sample .env' shell to rename .env.sample to .env , composer install shell to install all the dependent libraries used by the application and php artisan shell to setup the required database objects

![prepare-dependencies-stage-in-action](./Images/prepare-dependencies-stage-in-action.png)

### Updating our Jenkins File to Include unit test stage, code quality analysis stage and archiving our application code to upload into artifactory and Publishing it to Artifactory

![unit-test-code-quality-and-upload-to-artifactory-update](./Images/unit-test-code-quality-and-upload-to-artifactory-update.png)

![unit-test-code-quality-and-upload-to-artifactory-update-2](./Images/unit-test-code-quality-and-upload-to-artifactory-update-2.png)

### Deploying our code artifacts to artifactory server

![code-deployed-to-artifactory-server](./Images/code-deployed-to-artifactory-server.png)

### Artifacts live on artifactory server

![artifacts-live-on-artifactory-server](./Images/artifacts-live-on-artifactory-server.png)

### Plot Menu

![plot-menu](./Images/plot-menu.png)

### Deploying our php-todo application to todo server in Dev Environment

![Deploying-to-dev-environment](./Images/Deploying-to-dev-environment.png)

### php-todo application successfully deployed on todo server in Dev Environment

![successful-deployment-on-our-todo-server-1](./Images/successful-deployment-on-our-todo-server-1.png)

![successful-deployment-on-our-todo-server-2](./Images/successful-deployment-on-our-todo-server-2.png)#

### php-todo application live on todo server

![php-todo-application-live-on-todo-server](./Images/php-todo-application-live-on-todo-server.png)

### Installing Sonarqube using downloaded sonarqube role from ansible galaxy

![sonarqube-installation-via-downloaded-sonarqube-role](./Images/sonarqube-installation-via-downloaded-sonarqube-role.png)

### Installing ansible community role for postgresql installation

![ansible-community-role-for-postgresql-installation](./Images/ansible-community-role-for-postgresql-installation.png)

### Postgresql installation

![postgresql-10-installation](./Images/postgresql-10-installation.png)