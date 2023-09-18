#Role Name: get_azure_policy_data
#=========

#A brief description of the role goes here.

#The role get_azure_policy_data should be run by calling the playbook
#get_azure_policy_data.yml
#
#That playbook runs and calls the get_azure_policy_data role and creates a
#data file in "files/azure_policies.json".
#
#This file is later referenced and read by the export_azure_policies.yml playbook.
#
#The data file will contain data from your azure account - this data include 
#your azure policy definitions and their respective categories. 

 
#Requirements
#------------
#To run the playbook you need to have the Azure.Azcollection installed in your 
#ansible controller (or execution environment).
#
#You also must create and use the appropriate azure credentials (with the appropriate 
#role assignments) set up in your "azure/credentials" file (or in your 
#azure resource manager credential in AAP - Ansible Automation Platform)


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
