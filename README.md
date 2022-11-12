# Jenkins on Kubernetes by Helm Charts 	
## Requirements:
**You must install on your machine:**<br>
* [Helm](https://helm.sh/docs/intro/install/)
* [kubectl](https://kubernetes.io/docs/tasks/tools/)
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

**On Kubernetes cluster create a namespace called 'jenkins'**<br>
~~~
kubectl create namespace jenkins
~~~

**Clone this repo to your local**<br>
~~~ 
git clone https://github.com/JozNeto/jenkins-kubernetes-helm-charts.git
~~~
**Run Helm comand**<br>
~~~ 
helm install jenkins-for-lab -n jenkins jenkins/
~~~

