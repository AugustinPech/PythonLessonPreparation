## Generic Python DevOps Use Cases
- Python Script to query databases

        On a déjà mis en place des databases avec MariaDB et/ou en utilisant Adminer plusieurs fois, on en a déjà tous, en local. On peut peut-être requêter nos bases existantes ? On a tous 2-3 DB de boutique de E-Commerce (products / catégories / orders / users /...)
- Python script to execute a shell script and shell commands.

        On a fait beaucoup de terminal en Système et réseau avec Gerald. On a mis en place un server "distant" sur VM puis sur un VPS sur OVH-Cloud mais très peu d'élèves ont réellement travaillé sur OVH, et on n'a pas tous renouvelé l'abonnement. Par contre on a encore la VM.
        On a fait de la ligne de commande de base aussi, on sait tous mettre en place un vhost.
---
- Querying Splunk logs for specific alerting
- Python script to create Kafka Topics
- Python script to take backups.
- Python script for Kubernetes init containers to fetch secrets from the vault or other secrets management solutions.

        Dans ce bloc là (les 4 points précédents), je ne comprend pas de quoi on parle. 
---
- Python script to fetch IPs of live servers in an autoscaling group.

        je ne suis pas sur de comprendre mais on a déjà fait plusieurs manip' avec la table de routage. On sait faire du "port-forwarding" de base et mettre en place une connexion SSH
---
- Python AWS Lambda function to stop running instances on weekends.
- Python script for ETL jobs.
- Find SSL expiry date using python

        pareil, je ne comprend pas de quoi on parle dans les 3 poitns précédents.
---
- Develop custom CLI applications using Python

        en théorie tout le monde sait ce que c'est un CLI mais franchement ...je pense que c'est pas claire pour tout le monde
- CRUD operations using Python for databases.

        on en a déjà un peu parlé (voir point 1) on a déjà fait un CRUD en PHP vanilla.
- Custom scripts while using configuration management tools.

        c'est un peu trop technique pour nous je pense...
## Cloud-Specific Python Use Cases

        On n'a pas de compte AWS et on n'a encore aucunes bases
When working on cloud environments, you might need custom automation scripts as part of Infrastructure as code implementations. Let’s take a look at some real-world cloud-specific Python use cases.

- Provision AWS resources using Python AWS CDK.
- Use Boto3 modules to manage AWS services.
    - Python Boto3 program to manage AWS ec2 instances.
    - Python Boto3 program to manage AWS S3 Storage.
    - Python Boto3 program to retrieve secrets from parameter store and secrets manager.
## Kubernetes-Specific Python Use Cases
        
        à part Jamil qui a la certif' Kubernetes , on n'a aucunes bases
Many devops engineers had this question of how to leverage Python knowledge with Kubernetes.

Following are the tasks you can do with Python for while learning Kubernetes

- Start by creating Python programs to interact with Kubernetes APIs using various authentication mechanisms. (Token, Certificates, etc)
- Try running custom Python scripts with init containers to modify a file that a container requires during runtime.
- Write a custom webhook using Python Flask API for Kubernetes Validating and Mutating Admission controllers.
- Consider writing a Kubernetes operator in Python using the Kopf framework. An example use case for a custom Kubernetes operator could be to automate the backup of etcd to Amazon S3. You can use the kopf python framework
