# MAP REDUCE CLUSTER CONFIGURED USING ANSIBLE:


- vars/secret.yaml:
  ----------------
  
     AWS_ACCESS_KEY_VAL: AWS ACCESS KEY

     AWS_SECRET_KEY_VAL: AWS SECRET KEY


- vars/instance_vars.yaml:
  -----------------------

 	key: KEY NAME

	type_instance: t2.micro

	subnet_id: SUBNET ID

	region_id: ap-south-1

	security_group_id: SECURITY GROUP ID

	inventory_path: inventory

	ami_id: ami-068d43a544160b7ef

	has_public_ip: true


### Create files/ folder and download the following files in that folder:

-> [Oracle jdk 8](https://javadl.oracle.com/webapps/download/AutoDL?BundleId=244574_d7fc238d0cbf4b0dac67be84580cfb4b)

-> [hadoop 1.2.1-1](https://archive.apache.org/dist/hadoop/core/hadoop-1.2.1/hadoop-1.2.1-1.x86_64.rpm) 
        
-> [hive](https://downloads.apache.org/hive/hive-1.2.2/apache-hive-1.2.2-bin.tar.gz)



## HOW TO RUN THIS ANSIBLE PLAYBOOKS:

 - Run the ec2_config.yaml file first. 
   > ansible-playbook ec2_config.yaml
 
 - Run the tasks/main.yaml file only. 
   > ansible-playbook tasks/main.yaml
