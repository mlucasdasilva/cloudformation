# CloudFormation Templates  
  
  
Other references:  
  
https://github.com/awslabs/aws-academy-educator-toolkit  
  
  
  
## Subdirs:  
  
01 docker01-ec2-instance  
01 docker01-ec2-instance-generic  
02 docker-swarm-6-nodes  
03 vpc  
04 vpc export  
05 aws lab 5 ACAv1  
06 aws lab projeto 2 ACAv1  
07 Truenas  
08 lab docker swarm  
09 lab nginx keepalived  
10 lab k8s  
11 Glusterfs  
12 AWS SAM  
13 RDS  
14 Windows  
15 Centos  
97 Tests  
98 Dockerrun aws samples  
99 Userdata samples  
  
  
## CFT files:  
  
01 docker01-ec2-instance
  
01-docker01-resource-apenas.json  
01-docker01-resource-apenas.yml  
01-docker01-resource-e-description.json  
01-docker01-resource-e-description.yml  
01-docker01-resource-instance-e-sg.json  
01-docker01-resource-instance-e-sg.yml  
02- docker01-resource-e-description-with-eth0.json  
02- docker01-resource-e-description-with-eth0.yml  
03-docker01-with-eth0-mappings-e-parameters.json  
03-docker01-with-eth0-mappings-e-parameters.yml  
04-docker01-instance-e-template-with-eth0-with-mappings-e-parameters.json  
04-docker01-instance-e-template-with-eth0-with-mappings-e-parameters.yml  
05-docker01-instance-sg-e-templ-with-eth0-with-mappings-e-parameters.json  
05-docker01-instance-sg-e-templ-with-eth0-with-mappings-e-parameters.yml  
teste-cloudformation.json  
  
  
01 docker01-ec2-instance-generic  
  
01-docker01-instance-sg-mappings-parameters-generic.json  
02-docker01-instance-sg-parameters-generic.json  
02-docker01-instance-sg-parameters-generic.yml  
03-docker01-instance-sg-parameters-generic-outputs.yml  
04-docker01-instance-sg-parameters-generic-outputs-minhaweb.yml  
06-docker-3-instance-eth0-storage-AllTrafficsg-Vpc-3Pubsubnet-Unusedtempl.json  
  
  
02 docker-swarm-6-nodes  
  
01-docker-swarm-6-nodes.json  
01-docker-swarm-6-nodes.yml  
01b-docker-swarm-6-nodes-ips.yml  
02-docker-swarm-6-nodes-with-mappings-param.json  
02-docker-swarm-6-nodes-with-mappings-param.yml  
03-docker-swarm-6-nodes-vpc-and-public-subnets.json  
03-docker-swarm-6-nodes-vpc-and-public-subnets.yaml  
03-docker-swarm-6-nodes-vpc-and-public-subnets.yml  
04-docker-swarm-6-nodes-3az-sg-storage-eth0-templ-mappings-parameters.json  
05-docker-swarm-6-nodes-vpc-and-public-subnets.yml  
06-docker-swarm-6-nodes-and-nginx-1-node-vpc-and-public-subnets.yml  
07-docker-swarm-6-nodes-and-nginx-keepalived-2-nodes-vpc-and-public-subnets.yml  
  
  
03 vpc  
  
01-vpc template aws complete.json  
01-vpc template aws complete.yaml  
01-vpc template aws complete.yml  
02-vpc and 4 public subnets.json  
02-vpc and 4 public subnets.yaml  
02-vpc and 4 public subnets.yml  
  
  
04 vpc export  
  
01-vpc template aws complete (add export).json  
02-vpc and 4 public subnets (add export).json  
03-vpc and 4 public subnets (add export alias privatesubnet).json  
04-nat instance.yaml  
  
  
05 aws lab 5 ACAv1  
  
01-Lab5 lab-network-original.yaml  
02-Lab5 lab-application-original.yaml  
03-Lab5 lab-application2-original.yaml  
  
  
06 aws lab projeto 2 ACAv1  
  
01-add-instance project ACA 2.yaml  
02-add-instance project ACA 2(with AMIID).yaml  
  
  
07 Truenas  
  
01- instance truenas.yaml  
02- instances centos windows and aws linux2.yaml  
12-iSCSI instances centos windows and aws linux2.yaml  
13-iSCSI instances-truenas centos windows and aws linux2.yaml  
14-iSCSI instances truenas centos-target-and-initiator windows aws-linux2.yaml  
  
  
08 lab docker swarm  
  
01- 6 docker instances.yaml  
02- 6 docker instances e nfs.yaml  
03- 1 docker instance with userdata param.yaml  
04- 6 docker instances e nfs e userdata param.yaml  
05- 6 docker instances e nfs e elb e userdata param.yaml  
06- 6-docker-instances nfs app-elb net-elb userdata-param.yaml  
07- 1 simple instance aws linux2 docker.yaml  
08- 1 docker instance with userdata param sudoers.yaml  
09- 6 docker instances and swarm.yaml  
  
  
09 lab nginx keepalived  
  
01- nginx 2 instances install keepalived.yaml  
02- nginx 2 instances and config keepalived.yaml  
03- nginx 2 instances config keepalived and EIP.yaml  
  
  
10 lab k8s  
  
01- AWS IAM EKS Role K8s.yaml  
02- amazon-eks-nodegroup-role.yaml  
  
  
11 Glusterfs  
  
01-add instance centos.yaml  
02-add instance centos and ebs.yaml  
03-add instance centos-glusterfs and ebs.yaml  
04-add 3 instances centos-glusterfs and ebs.yaml  
  
  
12 AWS SAM  
  
01-aws-sam-cli-docker-instance-sg-parameters-generic-outputs.yml  
notas AWS SAM CLI - hello world.txt  
  
  
13 RDS\01- Rds Aurora.yaml  
  
  
14 Windows  
  
01- Windows instance.yaml  
02- Windows instance install my-workbench moba.yaml - Windows server instance with MySqlWorkBench and Moba-Xterm installed 
03- Windows instance user data param install myworkbench moba.yaml  
04- Windows instance user data param install myworkbench moba 5 ebs storage.yaml  
05- Windows instance user data param install myworkbench moba 10 ebs storage.yaml  
comandos ps.txt  
  
  
15 Centos\04- Centos7 instance user data param 10 ebs storage.yaml  
  
  
97 Tests\test import resources.json  
  
  
98 Dockerrun aws samples\Dockerrun-v2.aws.json  
98 Dockerrun aws samples\Dockerrun.aws.json  
98 Dockerrun aws samples\minhaweb.Dockerrun-v2.aws.json  
98 Dockerrun aws samples\minhaweb.Dockerrun.aws.json  
  
  
99 Userdata samples\userdata --ami amz2 --install docker compose git aws-cli-2 --start nginx.txt  
  
  