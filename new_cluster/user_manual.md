## Login

All users must login through the entrypoint: admin (LAN IP: 10.10.7.160).

Note that user must login from Shanghaitech Local Network. 

External access (WAN) to the cluster is disabled.

Shell Command: 
ssh username@10.10.7.160

Example: 
ssh rao@10.10.7.160

## User Guide

By regulation, all computing job must proceed through the PBS system. 
Running high workload program on the admin node is highly discoveraged.
The details of PBS system can be found in qsub-tutorial.ppt in this repository.

## Home Directory

By configuration, all users have a home directory mounted to whatever node he/she is currently using.

The path of this home directory will always be: ~

To navigate from any directory to home, type the following command: cd ~

Note that the content of the home directory will be synchronized across all nodes.

## Login from Entrypoint To Other Nodes

This is forbidden

## Access External Network Resources (Internet)

This is enabled