Class 11:Terraform BIG-IP Provider 
==========================================
Introduction:
----------------------
The Terraform Lab provides a demo environment to get familiar with the solutionsthat F5 provides in security, performance, and visibility. Users can use this environment to try automation solutions, builddemos and proof of concepts. Using the scenarios provided, users will be able to experience how F5 adds value and integrates into your build environment seamlessly.

This Solution delivers a few common scenarios to help you learn more:

* Virtual server deployment with redirection of HTTP to HTTPS traffic to enforce secured connections
* Web server pool membership management as a server maintenance scenario
* A Web Application Firewall policy management with URL and IP adress blocking scenario

Best of all, these scenarios are all powered with simple Terraform template files  that require zero knowledge of F5 configuration. 


Solution Architecture:
-------------------------
The solution environment has two main components:

1.	F5 Sandbox Provisioner – powered by Terraform, this sets up the architecture and environment. The architecture is fairly simple with some key components such as a F5 BIG IP Virtual Edition instance, an Jump box running Terraform, and a pair of web servers. You can learn more about the provisioned components in the next page.

2.	Solution use cases – overlaid onto the environment are the specific solution demos referenced above. Over time, we’ll add more solution demos to the architecture. More documentation for each use case is available `here <https://clouddocs.f5.com/training/fas-as3-usecases/>`_.


.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Contents:
   

   1_step_aws_console
   2_aws_market_place
   module*/module*
   3_run_the_script
   4_ssh_into_ubuntu_server
   5_lets_review_aws 
   6_install_terraform
   7_review_tf
   7.1_review_tf
   7.2_review_tf
   8_review_json 
   9_terraform_commands
   10_terraform_commands
   11_how_to_test
   12_review_bigip
   12.1_review_bigip
   
Expected time to complete: **1 hour**

