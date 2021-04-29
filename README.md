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


### In files folder download:
    ------------------------

-> [Oracle jdk 8](https://download.oracle.com/otn/java/jdk/8u291-b10/d7fc238d0cbf4b0dac67be84580cfb4b/jdk-8u291-linux-x64.rpm)

-> [hadoop 1.2.1-1](https://archive.apache.org/dist/hadoop/core/hadoop-1.2.1/hadoop-1.2.1-1.x86_64.rpm) 
        
-> [hive](https://downloads.apache.org/hive/hive-1.2.2/apache-hive-1.2.2-bin.tar.gz)
