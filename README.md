### PRIVATE PROJECTS DONE :

**Deployed a voting application on AWS, AZURE and GCP using the below microservices:**
1. voting-app - Python                    
2. result-app - Node.js                                                                       
3. in-memory db - Redis               
4. db - Postgresql
5. worker - .NET

- Containerized the above microservices in docker 
- Have used links when using the docker run to connect the microservices with each other as app is dependent on db
- Created images of them pushed to DockerHub and deployed them Kubernetes using the respective manifest files written
- Implemented the auto-scaling functionality using Deployments as a kind to the above setup  

**Deployed the above listed voting application microservices on OpenShift:**

- Build Python, Postgresql and  Node.js directly in dashboard using the default Catalog items
- Build Redis using a template by importing a JSON file 
- Above two build using Source Build Strategy
- Build .NET as a java application using Docker Build Strategy

**Deploying Nginx application using Google Kubernetes Engine:**

- Configuring Clusters using Google Cloud Platform
- Deploying and exposing Nginx container using Services and Ingress
- Accessing Nginx website using Endpoints

**Deployed a simple Python application from GitLab repository on OpenShift**

**Deployed a chat bot on Telegram using a Python application**

**Deployed a chat bot on Slack using a Node.js application**

**Performed REST API testing for HTTP methods on Car Fleet Management application using Postman**



