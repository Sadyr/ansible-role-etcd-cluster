Role Name
=========


Requirements
------------

Role Variables
--------------
etcd_setup_type: "single" #[single | cluster] #Define setup is single instance etcd or it is cluster.
etcd_cluster_setup_method: "static" #[ statis | discovery | dns_discovery ] # Define method to setup the cluster
etcd_initial_cluster: []

etcd_initial_cluster_token: infra-postgresql




Dependencies
------------


Example Playbook
----------------


License
-------
Author Information
------------------
