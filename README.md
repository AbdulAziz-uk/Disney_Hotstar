# **Welcome to the Hotstar App Deployment project tutorial!**
### **This project demonstrates how to deploy a Hotstar application on Kubernetes cluster using various DevOps tools.**

## 🤝 **Connect with Me:  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdulazizuk/)**

### Lets start deploying Hostart App

<ul>
<li><a title="Deployment of Disney Hotstar App in Kubernetes using Github+Jenkins+Sonarqube+npm+nodejs+trivy+docker+Terraform+Grafana+SSL" href="https://stardistributors.co.uk/devops/devops_tools/projects/disney_hotstar/disney_hotstar1.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/disney_hotstar/disney_hotstar1.jpg" alt="" width="644" height="352" /></a></li>
<li>Tools &amp; Services used:
<ul>
<li>
<table border="black">
<thead>
<tr>
<th><strong>Category</strong></th>
<th><strong>Tools</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Version Control</strong></td>
<td><img src="https://stardistributors.co.uk/devops/devops_tools/projects/disney_hotstar/github.jpg" alt="" width="63" height="20" /></td>
</tr>
<tr>
<td><strong>CI/CD</strong></td>
<td><a href="https://camo.githubusercontent.com/22b41fadf98ee5a0e46a1d3fb90d563272cf908e9fdc7d6f6f25e70145a9afb7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a656e6b696e732d4432343933393f7374796c653d666c61742d737175617265266c6f676f3d6a656e6b696e73266c6f676f436f6c6f723d7768697465" target="_blank" rel="noopener noreferrer nofollow"><img src="https://camo.githubusercontent.com/22b41fadf98ee5a0e46a1d3fb90d563272cf908e9fdc7d6f6f25e70145a9afb7/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a656e6b696e732d4432343933393f7374796c653d666c61742d737175617265266c6f676f3d6a656e6b696e73266c6f676f436f6c6f723d7768697465" alt="Jenkins" data-canonical-src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&amp;logo=jenkins&amp;logoColor=white" /></a></td>
</tr>
<tr>
<td><strong>Code Quality</strong></td>
<td><a href="https://camo.githubusercontent.com/4cf21d11d2fb1a75b253215cd0ae2c5002f72b868b12a0e4f5d61faabcbb5198/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f536f6e6172517562652d3445394243443f7374796c653d666c61742d737175617265266c6f676f3d736f6e617271756265266c6f676f436f6c6f723d7768697465" target="_blank" rel="noopener noreferrer nofollow"><img src="https://camo.githubusercontent.com/4cf21d11d2fb1a75b253215cd0ae2c5002f72b868b12a0e4f5d61faabcbb5198/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f536f6e6172517562652d3445394243443f7374796c653d666c61742d737175617265266c6f676f3d736f6e617271756265266c6f676f436f6c6f723d7768697465" alt="SonarQube" data-canonical-src="https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&amp;logo=sonarqube&amp;logoColor=white" /></a></td>
</tr>
<tr>
<td><strong>Containerization</strong></td>
<td><a href="https://camo.githubusercontent.com/bfb7555b6d85ca0d42c2c2e6a741cd9f5b9b1d7bb95535450f1afd2558554f86/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f636b65722d3234393645443f7374796c653d666c61742d737175617265266c6f676f3d646f636b6572266c6f676f436f6c6f723d7768697465" target="_blank" rel="noopener noreferrer nofollow"><img src="https://camo.githubusercontent.com/bfb7555b6d85ca0d42c2c2e6a741cd9f5b9b1d7bb95535450f1afd2558554f86/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f636b65722d3234393645443f7374796c653d666c61742d737175617265266c6f676f3d646f636b6572266c6f676f436f6c6f723d7768697465" alt="Docker" data-canonical-src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" /></a></td>
</tr>
<tr>
<td><strong>Orchestration</strong></td>
<td><a href="https://camo.githubusercontent.com/903b7f99682bb0c52aba2280e5b8e7ad5dce587908eb4d79ad0a9491f8b6a366/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4b756265726e657465732d3332364345353f7374796c653d666c61742d737175617265266c6f676f3d6b756265726e65746573266c6f676f436f6c6f723d7768697465" target="_blank" rel="noopener noreferrer nofollow"><img src="https://camo.githubusercontent.com/903b7f99682bb0c52aba2280e5b8e7ad5dce587908eb4d79ad0a9491f8b6a366/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4b756265726e657465732d3332364345353f7374796c653d666c61742d737175617265266c6f676f3d6b756265726e65746573266c6f676f436f6c6f723d7768697465" alt="Kubernetes" data-canonical-src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&amp;logo=kubernetes&amp;logoColor=white" /></a></td>
</tr>
<tr>
<td><strong>Monitoring</strong></td>
<td><a href="https://camo.githubusercontent.com/275efecee0c790e50cbfd5b8584e831774bd858dbb2cfd21245718ec1739496f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50726f6d6574686575732d4536353232433f7374796c653d666c61742d737175617265266c6f676f3d70726f6d657468657573266c6f676f436f6c6f723d7768697465" target="_blank" rel="noopener noreferrer nofollow"><img src="https://camo.githubusercontent.com/275efecee0c790e50cbfd5b8584e831774bd858dbb2cfd21245718ec1739496f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50726f6d6574686575732d4536353232433f7374796c653d666c61742d737175617265266c6f676f3d70726f6d657468657573266c6f676f436f6c6f723d7768697465" alt="Prometheus" data-canonical-src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&amp;logo=prometheus&amp;logoColor=white" /></a>&nbsp;<a href="https://camo.githubusercontent.com/52544223293f79c77382af85717e1878a63bb6e136e1c01a211e9ee36bcccdf5/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f47726166616e612d4634363830303f7374796c653d666c61742d737175617265266c6f676f3d67726166616e61266c6f676f436f6c6f723d7768697465" target="_blank" rel="noopener noreferrer nofollow"><img src="https://camo.githubusercontent.com/52544223293f79c77382af85717e1878a63bb6e136e1c01a211e9ee36bcccdf5/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f47726166616e612d4634363830303f7374796c653d666c61742d737175617265266c6f676f3d67726166616e61266c6f676f436f6c6f723d7768697465" alt="Grafana" data-canonical-src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&amp;logo=grafana&amp;logoColor=white" /></a></td>
</tr>
<tr>
<td><strong>Security</strong></td>
<td><a href="https://camo.githubusercontent.com/1327fc88dfba2bb5ac45e047e4a9feeee31114b21ca2cba95013d9e58363ba26/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4f574153502d3030303030303f7374796c653d666c61742d737175617265266c6f676f3d6f77617370266c6f676f436f6c6f723d7768697465" target="_blank" rel="noopener noreferrer nofollow"><img src="https://camo.githubusercontent.com/1327fc88dfba2bb5ac45e047e4a9feeee31114b21ca2cba95013d9e58363ba26/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4f574153502d3030303030303f7374796c653d666c61742d737175617265266c6f676f3d6f77617370266c6f676f436f6c6f723d7768697465" alt="OWASP" data-canonical-src="https://img.shields.io/badge/OWASP-000000?style=flat-square&amp;logo=owasp&amp;logoColor=white" /></a>&nbsp;<a href="https://camo.githubusercontent.com/67015341784fba0b9eed4975dd6b0bbca63d21f5824b7b7c833faf758e61c56f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f54726976792d3030393739443f7374796c653d666c61742d737175617265266c6f676f3d7472697679266c6f676f436f6c6f723d7768697465" target="_blank" rel="noopener noreferrer nofollow"><img src="https://camo.githubusercontent.com/67015341784fba0b9eed4975dd6b0bbca63d21f5824b7b7c833faf758e61c56f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f54726976792d3030393739443f7374796c653d666c61742d737175617265266c6f676f3d7472697679266c6f676f436f6c6f723d7768697465" alt="Trivy" data-canonical-src="https://img.shields.io/badge/Trivy-00979D?style=flat-square&amp;logo=trivy&amp;logoColor=white" /></a></td>
</tr>
<tr>
<td><strong>IAC</strong></td>
<td><a href="https://camo.githubusercontent.com/578ea379c69d266708eb9bc08774d4ca35814bf5c0456065e46e4dca29ee74f0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5465727261666f726d2d3632334345343f7374796c653d666c61742d737175617265266c6f676f3d7465727261666f726d266c6f676f436f6c6f723d7768697465" target="_blank" rel="noopener noreferrer nofollow"><img src="https://camo.githubusercontent.com/578ea379c69d266708eb9bc08774d4ca35814bf5c0456065e46e4dca29ee74f0/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5465727261666f726d2d3632334345343f7374796c653d666c61742d737175617265266c6f676f3d7465727261666f726d266c6f676f436f6c6f723d7768697465" alt="Terraform" data-canonical-src="https://img.shields.io/badge/Terraform-623CE4?style=flat-square&amp;logo=terraform&amp;logoColor=white" /></a></td>
</tr>
</tbody>
</table>
</li>
</ul>
</li>
<li>Code Repository:
<ul>
<li><a href="https://github.com/AbdulAziz-uk/Disney_Hotstar.git" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/disney_hotstar/github.jpg" alt="" width="63" height="20" /></a>&nbsp;https://github.com/AbdulAziz-uk/Disney_Hotstar.git</li>
</ul>
</li>
<li>Project Management Tool: Jira
<ul>
<li>link code repository from github</li>
</ul>
</li>
  <li><details><summary>Create a Ubuntu VM on AWS</summary>
<ul>
<li>Name=hotstar</li>
<li>o/S : ubuntu server 24.04 LTS (HVM), SSD Volume Type</li>
<li>Instance type: t3 large</li>
<li>keypair: generate .pem</li>
<li>15 GB</li>
<li>Security: Allow ports SSH, http, https, 8080(jenkins), 9000 (sonarqube), 587(gmail-smtp, 465 (gmail)</li>
<li>open MobXterm and connect to VM</li>
<li>Get VM details:
<ul>
<li>root@ip:/home/ubuntu#hostnamectl</li>
</ul>
</li>
</ul>
</li>
<li><details><summary>Clone the repository using git.&nbsp; Git is installed by default in ubuntu, if not install it.</summary>
<ul>
<li>root@ip:/home/ubuntu#git&nbsp;-v</li>
<li>Install git:&nbsp;</li>
<li>root@ip:/home/ubuntu#sudo apt update</li>
<li>root@ip:/home/ubuntu#sudo apt install git</li>
<li>Clone</li>
<li>root@ip:/home/ubuntu#git&nbsp;clone&nbsp;<a href="https://github.com/AbdulAziz-uk/Disney_Hotstar.git">https://github.com/AbdulAziz-uk/Disney_Hotstar.git</a></li>
<li>root@ip:~Disney_Hotstar/Scripts#ls&nbsp;(list of scripts )</li>
</ul>
</li>
<li><details><summary>Install the following tools using script, check scripts in github.&nbsp;&nbsp</summary>
<ul>
<li>Give executable permission to all scripts:</li>
<li>root@ip:~Disney_Hotstar/Scripts#sudo&nbsp;chmod +x *.sh</li>
<li>root@ip:~Disney_Hotstar/Scripts#&nbsp;ll (all scrits in green coloured, can be execute)</li>
<li>Install Jenkins:&nbsp;
<ul>
<li>root@ip:~Disney_Hotstar/Scripts#sh&nbsp;jenkins.sh</li>
<li>Java is installed along with jenkins, check&nbsp;</li>
<li>root@ip:~Disney_Hotstar/Scripts#java&nbsp;--version</li>
<li>#systemctl status jenkins</li>
<li>#systemctl enable jenkins (it will enable jenkins and start after vm restart)</li>
<li>Acces jenkins:</li>
<li>opne browser: <a href="http://ip:8080">http://ip:8080</a></li>
<li>Reveal password from the following path</li>
<li>#sudo cat /var/lib/jenkins/secrets/initialAdminPassword</li>
<li>Install default plugins</li>
</ul>
</li>
<li>Install docker
<ul>
<li>root@ip:~Disney_Hotstar/Scripts#sh docker.sh</li>
<li>root@ip:~Disney_Hotstar/Scripts#docker&nbsp;-v</li>
<li>root@ip:~Disney_Hotstar/Scripts#systemctl&nbsp;status docker</li>
<li>check the script for all the commands defined like adding user to docker group, giving permission, setting port etc.&nbsp;</li>
</ul>
</li>
<li>Install SonarQube container &amp; generate token:
<ul>
<li>Run SonarQube container in detached mode with port mapping 9000</li>
<li>cname sonar -p 9000:9000 sonarqube:lts-community</li>
<li>#docker container ls (list of containers, sonar container is running)</li>
<li>#docker images (list of images)</li>
<li>Access sonar:</li>
<li>open browser <a href="http://ip:9000">http://ip:9000</a></li>
<li>default username=admin, password=admin</li>
<li>Generate Sonar token for the user, which will be use while integration with jenkins.</li>
<li>Administrtion/security/users/token/Generate Token/ Name=sonar-token, expires in = 60 days and generate.&nbsp; copy token.</li>
</ul>
</li>
<li>Install kubectl container for kubernetes cluster.
<ul>
<li>root@ip:~Disney_Hotstar/Script#sh&nbsp;kubectl.sh</li>
</ul>
</li>
<li>Install AWS cli: To communicate with AWS
<ul>
<li>root@ip:~Disney_Hotstar/Script#sh&nbsp;awscli.sh</li>
</ul>
</li>
<li>Install Trivy:
<ul>
<li>root@ip:~Disney_Hotstar/Script#sh trivy.sh</li>
<li>#trivy -v</li>
</ul>
</li>
<li>Install Terraform:
<ul>
<li>root@ip:~Disney_Hotstar/Script#sh terraform.sh</li>
</ul>
</li>
</ul>
</li>
  <li><details><summary>Install plugins in Jenkins:</summary>
<ul>
<li>Go to Manage Jenkins/Plugins/ search and install the following plugins</li>
<li>Eclipse Temurin installer (it will install jdk)</li>
<li>Sonaraube scanner for jenkins</li>
<li>Nodejs Plugin</li>
<li>OWASP Dependency-Check</li>
<li>stage view</li>
<li>Blue ocean</li>
<li>Docker</li>
<li>Docker commons</li>
<li>docker pipeline</li>
<li>docker api</li>
<li>docker-build-step</li>
<li>terraform</li>
<li>restart jenkins: http://ip/8080/restart</li>
</ul>
</li>
  <li><details><summary>Integrate Jenkins with SonarQube</summary>
<ul>
<li>First add the server sonarqube in jenkins
<ul>
<li>Go to Manage Jenkins/System scroll down to Sonar Qube servers</li>
<li>Add SonarQube</li>
<li>Name = sonar</li>
<li>Server URL= <a href="http://192.168.171.200:9000">http://192.168.171.200:9000</a></li>
<li>Server authentication token: click +add
<ul>
<li>Domain = Global credentials (unrestricted)</li>
<li>Kind = secret text</li>
<li>scope: Glonal (jenkins,nodes, items, all child items,etc)</li>
<li>Seccret=past the token which was generated in sonarqube insallation</li>
<li>ID=sonar-token</li>
<li>Description=sonar-token</li>
<li>Add</li>
</ul>
</li>
<li>In Server Authentication token: click drop down and select sonar-token</li>
<li>apply &amp; save</li>
</ul>
</li>
</ul>
</li>
  <li><details><summary>Configure Tools in jenkins (jdk, maven, sonarqube, trivy, terraform)</summary>
<ul>
<li>Go to Manage Jenkins/Tools:</li>
<li>JDK
<ul>
<li>Name=jdk17</li>
<li>Install automatically and click add installer and select install from adoptium.net</li>
<li>select version jdk-17.0.9+9</li>
</ul>
</li>
<li>SonarQube Scanner Installations
<ul>
<li>click Add SonarQube Scanner</li>
<li>Name = sonar-scanner</li>
<li>Version = Install from Maven Central and select latest/required version</li>
</ul>
</li>
<li>NodeJS installations:
<ul>
<li>Add NodeJs</li>
<li>Name=nodejs</li>
<li>select install automatically</li>
<li>Version= Install from nodejs.org and select version 17.9.0</li>
</ul>
</li>
<li>Dependency Check installation
<ul>
<li>Add Dependency-Check</li>
<li>Name=DC</li>
<li>install automatically</li>
<li>Add installer - select install from github.com</li>
<li>version = dependency-check 12.1.0</li>
<li>apply &amp; save</li>
</ul>
</li>
</ul>
</li>
  <li><details><summary>Create CICD Pipeline</summary>
<ul>
<li>New item, Name=hotstar and select pipeline and ok</li>
<li>Descripton= Bingo pipeline</li>
<li>Discard old Builds = max # of builds to keep = 3</li>
<li>pipeline: Definition=pipeline script (declarative script)<br />
<ul>
<li>click for yaml code.</li>
<li>
<div>
<div>pipeline {</div>
<div>&nbsp; agent any</div>
<div>&nbsp; &nbsp;tools {</div>
<div>&nbsp; &nbsp; jdk 'jdk17'</div>
<div>&nbsp; &nbsp; nodejs 'nodejs'</div>
<div>&nbsp; }</div>
<div>&nbsp; environment {</div>
<div>&nbsp; &nbsp; SONARQUBE_HOME=tool 'sonar-scanner'</div>
<div>&nbsp; }</div>
<div>&nbsp; stages {</div>
<div>&nbsp; &nbsp; stage ('clean workspace'){</div>
<div>&nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; cleanWs()</div>
<div>&nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; stage ('Git Clone') {</div>
<div>&nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; git branch:'main', url:'https://github.com/AbdulAziz-uk/Disney_Hotstar.git'</div>
<div>&nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; stage ('Sonar Analysis'){</div>
<div>&nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; withSonarQubeEnv('SonarQube'){</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh ''' $SONARQUBE_HOME/bin/sonar-scanner -Dsonar.projectName=hotstar \</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -Dsonar.projectKey=hotstar '''</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; stage ('quality gate'){</div>
<div>&nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; script {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; waitForQualityGate abortPipeline:false, credentialsId:'sonar-token'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; stage ('Install Dependencies'){</div>
<div>&nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; sh "npm install"</div>
<div>&nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; stage ('OWASP FS Scan'){</div>
<div>&nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; dependencyCheck additionalArguments:'--scan ./ --disableYarnAudit --disableNodeAudit --nvdapiKey 36883b57-9d9d-4677-b466-f7012f883687', odcInstallation:'DC'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; dependencyCheckPublisher pattern:'**/dependency-check-report.xml'</div>
<div>&nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; stage ('Trivy FS Scan'){</div>
<div>&nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; sh "trivy fs . &gt; trivyfs.txt"</div>
<div>&nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; stage ('Docker Build &amp; Push'){</div>
<div>&nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; script {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; withDockerRegistry(credentialsId:'docker', toolName:'docker'){</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh "docker build -t hotstar ."</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh "docker tag hotstar aziz27uk/hotstar:latest"</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh "docker push aziz27uk/hotstar:latest"</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; stage ('Trivy'){</div>
<div>&nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; sh "trivy image aziz27uk/hotstar:latest &gt; trivyimage.txt"</div>
<div>&nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; stage ('Deploy to Container'){</div>
<div>&nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; sh 'docker run -d --name hotstar -p 3000:3000 aziz27uk/hotstar:latest'</div>
<div>&nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; }</div>
<div>}</div>
</div>
</li>
<li>Build now: Jenkins will clone the files from github to workspaces, path in VM will be&nbsp; (/var/jenkins/workspace/hotstar)</li>
<li>disney_hotstar2.jpg</li>
</ul>
</li>
<li>Access appliation:
<ul>
<li>http://ip:3000</li>
</ul>
</li>
</ul>
</li>
<li>Code</li>
<li>Code</li>
</ul>
</details></li>




